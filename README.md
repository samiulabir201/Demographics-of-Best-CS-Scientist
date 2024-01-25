# Demographics-of-Best-CS-Scientist

## Problem Statement
The goal of this project is to gather information on the best 1000 computer science researchers from [this website](https://research.com/scientists-rankings/computer-science). </br>
Later we used the scraper data to understand the following demographics and correlations using Tableau Dashboard:

1. A bar chart of countries with average publications.
2. European countries with the number of scientists on a map (excluding Russia)
3. Which Middle Eastern universities are good at research? (using citations to find that)
4. Which column is directly correlated with the World Rank column? We want to understand how the ranking was done.

You can visit the public dashboard [here](https://public.tableau.com/app/profile/samiul.islam6711/viz/DemographicsofBestCSScientist/Dashboard1)

## Findings and observations from the [Dashboard](https://public.tableau.com/app/profile/samiul.islam6711/viz/DemographicsofBestCSScientist/Dashboard1):

1. Brazilian scientists have the highest average publications.
2. Researchers from King Abdullah University of Science and Technology (KAUST), Saudi Arabia have the highest number of average citations.
3. Among European countries, the United Kingdom (UK) has the highest number of scientists among the top 1000.
4. The ranking was done most probably using H-Index.


## Build From Sources and run the Selenium scraper 


1. Clone the repo

```bash
git clone https://github.com/samiulabir201/Demographics-of-Best-CS-Scientist
```

2. Initialize and activate the virtual environment

```bash
virtualenv --no-site-packages venv
.\venv\Scripts\activate
```

3. Install dependencies

```bash
pip install -r requirement.txt
```

4. Download chrome driver from https://chromedriver.chromium.org/downloads

5. Run the scrapper

   ```bash
   python selenium_scraper\scraper.py --chromedriver_path <path_to_chromedriver>
   ```
6. You will get a file named `best_cs_scientist_details.csv` containing all the required fields. Alternatively, check the scrapped data here: https://github.com/samiulabir201/Demographics-of-Best-CS-Scientist/blob/main/selenium_scraper/best_cs_scientist_details.csv

## Analytics   
Tableau Public view: https://public.tableau.com/app/profile/samiul.islam6711/viz/DemographicsofBestCSScientist/Dashboard1
