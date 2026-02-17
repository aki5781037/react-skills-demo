---
description: Feature Development Workflow
---

# Feature Development Workflow

This workflow guides the Agent through the standard feature development process.

1. **Create Branch**
   - Create a new branch for the feature.
   - Example: `git checkout -b feature/my-feature`

2. **Implement Changes**
   - Write code according to the implementation plan.
   - Follow `CONTRIBUTING.md` guidelines.

3. **Verify**
   - Run verification tools.
   // turbo
   - Command: `cmd /c "npx skills run verify"`

4. **Commit**
   - Commit changes if verification passes.
   - Example: `git commit -m "feat: implement my-feature"`
