# QueryMind

**QueryMind** is an Agentic AI-powered SQL MCP Server that allows AI agents and MCP-compatible applications to interact with databases using natural language.

## Features

- **Natural Language to SQL:** Convert user questions into SQL queries using an LLM.
- **SQL Validation:** Validate generated queries before execution.
- **Human-in-the-Loop:** Require human approval before executing write operations.
- **Self-Correction:** Automatically detect SQL errors and retry with corrected queries.
- **MCP Integration:** Expose database capabilities as reusable MCP tools.
- **Schema Intelligence:** Discover foreign-key relationships, find join paths, and generate JOIN conditions.

## Tech Stack

Python, MySQL, SQLAlchemy, LangChain, LangGraph, Groq, SQLGlot, FastMCP, NetworkX.

## Project Status

Core SQL agent, MCP integration, human approval, self-correction, and Schema Intelligence are implemented.

**QueryMind aims to provide a reusable database intelligence service for AI agents.**