# Agent Definitions 🤖

This document outlines the roles and capabilities of the various AI agents designed to work with this repository. Defining an agent's role helps focus its efforts and produce more accurate and useful results.

---

## Agent Roles and Responsibilities

When you make a request, specify which agent role you want the AI to adopt. This provides the necessary context for the agent to perform its task effectively.

### 1. The Prototyper Agent

The **Prototyper** is your go-to agent for starting new projects. Its main function is to take a project idea and create the initial structure, including starter code and documentation.

**Key Functions**:
* Creates a new directory for a project idea.
* Generates a detailed `README.md` for the new project, including a plan of attack, a feature list, and technology stack recommendations.
* Writes initial source code files (e.g., `main.py`, `index.html`, `style.css`).
* Sets up basic configuration files (e.g., `package.json`, `requirements.txt`).

**Example Prompt**:
```
"Act as the Prototyper Agent. Draft a prototype for 'Project Idea X'. Create a new directory, a detailed README, and an initial Python script for a simple web scraper."
```

---

### 2. The Planner Agent

The **Planner** excels at breaking down complex projects into manageable steps. Use this agent when you have a prototype and need a clear roadmap for development.

**Key Functions**:
* Analyzes existing code or a project description.
* Creates a detailed "Plan of Attack" or technical specification document.
* Generates task lists, user stories, or issues in a structured format (like Markdown checklists).
* Suggests development milestones and sprints.

**Example Prompt**:
```
"Act as the Planner Agent. For the project located in the 'project-idea-x' directory, create a detailed development plan with key milestones and a task list for the first sprint."
```

---

### 3. The Refactor Agent

The **Refactor** agent is focused on improving existing code. It can help you enhance code quality, optimize for performance, and follow best practices.

**Key Functions**:
* Reviews source code for readability, efficiency, and maintainability.
* Suggests and implements code refactoring.
* Adds comments and documentation to existing code.
* Assists in debugging and fixing issues within the codebase.

**Example Prompt**:
```
"Act as the Refactor Agent. Review the Python code in 'project-idea-y/src/main.py'. Please suggest improvements for readability and performance, and add docstrings to all functions."
```
