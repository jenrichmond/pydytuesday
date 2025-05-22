This repo contains my rudimentary attempts to use python to make something with TidyTuesday data. 


reminder re how to read TidyTuesday using python


# Using Python
# Option 1: pydytuesday python library
## pip install pydytuesday

import pydytuesday
import pandas as pd

# Download files from the week, which you can then read in locally

pydytuesday.get_date('2025-05-20')

# Option 2: Read directly from GitHub and assign to an object

water_quality = pandas.read_csv('https://raw.githubusercontent.com/rfordatascience/tidytuesday/main/data/2025/2025-05-20/water_quality.csv')

