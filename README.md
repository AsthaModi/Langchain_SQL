## SQL Database Agent with OpenAI and LangChain
This project demonstrates how to create an SQL database agent using the LangChain framework, OpenAI, and FAISS (Facebook AI Similarity Search). The agent interacts with an SQLite database (Chinook in this case) to generate SQL queries based on natural language input and returns the relevant data from the database.

### Requirements
To run this project, you'll need the following:

* Python 3.8+
* LangChain
* OpenAI API
* FAISS
* SQLite (Chinook sample database)

### Installation
#### Clone the repository:
- git clone https://github.com/AsthaModi/Langchain_SQL.git
- cd sql-agent-langchain
#### Install dependencies: 
- pip install langchain openai faiss-cpu sqlite3
#### Set up environment variables: 
- Set your OpenAI API key as an environment variable. Replace YOUR API KEY HERE in the script with your actual API key.


### Project Overview
#### Project Overview
- A connection to an SQLite database (Chinook).
- A LangChain SQL agent that generates and executes SQL queries based on user inputs.
- Semantic similarity-based few-shot prompt selection using FAISS and OpenAI embeddings.
- A dynamic prompt template that generates SQL queries in response to natural language queries.
##### Database
- The Chinook sample database is an SQLite database containing tables such as Artist, Album, Track, and Customer, simulating a music store.
