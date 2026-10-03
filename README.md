# Deep Research Agent

An autonomous AI agent designed to perform comprehensive web research and generate detailed reports based on user queries.

## 🚀 Overview

The Deep Research Agent leverages Large Language Models (LLMs) and web search capabilities to transform a simple query into a structured research plan, execute searches, synthesize information, and produce a professional markdown report.

## 🎯 Business Goal

The primary goal of this project is to automate the time-consuming process of manual information gathering. By automating the "search-read-summarize" loop, the agent provides:
- **Efficiency**: Rapidly gathers data from multiple sources.
- **Depth**: Creates a structured research plan to ensure all angles of a query are covered.
- **Actionability**: Delivers a final report with a summary and suggested follow-up questions for further exploration.

## 🛠 Technologies Used

- **Python**: Core programming language.
- **OpenAI API**: For advanced reasoning, planning, and report generation.
- **Pydantic**: For strict data validation and structured responses (as seen in `response_model.py`).
- **Web Search API**: (e.g., Tavily/Google) To fetch real-time information from the web.

## 📋 Features

- **Autonomous Planning**: Generates a `WebSearchPlan` with reasoned search queries.
- **Structured Output**: Produces reports containing a short summary, a detailed markdown body, and follow-up questions.
- **Email Integration**: Capability to send report confirmations via email.

## ⚙️ Setup

1. **Clone the repository**:
   ```bash
   git clone <repository-url>
   cd deep_research_new
   ```

2. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Configure Environment**:
   Copy the example environment file and add your API keys:
   ```bash
   cp .env.example .env
   ```

4. **Run the Agent**:
   ```bash
   python main.py
   ```

## 📄 License

This project is licensed under the MIT License.

