# LLMs Playpen

Experimenting with LLM-powered application development. Currently one project:

## YouTube Video Summarizer

Builds a summarization pipeline using LangChain and the Together AI API
(Llama 3.3 70B). Loads a YouTube video transcript via LangChain's
`YoutubeLoader`, constructs a prompt template, and runs it through an
`LLMChain` to produce a structured Markdown summary.

Built following a FreeCodeCamp walkthrough as a first hands-on exercise
with LangChain pipelines and hosted LLM APIs.

**Stack:** Python - LangChain - Together AI - Llama 3.3 70B - python-dotenv

**Notebook:** `first_llm.ipynb`

> Note: requires a Together AI API key stored in a `.env` file as `API_KEY`.
