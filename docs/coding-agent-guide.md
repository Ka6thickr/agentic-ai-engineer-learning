# Coding Agent Guide

Use this repository as a 12-week learning workspace for GitHub Copilot Agent and Codex.

## Working conventions
- Prefer C# for the main exercises and use Python for comparison where useful.
- Keep each change focused on the current lab or issue.
- Add tests for new behavior.
- Keep external service integrations behind interfaces so labs can use mocks when services are unavailable.
- Update the relevant README when behavior changes.
- Run the available build and test commands before finishing a task.
- Summarize files changed, tests run, and anything that could not be validated.

## Suggested .NET validation
```bash
dotnet restore
dotnet build --no-restore
dotnet test --no-build
```

## Suggested agent task format
1. Read the relevant lab README and issue.
2. Describe the expected files to change.
3. Implement the smallest complete change.
4. Add or update tests.
5. Run validation.
6. Summarize results and remaining risks.
