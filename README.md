
# UTM Professor Data Analysis (Demo Only)

This project demonstrates how to analyze and visualize professor rating data using **Bayesian averaging**, based on previously available data from [RateMyProfessors](https://www.ratemyprofessors.com/).  
Only analysis logic and example plots are retained for educational purposes.

---

## Project Structure (Simplified)

- `system_class.py`:  
  Defines core classes including `University`, `Department`, `ProfData`, and `CourseUnderProf`.

- `analysis.py`:  
  Contains statistical functions and Bayesian scoring logic, as well as plotting utilities.

- `main.py`:  
  Main script to run analysis and generate plots (no longer includes any scraping or data fetching).

---

## Current Status

- Code for analysis, Bayesian ranking, and visualization
- Sample output plots generated from previously available data (shown below)

---

## Sample Visualizations

These plots are **examples** only, based on previously generated data that has now been removed:

![Difficulty Ranking Chart](https://raw.githubusercontent.com/Jackymn25/utm-professor-analysis-rmp/main/plots/pic_2.png)
![Difficulty Ranking Chart](https://raw.githubusercontent.com/Jackymn25/utm-professor-analysis-rmp/main/plots/pic_1.png)
![Difficulty Ranking Chart](https://raw.githubusercontent.com/Jackymn25/utm-professor-analysis-rmp/main/plots/myplot1.png)

---

## Usage (With Your Own Data)

If you have your own JSON-formatted professor data (not provided here), you can place it in the `data/` directory:

- The expected filename is `all_prof_data.json`
- Run the main script:

First set up environment

```bash
pip install -r requirements.txt

```bash
python main.py

