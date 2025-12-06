ai-career-success-predictor/
│
├── data/
│   └── campus_placement.csv               # Your Kaggle dataset (optional to include if size allowed)
│
├── notebooks/
│   ├── 01_data_prep_and_eda.ipynb         # Databricks export or .py
│   ├── 02_model_training_mlflow.ipynb
│   └── 03_evaluation_and_interpretability.ipynb
│
├── streamlit_app/
│   ├── app.py                             # Main Streamlit app
│   ├── utils.py                           # Helper functions
│   └── model/
│       ├── best_model.pkl                 # Saved final model
│       ├── encoder.pkl                    # Saved preprocessing pipeline
│       └── explainer.pkl                  # SHAP explainer
│
├── mlflow_runs/                            # OPTIONAL: export MLflow artifacts
│
├── docs/
│   ├── slides.pdf                         # Final slide deck
│   ├── presentation_script.md             # 15-minute script
│   └── architecture_diagram.png           # OPTIONAL
│
├── requirements.txt                        # Required packages for Streamlit deployment
├── README.md                               # Main project documentation
└── LICENSE                                 # OPTIONAL
