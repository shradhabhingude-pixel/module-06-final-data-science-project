# Module 06 — Final Data Science Project
## Palmer Penguins: Exploratory Analysis and Species Classification

This portfolio-ready beginner project analyzes a public penguin measurement dataset and trains a machine learning classifier to predict species from bill and body measurements.

### Research question
Can four physical measurements (bill length, bill depth, flipper length, body mass) help classify penguin species in this dataset?

### Workflow
1. Load a public CSV and inspect data quality.
2. Remove duplicate records and rows without a target label.
3. Explore species counts and measurement distributions with visualizations.
4. Split the data into stratified training and test sets.
5. Train a most-frequent baseline and a Logistic Regression pipeline.
6. Evaluate with accuracy, macro F1, a classification report, and a confusion matrix.
7. Summarize findings and project limitations.

### Dataset and attribution
The project uses the simplified Palmer Penguins dataset from the `allisonhorst/palmerpenguins` project. It contains 344 observations across Adelie, Chinstrap, and Gentoo penguins from islands in the Palmer Archipelago, Antarctica. Data were collected and made available by Dr. Kristen Gorman and the Palmer Station Antarctica LTER program. The dataset is available under CC0.

- Project: https://github.com/allisonhorst/palmerpenguins
- CSV source: https://raw.githubusercontent.com/allisonhorst/palmerpenguins/main/inst/extdata/penguins.csv
- Citation: Horst AM, Hill AP, Gorman KB (2020), *palmerpenguins: Palmer Archipelago (Antarctica) penguin data*, https://doi.org/10.5281/zenodo.3960218.

### Files
- `Module_06_Final_Data_Science_Project.ipynb` — complete Colab/Jupyter notebook.
- `README.md` — portfolio overview, reproduction steps, and data citation.
- `LINKEDIN_POST.md` — post draft to personalize after you publish the repository.
- `requirements.txt` — Python packages for running locally.
- `DATA_SOURCE.txt` — direct dataset links and license.

### Run in Google Colab
1. Go to https://colab.research.google.com/.
2. Select **File → Upload notebook** and upload the `.ipynb` file.
3. Run **Runtime → Run all**. The notebook needs internet access to load the public CSV.
4. Save a copy to Google Drive and use **Share → Copy link** to submit the Colab deliverable.

### Publish on GitHub
Create a new public repository, then upload the extracted project files (not only the ZIP). Include the notebook and README. Add the repository link to your course submission and LinkedIn post.

### Limitations
The data are observational and geographically limited. Model performance is measured on one held-out split, so it may vary on new samples. The project demonstrates a learning workflow and is not intended for research or operational decisions.
