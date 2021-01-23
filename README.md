# 244-assignment-1

## Task 1 (individual): Data wrangling & visualization (Sierra amphibians)

For Task 1, you will read in data an .xlsx file, do some data wrangling as needed, then create two data visualizations and put them together in a finalized compound figure (e.g. using the {patchwork} package introduced in the Week 2 Lab).

**Data summary:** You will explore amphibian abundance data recorded by the Sierra Lakes Inventory Project. From the Environmental Data Initiative repository: “The Sierra Lakes Inventory Project (SLIP) was a research endeavor that ran from 1995-2002 and has supported research and management of Sierra Nevada aquatic ecosystems and their terrestrial interfaces. We described the physical characteristics of and surveyed aquatic communities for > 8,000 lentic water bodies in the southern Sierra Nevada, including lakes, ponds, marshes, and meadows.”

**Data citation:** Knapp, R.A., C. Pavelka, E.E. Hegeman, and T.C. Smith. 2020. The Sierra Lakes Inventory Project: Non-Native fish and community composition of lakes and ponds in the Sierra Nevada, California ver 2. Environmental Data Initiative. https://doi.org/10.6073/pasta/d835832d7fd00d9e4466e44eea87fab3

**Complete Task 1** in a single well-organized .Rmd. Read in the amphibian data (sierra_amphibians.xlsx), then do any wrangling necessary to create two finalized data visualizations:

## Task 2 (individual): Principal components analysis (coder’s choice)

For this task, I’ll provide a couple of datasets that you can use for PCA exploration, but you are also welcome to find/choose a different dataset to use. You only need to use one dataset to perform PCA, create a biplot, and interpret the results. Whichever dataset you choose, create a finalized HTML (knitted from .Rmd) that includes: 

- A useful descriptive introductory summary (3 - 4 sentences) that helps the audience understand the data (include a citation as necessary) and what you’ll be exploring
- All of your organized and well-annotated code (with warnings/messages suppressed) you wrote to wrangle data then run PCA, and to create a professional looking PCA biplot that appears (with a caption) in your knitted HTML
- A brief summary (nicely formatted and professionally written bulletpoints are fine) highlighting some major takeaways from your PCA that can be gleaned from the biplot

**Data:** Food nutrient information for raw fruits and veggies from USDA (National Nutrient Database, now FoodData Central):
The file: usda_nutrients.csv
Note: If you use this dataset, you’ll probably want to narrow the scope of your PCA (e.g. by limiting the food types and/or nutrients explored)
