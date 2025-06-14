# FlowAgent: Autonomous AI Task Planner with Tools & Memory

**FlowAgent** is an intelligent multi-step AI agent built with Python. It can:
- Break down user requests into logical action steps
- Use external tools (e.g., calculator, web search)
- Store long-term memory in a vector database
- Pick up where it left off, even across sessions

### 🚀 Example Task
> "Plan a birthday party for a 7-year-old with a superhero theme under $300."

The agent will:
1. Break the task into subtasks (venue, food, activities)
2. Use tools (e.g., search APIs, budget calculator)
3. Save progress and results for later use

---

## 🧱 Tech Stack
- Python 3.10+
- OpenAI (or local model via LM Studio)
- LangChain (agent framework)
- ChromaDB or FAISS (for memory)

---

## 📂 Repo Structure
See `tools/`, `memory/`, and `agent/` folders for core logic.
Run `main.py` to get started.
