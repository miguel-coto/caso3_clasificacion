

# The directory structure of your new project looks like this.
________________________________________________________________________________________

- README.md: The top-level README for analysts using this project.
- data
   - external : Data from third party sources.
   - interim  : Intermediate data that has been transformed.
   - processed: The final, canonical data sets for modeling.
   - raw      : The original, immutable data dump.

- docs: Internal documentation in formats: HTML, LaTeX (for printable PDF versions), ePub,
        Texinfo, manual pages, plain text

- models: Trained and serialized models, model predictions, or model summaries

- notebooks: R-markdowns or Jupyter notebooks. Naming convention is a number (for ordering),
             the creator's initials, and a short `-` delimited description, e.g.
             `1.0-mcg-initial-data-exploration`.

- references: Data dictionaries, manuals, and all other explanatory materials.

- reports: Generated analysis as HTML, PDF, LaTeX, etc.

- requirements.txt: The requirements file for reproducing the analysis environment.

- src: Source code for use in this project.

  - data: Scripts to download or generate data
      + make_dataset.R

  - features: Scripts to turn raw data into features for modeling
      + build_features.R

  - models: Scripts to train models and then use trained models to make predictions
      + predict_model.R
      + train_model.R

  - visualization: Scripts to create exploratory and results oriented visualizations
      + visualize.R

  - utilities: Common functions and code that can be utilized for the rest of the sripts/notebooks.

- test: Scripts to generate the tests for the rest of the code.
		
