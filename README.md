# 🔍 AutoEDA: LLM-Powered Automated Exploratory Data Analysis

An intelligent and interactive tool for automated exploratory data analysis powered by Large Language Models (LLMs). This project combines the power of LLMs with traditional data analysis tools to provide an intuitive interface for data exploration and visualization.

## 🌟 Features

- **📤 Interactive Data Upload**: Easy CSV file upload with automatic data cleaning
- **🧹 Automated Data Cleaning**:
  - Automatic datetime parsing
  - Missing value handling
  - Duplicate removal
- **📊 Smart Visualization**:
  - Natural language queries for plot generation
  - Multiple chart types support:
    - Scatter plots
    - Bar charts
    - Box plots
    - Histograms
    - Heat maps
    - Line plots
    - Pie charts
- **💬 Natural Language Querying**: Ask questions about your data in plain English
- **🤖 Machine Learning Integration**:
  - Automated model training
  - Support for classification and regression
  - Feature importance analysis
  - Model export functionality

## 🚀 Getting Started

### Prerequisites

- Python 3.x
- Jupyter Notebook
- Required Python packages:
  ```
  pandas
  matplotlib
  seaborn
  ipywidgets
  python-dotenv
  groq
  scikit-learn
  ```

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Akshit-Soni/AutoEDA.git
   cd AutoEDA-main
   ```

2. Create and activate a virtual environment:
   ```bash
   python -m venv .venv
   source .venv/bin/activate  # On Windows use: .venv\Scripts\activate
   ```

3. Install required packages:
   ```bash
   pip install pandas matplotlib seaborn ipywidgets python-dotenv groq scikit-learn
   jupyter nbextension enable --py widgetsnbextension --sys-prefix
   ```

4. Set up environment variables:
   ```bash
   # Create .env file with your Groq API key
   echo "GROQ_API_KEY=your_api_key_here" > .env
   ```

5. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

## 📖 Usage

1. **Upload Data**:
   - Click the upload button and select your CSV file
   - The tool automatically cleans and prepares your data

2. **Explore Data**:
   - Use the query input to ask questions about your data
   - Toggle between cleaned and raw datasets
   - Generate visualizations using natural language

3. **Create Visualizations**:
   - Ask for specific plots in natural language
   - Customize plots with different parameters
   - Save generated plots automatically

4. **Train Models**:
   - Select model type (classification/regression)
   - Describe your modeling goal in natural language
   - Export trained models for later use

## 🎨 Example Queries

```
"Show me the distribution of ages in the dataset"
"Create a scatter plot comparing price and square footage"
"What is the average salary by department?"
"Train a model to predict customer churn based on usage metrics"
```

## 🔧 Project Structure

```
AutoEDA/
├── AutoEDA.ipynb          # Main notebook with interactive interface
├── README.md             # Project documentation
├── titanic.csv          # Sample dataset
├── .env                 # Environment variables (containing GROQ_API_KEY)
└── .venv/              # Python virtual environment
```

## 🛠️ Customization

The tool can be customized by:
- Modifying the cleaning pipeline
- Adding new visualization types
- Extending machine learning capabilities
- Customizing the LLM prompts

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 🙏 Acknowledgments

- Groq for providing the LLM API
- The open-source community for various Python data science tools

## 📧 Contact

For questions and feedback, please reach out to soniakshit15502@gmail.com

---
**Note**: The project includes a sample dataset (titanic.csv) for testing and demonstration purposes.
