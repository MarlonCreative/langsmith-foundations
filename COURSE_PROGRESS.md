# LangSmith Essentials course progress

This is my working copy of the [LangChain Academy LangSmith Essentials course](https://academy.langchain.com/courses/take/quickstart-langsmith-essentials/multimedia/77918169-getting-set-up). The original course code is maintained at [langchain-ai/lca-langsmith-essentials](https://github.com/langchain-ai/lca-langsmith-essentials).

## November 10, 2026 — Getting set up

- Cloned the course repository.
- Selected the `langgraph-agent` project used in the lessons.
- Installed its locked dependencies with `uv sync` using Python 3.13.3.
- Ran `check_setup.py`: Python, the virtual environment, `uv`, and the required packages pass.
- Remaining setup: add my LangSmith and OpenAI API keys to the local, Git-ignored `.env` file; add the OpenAI key as a LangSmith workspace provider secret; rerun the setup checker.

The `.env` file is intentionally excluded from Git. No API keys belong in this repository.
