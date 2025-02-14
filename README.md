# AI Assistant Streamlit Application

This repository contains a Streamlit application that integrates phi-based AI agents to provide users with financial data analysis and web search capabilities.

## Features

- **Web Search Agent**: Utilizes DuckDuckGo to fetch and summarize web information.
- **Finance AI Agent**: Leverages YFinanceTools to provide stock prices, analyst recommendations, stock fundamentals, and company news.
- **Multi-Agent Collaboration**: Combines the strengths of both agents to deliver comprehensive responses to user queries.

## Installation

1. **Clone the Repository**:

   ```shell
   git clone https://github.com/essiebx/Financial-Agent.git
   
 ## getting started
 
2. **Create a Virtual Environment**
 ```shell
   py -m venv myvenv

  ``` shell
   myvenv/Scripts/activate

3. **Install Dependencies:**
``` shell
pip install -r requirements.txt


4. **Set Up Environment Variables(this are your APIss)**

   **Create a .env file in the root directory. **

  **Add your API keys: **

 ## Environment Variables Setup

Create a `.env` file in the root directory and add the following keys:

```shell
OPENAI_API_KEY='replace this with your OpenAI API key'
# You will need a subscription for this API key.
# The OpenAI API key is associated with the Phi-Data framework, which still relies on it.

GROQ_API_KEY='replace this with your Groq API key'

PHIDATA_API_KEY='replace this with your PhiData API key'

## API Key Setup

- **Groq API Key** → [Generate your key here](https://console.groq.com/keys)
- **OpenAI API Key** → [Get your API key](https://platform.openai.com/docs/api-reference/introduction)
- **PhiData API Key** → [Manage your API key](https://www.phidata.app/settings) **make sure you click the api just below the settings**


  ## Running the appliaction
1.  ```` shell
  streamlit run app.py
-**Open your browser and navigate to http://localhost:8501**
-**Enter your query in the input box and click "Submit" to receive a response from the AI assistant.**

