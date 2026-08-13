# 🤖 LangChain + Gemini — AI DataFrame Agent

<p align="center">
  <b>Building AI Data Analysis Agents with Python, LangChain, Gemini & Pandas</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python" alt="Python">
  <img src="https://img.shields.io/badge/LangChain-AI%20Agents-green?style=for-the-badge" alt="LangChain">
  <img src="https://img.shields.io/badge/Google%20Gemini-Generative%20AI-purple?style=for-the-badge" alt="Google Gemini">
  <img src="https://img.shields.io/badge/Pandas-Data%20Analysis-black?style=for-the-badge&logo=pandas" alt="Pandas">
  <img src="https://img.shields.io/badge/Jupyter-Notebook-orange?style=for-the-badge&logo=jupyter" alt="Jupyter">
  <img src="https://img.shields.io/badge/GitHub-Version%20Control-black?style=for-the-badge&logo=github" alt="GitHub">
</p>

---

## 📌 About the Project

This project demonstrates the fundamentals of **AI Agents, Generative AI, and LLM-powered Data Analysis** using **LangChain, Google Gemini, Python, and Pandas**.

The project explores how an AI agent can interact with **Pandas DataFrames** and answer questions about structured datasets using natural language.

Instead of manually writing Pandas code for every analysis task, users can ask questions in natural language and the AI agent can determine the required data analysis operations.

The notebooks included in this repository demonstrate practical implementations of **LangChain Pandas DataFrame Agents** and **Google Gemini-powered agents**.

---

## 🚀 Project Features

* 🤖 AI Agent development using **LangChain**
* 🧠 Google Gemini LLM integration
* 🐼 Pandas DataFrame analysis
* 📊 Dataset exploration using natural language
* 🔍 Missing-value analysis
* 📈 DataFrame comparison
* 💻 AI-powered Python data analysis
* 📓 Jupyter Notebook implementations
* 🔐 API key management using environment variables
* ⚡ Generative AI-powered data analysis
* 🛠️ LLM tool-based agent workflows

---

## 📂 Project Structure

```text
langchain-gemini-dataframe-agent/
│
├── 📓 Langchain_agents.ipynb
├── 📓 langchain_agents_using_gemini.ipynb
├── 📊 titanic dataset.csv
├── 🔐 .gitignore
└── 📄 README.md
```

### 📓 `Langchain_agents.ipynb`

This notebook demonstrates the use of a **LangChain Pandas DataFrame Agent** for interacting with a dataset.

The agent can understand natural-language questions and perform data analysis operations using the Pandas DataFrame.

Example questions include:

```text
How many rows are there?

How many people have more than 3 siblings?

Which columns contain missing values?
```

Key concepts covered:

* LangChain Agents
* Pandas DataFrame Agent
* LLM integration
* Natural-language data analysis
* Python-based data analysis
* Agent reasoning

---

### 🤖 `langchain_agents_using_gemini.ipynb`

This notebook demonstrates using **Google Gemini** with LangChain to create an AI-powered DataFrame analysis agent.

The agent can answer questions about the dataset and perform operations on DataFrames.

Example tasks include:

```text
How many rows are there?

How many people have more than 3 siblings?

Which attribute has missing values?

How many rows in the Age column are different?

Are the number of columns the same in the DataFrames?
```

The notebook also demonstrates creating modified DataFrames and comparing datasets using the AI agent.

Key concepts covered:

* Google Gemini
* LangChain
* Pandas
* DataFrame Agents
* Generative AI
* Natural-language querying
* DataFrame comparison

---

## 🧠 What is an AI DataFrame Agent?

An **AI DataFrame Agent** allows an LLM to interact with structured data such as Pandas DataFrames.

The workflow can be represented as:

```text
User Question
      ↓
AI Agent
      ↓
LLM Reasoning
      ↓
DataFrame Analysis
      ↓
Python / Pandas Operations
      ↓
Result
      ↓
Natural-Language Answer
```

For example, instead of writing:

```python
df.shape[0]
```

the user can simply ask:

```text
How many rows are there?
```

The agent determines how to analyze the DataFrame and returns the result.

---

## 🔗 What is LangChain?

**LangChain** is a framework for building applications powered by Large Language Models.

It provides components for:

* LLM integration
* Agents
* Tools
* Prompt templates
* Data interaction
* AI workflows
* Generative AI applications

In this project, LangChain is used to connect the LLM with Pandas DataFrames and create an intelligent data analysis agent.

---

## 🤖 What is Google Gemini?

**Google Gemini** is a family of generative AI models that can understand and generate natural language.

In this project, Gemini is used as the LLM that powers the LangChain DataFrame Agent.

The combination can be represented as:

```text
Google Gemini
      ↓
LangChain
      ↓
DataFrame Agent
      ↓
Pandas
      ↓
Dataset Analysis
```

---

## 🐼 Pandas Data Analysis

The project uses **Pandas** for working with structured datasets.

The DataFrame can be used to:

* Inspect rows and columns
* Analyze missing values
* Perform calculations
* Create new columns
* Modify data
* Compare DataFrames
* Answer data-related questions

---

## 📊 Dataset

The project uses a **Titanic dataset** for demonstrating AI-powered DataFrame analysis.

The dataset contains information about Titanic passengers and includes attributes that can be analyzed using Pandas and the AI agent.

Examples of analysis include:

* Number of rows
* Passenger information
* Sibling/spouse information
* Missing values
* Age-related analysis
* Column comparison

---

## 🛠️ Technologies Used

| Technology          | Purpose                            |
| ------------------- | ---------------------------------- |
| 🐍 Python           | Programming language               |
| 🔗 LangChain        | AI application and agent framework |
| 🤖 Google Gemini    | Large Language Model               |
| 🐼 Pandas           | Data manipulation and analysis     |
| 📊 Titanic Dataset  | Data analysis                      |
| 📓 Jupyter Notebook | Development & experimentation      |
| 🔐 dotenv           | Environment variable management    |
| 🐙 Git & GitHub     | Version control                    |

---

## 🔐 API Key Security

The Gemini API key should **not** be stored directly in the notebook or uploaded to GitHub.

Create a `.env` file in the project directory:

```env
GEMINI_API_KEY=your_gemini_api_key
```

Load the API key using Python:

```python
from dotenv import load_dotenv
import os

load_dotenv()

api_key = os.getenv("GEMINI_API_KEY")
```

### ⚠️ Important

Never upload your `.env` file to GitHub.

Add the following to `.gitignore`:

```text
.env
.ipynb_checkpoints/
__pycache__/
```

If an API key has already been exposed publicly, revoke it and create a new one.

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/Swati2064/langchain-gemini-dataframe-agent.git
```

### 2. Navigate to the project

```bash
cd langchain-gemini-dataframe-agent
```

### 3. Create a virtual environment

```bash
python -m venv venv
```

### 4. Activate the environment

**Windows:**

```bash
venv\Scripts\activate
```

### 5. Install dependencies

```bash
pip install langchain
pip install langchain-experimental
pip install langchain-google-genai
pip install pandas
pip install python-dotenv
pip install jupyter
```

---

## ▶️ Running the Project

Start Jupyter Notebook:

```bash
jupyter notebook
```

Then open:

```text
Langchain_agents.ipynb
```

or:

```text
langchain_agents_using_gemini.ipynb
```

Run the notebook cells step by step.

---

## 💡 Example Questions

After creating the DataFrame Agent, you can ask questions such as:

```text
How many rows are there?
```

```text
How many people have more than 3 siblings?
```

```text
Which attribute has missing values?
```

```text
How many rows in the age column are different?
```

```text
Are the number of columns the same in the DataFrames?
```

The agent interprets the question and performs the required DataFrame analysis.

---

## 🧹 Data Preprocessing

The project also demonstrates DataFrame modification and preprocessing.

For example, missing values in the `Age` column can be handled using the mean value:

```python
df1 = df.copy()

df1["age"] = df1["Age"].fillna(
    df1["Age"].mean()
)
```

A new calculated column can also be created:

```python
df2 = df1.copy()

df2["Age_Multiplied"] = df1["age"] * 2
```

These DataFrames can then be analyzed and compared using the AI agent.

---

## 📚 Concepts Learned

This project covers important concepts in modern AI and Data Science:

* Large Language Models
* Generative AI
* AI Agents
* LangChain
* Google Gemini
* Pandas
* DataFrame Agents
* Natural-Language Data Analysis
* Tool Calling
* Agent Reasoning
* Data Preprocessing
* Missing-Value Handling
* DataFrame Comparison
* Environment Variables
* API Integration

---

## 🎯 Learning Objectives

The main objectives of this project are to understand how to:

1. Build an AI agent using LangChain.
2. Connect Google Gemini with LangChain.
3. Allow an LLM to interact with Pandas DataFrames.
4. Ask natural-language questions about datasets.
5. Perform data analysis using an AI agent.
6. Handle missing values in datasets.
7. Compare multiple DataFrames.
8. Secure API keys using environment variables.
9. Understand the fundamentals of Agentic AI and Generative AI.

---

## 🔮 Future Improvements

Possible future enhancements include:

* 🌐 Streamlit web interface
* 📤 CSV file upload
* 📊 Automatic data visualization
* 📈 AI-generated charts
* 💬 Conversational DataFrame analysis
* 📁 Excel file support
* 🗂️ Multiple dataset support
* 🧠 RAG-based data analysis
* 🔗 Vector database integration
* 🛠️ Custom LangChain tools
* 📊 Agent monitoring and evaluation
* 🚀 Deployment using Streamlit or FastAPI

---

## 👩‍💻 Author

**Swati Jadhav**

🎓 B.Tech — Artificial Intelligence & Data Science

### Skills Demonstrated

`Python` • `Pandas` • `LangChain` • `Google Gemini` • `Generative AI` • `AI Agents` • `Data Analysis`

---

## ⭐ Support

If you find this project useful for learning **LangChain, Generative AI, Agentic AI, and AI-powered Data Analysis**, consider giving the repository a ⭐ on GitHub.

---

<p align="center">
  <b>🤖 Exploring Agentic AI • Generative AI • LangChain • Gemini • AI Data Analysis</b>
</p>
