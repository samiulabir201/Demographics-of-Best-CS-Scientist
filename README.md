# Demographics-of-Best-CS-Scientist

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
6. You will get a file named `best_cs_scientist_details.csv` containing all the required fields.

Alternatively, check the scrapped data here: https://github.com/samiulabir201/Demographics-of-Best-CS-Scientist/blob/main/selenium_scraper/best_cs_scientist_details.csv

## Analytics   
Tableau Public view: https://public.tableau.com/app/profile/samiul.islam6711/viz/DemographicsofBestCSScientist/Dashboard1
