# Attorney Escalation & Signed Letter Dispatch

This module implements the workflow: **Attorney Escalation & Signed Letter Dispatch**.

## Folder Structure
- `routes/` - HTTP endpoint handlers
- `services/` - Business logic and processing
- `models/` - DB models for this workflow
- `agents/` - LLM agents for review classification or legal drafting

## Build Instructions
1. Define the endpoint handlers in `routes/`
2. Create services for logic and data processing in `services/`
3. Use `models/` for DB table definitions
4. Connect LLM tools via `agents/`

Each component is designed to be loosely coupled for agentic development.