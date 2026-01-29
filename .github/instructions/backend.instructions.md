---
applyTo: "backend/**/*,*.py"
---

## Backend Guidelines

- All API endpoints must be defined in the `routers` folder.
- Load example database content from the `database.py` file.
- Log detailed errors (including stack traces and sensitive information) only on the server. Do not expose these details to the frontend; instead, return appropriate HTTP status codes and user-friendly error messages (for example, "Unable to load activities" or "Registration failed").
- Ensure all APIs are explained in the documentation.
- Verify changes in the backend are reflected in the frontend (`src/static/**`). If possible breaking changes are found, mention them to the developer.