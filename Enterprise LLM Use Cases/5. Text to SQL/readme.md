# Text-to-SQL with LLM (powered by watsonx.ai)

This use case demonstrates a solution for converting natural language text into SQL queries using Language Model (LLM) powered by watsonx.ai. The directory consists of Python scripts, Jupyter Notebooks, and an Excel file that work together to achieve this goal.

## Files and Descriptions

### Python Scripts

#### `db_connectors.py`

This script contains functions related to connecting to various databases. It includes connectors for different types of databases such as SQLite, MySQL, PostgreSQL, etc.

#### `prompt_formatters.py`

This script contains functions or classes related to formatting prompts for the text-to-SQL use case. It helps in preparing and transforming natural language queries for processing.

### Jupyter Notebooks

#### `sqlite.ipynb`

This notebook contains code, examples, and explanations related to working with SQLite databases. It demonstrates how to connect to SQLite databases, execute SQL queries, and retrieve results.

#### `t5-wikiSQL-hf.ipynb`

This notebook demonstrates the process of using the T5 model to convert natural language text into SQL queries within the context of the WikiSQL dataset. It includes code for preprocessing text, loading the model, generating SQL queries, and evaluating the results.

### Data File

#### `LCDataDictionary.xlsx`

This Excel file may contain metadata that includes a data dictionary or other related information.

## Usage

### 1. Set Up the Environment

Before running the code, ensure that you have the necessary dependencies installed. You may need to install specific Python packages or set up a virtual environment. Here's an example:

```bash
pip install pandas numpy sqlite plotly
```

### 2. Database Connection

Utilize the `db_connectors.py` script to establish connections to the required databases. Modify the connection parameters as needed for your specific database setup.

### 3. Preprocess and Format Prompts

Use the `prompt_formatters.py` script to preprocess and format the natural language queries that you wish to translate into SQL.

### 4. Run the SQLite Notebook

Open the `sqlite.ipynb` notebook and follow the instructions to work with SQLite databases. Execute the cells to connect to the database, run queries, and analyze the results.

### 5. Run the T5 WikiSQL Notebook

Open the `t5-wikiSQL-hf.ipynb` notebook and follow the instructions to load the T5 model and perform text-to-SQL translation. Execute the cells to preprocess text, generate SQL queries, and evaluate performance.

### 6. Utilize the Excel File

Refer to the `LCDataDictionary.xlsx` file for any additional data or metadata needed to support the project. Integrate the information as needed within the notebooks or scripts.

### 7. Analyze the Results

Review the outputs and visualizations generated by the notebooks to understand the performance and results of the text-to-SQL translation.
