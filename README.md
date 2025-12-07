# Text-to-SQL LLM  
A production-ready pipeline that converts everyday questions into executable SQL and returns results from your database. Built with Llama, LangChain, and Streamlit to make data querying intuitive and fast.

# Overview
This project demonstrates a complete Text-to-SQL system: users submit a natural language prompt, the LLM produces a SQL statement, the query runs against your database, and the results are displayed in a simple web UI. It’s designed to reduce manual SQL writing and accelerate insight generation.

# Tech Stack
Llama: Translates natural language into SQL
LangChain: Connects the LLM to database tools and schema context
Streamlit: Interactive front-end for running queries and viewing results
SQL Database: Backend datastore for executing generated queries
Pipenv: Environment and dependency management

# Features
Natural language to SQL without writing queries by hand
Automated data retrieval directly from your tables
LLM-powered analytics and query generation
Streamlit UI for a smooth, browser-based experience
Multi-database support across common SQL engines
Installation
Prerequisite: Python 3.8+

Bash
pipenv install
pipenv install streamlit langchain_groq
pipenv shell

# Start the Streamlit app
streamlit run app.py
Sample Prompts
What is the average score for each class?
Which student has the highest marks?
Which student has the lowest marks?
Who is second-highest in Machine Learning?
List students with the second-highest marks by course.
Future Improvements
Add support for multiple LLM providers and models
Build visual dashboards for query outputs
Use fine-tuned models for more precise SQL generation
