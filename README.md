# Multi-Agent System 🔬

An advanced AI-powered research system leveraging multi-agent architecture for intelligent web research, content analysis, and report generation.

## 🚀 Live Demo

**[Try the app on Streamlit Cloud](https://multi-agent-syste-f4rwl6ddcktf6auiizsxdb.streamlit.app/)**

## 📋 Features

- **Search Agent**: Intelligent web search using Tavily API
- **Reader Agent**: Advanced web scraping and content extraction
- **Writer Chain**: AI-powered content generation and synthesis
- **Critic Chain**: Automated quality assessment and refinement
- **Multi-Agent Orchestration**: Seamless coordination between specialized agents
- **Beautiful UI**: Modern, responsive interface with custom styling

## 🛠️ Tech Stack

- **LLM**: Mistral AI, OpenAI
- **Framework**: LangChain, Streamlit
- **Search**: Tavily API
- **Web Scraping**: BeautifulSoup4, Requests
- **Async Support**: aiohttp
- **Data Processing**: Pandas

## 📦 Installation

1. Clone the repository:
```bash
git clone https://github.com/Aheed-Siddiqui-Official/Multi-Agent-System.git
cd Multi-Agent-System
```

2. Create a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Set up environment variables:
Create a `.env` file with your API keys:
```
OPENAI_API_KEY=your_openai_key
TAVILY_API_KEY=your_tavily_key
MISTRAL_API_KEY=your_mistral_key
```

## 🚀 Running Locally

```bash
streamlit run app.py
```

The app will be available at `http://localhost:8501`

## 📁 Project Structure

```
.
├── app.py              # Main Streamlit application
├── agents.py           # Multi-agent definitions
├── tools.py            # Tool implementations (search, scraping)
├── pipeline.py         # Research pipeline orchestration
├── requirements.txt    # Project dependencies
└── README.md          # This file
```

## 🔧 Agent Components

### Search Agent
Performs intelligent web searches to find relevant information.

### Reader Agent
Extracts and processes content from web pages.

### Writer Chain
Synthesizes information into coherent, well-structured reports.

### Critic Chain
Evaluates and improves generated content for quality assurance.

## 🌐 Deployment

The app is deployed on **Streamlit Cloud** at:
```
https://multi-agent-syste-f4rwl6ddcktf6auiizsxdb.streamlit.app/
```

### Deployment Steps:
1. Push code to GitHub
2. Connect repo to Streamlit Cloud
3. Add API secrets in Streamlit Cloud dashboard:
   - `OPENAI_API_KEY`
   - `TAVILY_API_KEY`
   - `MISTRAL_API_KEY`

## 📝 License

This project is open source and available under the MIT License.

## 👤 Author

**Muhammad Aheed Siddiqui**
- GitHub: [@Aheed-Siddiqui-Official](https://github.com/Aheed-Siddiqui-Official)

## 🤝 Contributing

Contributions are welcome! Feel free to open issues and submit pull requests.

---

Built with ❤️ using LangChain, Streamlit, and AI
