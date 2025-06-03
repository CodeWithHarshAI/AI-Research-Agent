# AI-Research-Agent

# 📰 Multi-Agent HackerNews Research Assistant

This Streamlit app enables powerful AI-driven research on top HackerNews stories and users using a team of LLM-based assistants. Built with GPT-4o and the Agno agent framework, it's your go-to tool for content discovery, blogging, and trend analysis.

## 🚀 Features

- 📖 Research **top HackerNews stories**
- 👤 Analyze **influential users** and their activity
- 🧠 Use a **multi-agent system** with story/user specialists and a coordination assistant
- ✍️ Generate **blog posts**, **social media content**, or **summary reports**

## 🛠️ Quickstart

### 1. Clone the Repository

```bash
git clone https://github.com/CodeWithHarshAI/AI-Research-Agent.git
cd AI-Research-Agent
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

Or install manually:

```bash
pip install streamlit agno openai
```

### 3. Setup OpenAI API Key

You can:
- Set it as an environment variable:
  ```bash
  export OPENAI_API_KEY=your-key-here
  ```
- Or store it in a `.env` file in the project root:
  ```
  OPENAI_API_KEY=your-key-here
  ```

### 4. Run the App

```bash
streamlit run research_agent.py
```

## ⚙️ How It Works

- The app initializes three agents:
  - `story_researcher`: Extracts insights from HackerNews stories.
  - `user_researcher`: Digs into HackerNews user behavior.
  - `hn_assistant`: Delegates tasks and synthesizes responses.
- You enter a research question or topic.
- Agents coordinate to pull real-time data and generate insightful responses via GPT-4o.
- The result can be saved or shared as a report or blog post.

## 📄 File Structure

```
.
├── research_agent.py             # Main streamlit interface
├── research_agent_llama3.py      # Optional variant with LLaMA3 support
├── requirements.txt              # Project dependencies
└── README.md                     # You're here!
```

## 📚 License

MIT License

---

Made with 🤖 by **Harsh**  
[GitHub: CodeWithHarshAI](https://github.com/CodeWithHarshAI)
