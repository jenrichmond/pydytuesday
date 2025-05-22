This repo contains my rudimentary attempts to use python to make something with TidyTuesday data. 


reminder re how to read TidyTuesday using python

Option 1: pydytuesday python library

import pydytuesday
import pandas as pd

downloads files from the week, which you can then read in locally

pydytuesday.get_date('2025-05-20')

Option 2: Read directly from GitHub URL and assign to an object

water_quality = pandas.read_csv('https://raw.githubusercontent.com/rfordatascience/tidytuesday/main/data/2025/2025-05-20/water_quality.csv')

