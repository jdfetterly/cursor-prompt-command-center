
# AI Agents & Automations Prompting Cheat Sheet for Cursor (and Other AI Code Assistants)

Use this cheat sheet to design, build, and optimize AI-powered agents and automated workflows—ideal for n8n, Replit bots, OpenAI function-calling, and productivity hacks.

---

## 1. Designing Agent Roles & Responsibilities

**Prompt Examples:**
1. Define a GPT agent that acts as a customer support rep.
2. Create a research assistant agent for competitive analysis.
3. Describe the role of an AI concierge for onboarding users.
4. Design a CMO agent that creates content and marketing strategy.
5. Define the boundaries of a finance bot that summarizes budgets.
6. Write role instructions for a project manager agent.
7. Create a GPT that serves as a prompt librarian.
8. Set up an “ops agent” to track tasks and report blockers.
9. Design a technical support bot that escalates when needed.
10. Define agent behaviors for responding to vague user prompts.

---

## 2. Multi-Step Workflow Planning

**Prompt Examples:**
1. Create a flow that extracts text from email and adds it to Notion.
2. Build a step-by-step process for summarizing long docs into bullets.
3. Generate a workflow to turn calendar events into follow-up email drafts.
4. Create a system that turns Slack messages into GitHub issues.
5. Use n8n to extract, transform, and send Google Sheet data to email.
6. Chain together GPT + Zapier to auto-tag leads based on form input.
7. Build a reminder system that checks task status and sends alerts.
8. Combine calendar, Gmail, and notes into a daily summary.
9. Trigger a workflow when a new blog post is published.
10. Create a pipeline that takes screenshots of pages and stores summaries.

---

## 3. Prompt Engineering for Reliable Behavior

**Prompt Examples:**
1. Format responses as JSON and wrap with triple backticks.
2. Include “you are” and “your goal is” for context anchoring.
3. Use few-shot examples to demonstrate the expected output.
4. Add explicit rules: “Never respond unless...” or “Only use this format.”
5. Clarify response length limits (e.g., “Use fewer than 3 sentences.”)
6. Use checklist-style formatting for reliable parsing.
7. Instruct the agent to ask clarifying questions before acting.
8. Add fallback text for when data is missing.
9. Define how to handle unrecognized commands gracefully.
10. Specify structured fields for function-calling agents.

---

## 4. Memory, Context, and Persistence

**Prompt Examples:**
1. Instruct this agent to remember user preferences across chats.
2. Add a summary of past interactions to the system prompt.
3. Create a prompt that stores and updates a running to-do list.
4. Use vector embeddings to retrieve related user history.
5. Summarize this chat and persist key info in a database.
6. Ask the user if they want to save new items to memory.
7. Update context with the most recent summary after each task.
8. Use context compression to stay under token limits.
9. Keep recent inputs in a rolling memory window.
10. Distinguish short-term vs long-term memory usage in prompts.

---

## 5. Function Calling (OpenAI or Local Agents)

**Prompt Examples:**
1. Define a function for scheduling events and parsing date/time.
2. Write a JSON schema for a `send_email` function.
3. Add a fallback response if function output is null.
4. Format the output so it’s valid for function parsing.
5. Simulate user confirmation before calling a sensitive function.
6. Chain multiple function calls to build a compound response.
7. Add tool descriptions to help the model pick the right one.
8. Use structured input validation on all arguments.
9. Create a summary of what each tool does for developer docs.
10. Return multiple formats (plain + structured) for debug/testing.

---

## 6. Error Handling & Recovery

**Prompt Examples:**
1. Add a retry prompt if the API call fails.
2. Create a system fallback when data is missing or incomplete.
3. Instruct the agent to ask the user for clarification when needed.
4. Detect and flag when the model returns hallucinated data.
5. Add a timeout warning if the operation is taking too long.
6. Roll back to a previous state if function call fails.
7. Log unrecognized input for future training.
8. Respond with “I don’t know” when unsure—don’t guess.
9. Include a debug mode that prints raw outputs.
10. Suggest the next best action if the first attempt fails.

---

## 7. Use Cases & Ideas for Agents & Automations

**Prompt Examples:**
1. Build a founder dashboard assistant that gives daily summaries.
2. Create a marketing copy generator for feature announcements.
3. Build a custom note-taking AI that syncs to Google Docs.
4. Generate social content from calendar events automatically.
5. Develop a “focus mode” GPT that blocks distractions and tracks time.
6. Create a Slack bot that answers internal process questions.
7. Build a lead scoring assistant using GPT + CRM data.
8. Build an AI QA agent that flags bugs in PRs before review.
9. Develop a status update generator for team standups.
10. Use GPT to clean up raw user data and tag it for analysis.

---

## Quick Reference: Tools & Integrations

| Area           | Tools / Terms                               |
|----------------|---------------------------------------------|
| Agents         | OpenAI Assistants, Custom GPTs, LangChain    |
| Workflows      | n8n, Zapier, Make.com, Replit, Airplane.dev  |
| Prompts        | System prompts, JSON outputs, function calls |
| Context        | Memory tokens, vector embeddings, metadata   |
| Debugging      | Logs, fallback prompts, “Why did this fail?” |

---

This cheat sheet helps you build and operate AI-powered tools that automate tasks, scale communication, and create leverage across your stack.
