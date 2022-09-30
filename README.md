# Ransomware-Actors-Analysis

## Overview
Ransomware has become a significant threat to companies, large and small, all around the world. Ransomware in 2021 almost doubled from the previous year and 2022 shows no sign of slowing down. In this project, we analyse the ransomware landscape in 2022 by finding first-hand evidence of the various attacks that occurred by looking through the ransomware shaming websites on the dark web. We base our study by choosing 4 ransomware groups.

### Ransomware Groups
The 4 ransomware groups and their website onion urls:

1. Lockbit3.0: http://lockbitapt6vx57t3eeqjofwgcglmutr3a35nygvokja5uuccip4ykyd.onion.ly/
2. Snatch: http://hl66646wtlp2naoqnhattngigjp5palgqmbwixepcjyq5i534acgqyad.onion.ly/
3. Quantum: http://quantum445bh3gzuyilxdzs5xdepf3b7lkcupswvkryf3n7hgzpxebid.onion.ly/
4. Hive: http://hiveleakdbtnp76ulyhi52eag6c6tyc3xw7ez7iqy6wc34gd2nekazyd.onion.ly/

![Landing Page of Ransomware Groups](ransomware_groups.png)

## Data Collection Scripts
We downloaded the raw HTML files of the 4 sites found in the `html_files_raw` folder.

We wrote Python scripts found in the `scripts` folder to scrape data from those HTML. We have an individual script for every Ransomware group. 

The raw data collected can be found in the `csv_data_raw` folder. The cleaned data can be found in the `csv_data_cleaned`. We have also compiled all the cleaned csv files into a single file called `ransomware_combined_cleaned_data` also found in the `csv_data_cleaned` folder.

Our Tableu Charts are also saved and can be found in the `Tableu Charts.twb` file.

## Running the scripts
If you would like to run the scripts, ensure you have Anaconda installed in your machine. Also ensure that you have the following libraries:
```
BeautifulSoup
codecs
Selenium
```
Then run the appropriate Jupyter Notebook script file in Jupyter Notebook.
