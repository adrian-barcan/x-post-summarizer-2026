# X Post Summarizer 2026

This repository contains an AI-generated summary of a public figure's 2026 X posts. The analyzed handle is @llm_wizard.

## Project Description

This project summarizes the 2026 posts of a public figure on X using AI. It leverages a LangGraph agent combined with GitHub MCP tools for repository operations and the X API v2 for retrieving posts.

## How It Was Built

- The LangGraph agent orchestrates the workflow.
- GitHub MCP tools are used for creating and managing the repository, branches, files, and pull requests.
- The X API v2 is used to search and retrieve recent posts from the specified X handle.

## How to Replicate

1. **Set up your X API Bearer Token:**
   - Obtain your Bearer Token from the X developer portal.
   - Set it as an environment variable in your shell:
     ```bash
     export X_BEARER_TOKEN="your_bearer_token_here"
     ```

2. **Install Python dependencies:**
   - This project requires the `requests` library.
   - Install it using pip:
     ```bash
     pip install requests
     ```

3. **Run the search script:**
   - Use the provided `x_search.py` script to fetch recent posts from a specified X handle.
   - Example:
     ```bash
     python x_search.py llm_wizard
     ```

4. **Review the generated posts and summaries in the repository.**

## Files

- `summary.md`: Contains the AI-generated summary of the posts.
- `metadata.json`: Contains metadata about the analysis.
- `x_search.py`: Python script to search and retrieve posts from X.

---

Feel free to explore and adapt this project for your own analysis needs.