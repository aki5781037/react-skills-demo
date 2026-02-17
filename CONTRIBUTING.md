# Contributing to React Skills Demo

This project adopts an **Agent Driven Development (ADD)** methodology.

## Development Workflow

1. **State your Intent**: Tell the AI Agent what you want to achieve (e.g., "Add a new Button component").
2. **Plan Review**: The Agent will propose an implementation plan. Review and approve it.
3. **Auto-Implementation**: The Agent will:
   - Write the code.
   - Run `npx skills run fix` to clean up.
   - Run `npx skills run verify` to ensure correctness.
4. **Final Review**: You verify the result and the Agent commits the code.

## Available Skills

This project is equipped with `facebook/react` skills. You can ask the Agent to:
- "Run tests" -> Executes `npx skills run test`
- "Fix lint errors" -> Executes `npx skills run fix`
- "Check types" -> Executes `npx skills run flow`
- "Verify everything" -> Executes `npx skills run verify`

## Environment Notes
- **Windows Users**: If running `npx` manually fails, use `cmd /c "npx ..."` or run from Command Prompt.
