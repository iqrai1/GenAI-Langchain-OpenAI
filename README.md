# Getting Started with LangChain + OpenAI

This repository demonstrates how to build and deploy a simple Generative AI application using **LangChain**, **OpenAI**, **LangSmith**, and **LangServe**.

It includes two notebooks:

- `1.1.1-GettingStarted.ipynb`: Introductory setup and walkthrough of basic LangChain components
- `1.1.2-Simpleapp.ipynb`: A basic Generative AI app using prompt templates and an LLM

---

## What You'll Learn

- How to use **LangChain** to create prompt templates, call models, and parse outputs
- How to configure your environment for **OpenAI** and **LangChain**
- How to trace your application using **LangSmith**
- How to deploy the app using **LangServe**

---

## 🛠Tech Stack

- **LangChain** – LLM app orchestration
- **OpenAI API** – Access to models like `gpt-4o`
- **LangSmith** – Debugging and tracing LLM chains
- **Python** + **Jupyter Notebooks** – Development environment

---

## ⚙️ Setup Instructions

1. Clone this repo:

    ```bash
    git clone https://github.com/yourusername/langchain-getting-started.git
    cd langchain-getting-started
    ```

2. Install dependencies:

    ```bash
    pip install langchain langchain-openai langsmith python-dotenv
    ```

3. Create a `.env` file with your API keys:

    ```env
    OPENAI_API_KEY=your_openai_key
    LANGCHAIN_API_KEY=your_langchain_key
    LANGCHAIN_PROJECT=your_project_name
    ```

4. Run the notebooks:

    ```bash
    jupyter notebook 1.1.1-GettingStarted.ipynb
    jupyter notebook 1.1.2-Simpleapp.ipynb
    ```

---

## Notebook Summaries

### `1.1.1-GettingStarted.ipynb`

- Set up LangChain, OpenAI, and environment variables
- Build a simple chain using prompt templates
- Use LangSmith for tracing and debugging

### `1.1.2-Simpleapp.ipynb`

- Demonstrates a complete Generative AI app
- Uses `ChatOpenAI` to build a Q&A experience
- Can be extended to include retrievers and RAG pipelines

---

## Who Should Use This

- Developers learning LangChain for the first time
- Students or job-seekers building AI portfolios
- Recruiters assessing foundational understanding of GenAI pipelines

---
