# 🧪 Smart Reaction Design Tool

A Streamlit application for predicting molecular properties (`LogP` and `LogS`) and generating novel molecules using **ChemBERTa** and **ChemGPT**.

## 🚀 Features

- **Property Prediction:** Predict `LogP` and `LogS` values from SMILES strings.
- **Molecule Generation:** Generate new molecules based on input SMILES.
- **Visualization:** View molecular structures and evaluation metrics.

## 🛠️ Installation

1. **Clone the Repository**
    ```bash
    git clone https://github.com/yourusername/ChemLLMathon_SmartReactionDesignTool.git
    cd ChemLLMathon_SmartReactionDesignTool
    ```

2. **Create and Activate Virtual Environment**
    ```bash
    python3 -m venv env
    source env/bin/activate  # On Windows: env\Scripts\activate
    ```

3. **Install Dependencies**
    ```bash
    pip install -r requirements.txt
    ```

## 💻 Usage

Run the Streamlit app:
```bash
streamlit run app.py
