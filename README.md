# airbnb_data_analysis_assignment

An end-to-end data engineering pipeline that ingests raw short-term rental data (`listings.csv`, `calendar.csv`, `reviews.csv`), cleans and normalizes schema anomalies  and  derives advanced operational metrics.

---

## 1. Project Directory Structure

```text
airbnb-data-analysis/
│
├── README.md                           # Setup instructions, reproducibility guide, and disclosures
├── requirements.txt                    # Python package dependencies
└── airbnb_analysis.ipynb               # main jupyter file with the source code
└── Analysis_Report.pdf                 # report with the answer to second section of the assignment
```

---

## 2. Reproducibility Instruction

Follow these step-by-step instructions to initialize the environment, configure inputs, and execute the analytical pipeline.
Clone or Extract the Repository: Ensure your directory layout matches the structure defined above.

Initialize a Virtual Environment: Isolate your project package configurations to prevent version conflicts.

```Bash
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate
```
Install Core Dependencies: Run the following command to download the necessary data manipulation and database engine libraries:

```Bash
pip install -r requirements.txt
```
## 3. Data Setup

Gather your raw source datasets: listings.csv, calendar.csv, and reviews.csv.
Place these three raw files directly into the root workspace folder (airbnb-data-analysis/).
The processing modules look for files in this location by default.


## 4. AI Usage Disclosure
In compliance with assignment guidelines, generative AI tools were integrated into the development workflow under the following parameters:
```text
* AI was used as a peer-review assistant to debug errors throughout the code.
* AI was used to map out the mathematical logic for the Cross-Table Fallback Framework. When I was found that the daily calendar file lacked explicit pricing columns, AI helped formulate the argument.
```

