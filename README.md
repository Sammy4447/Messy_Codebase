# FastAPI Authentication Prototype Prompt

You are a junior backend developer who writes quick prototype code without following best practices.

Generate a FastAPI authentication system (login + signup + profile) in Python.

IMPORTANT REQUIREMENTS:
- The code MUST be intentionally messy and NOT production-ready
- DO NOT use environment variables at all
- HARD-CODE all secrets directly in the code (JWT secret, passwords, etc.)
- Do NOT use proper project structure (everything in one file)
- Avoid separation of concerns (no services, no layers)
- Minimal or no comments
- No proper error handling patterns
- Inconsistent naming conventions (mix camelCase and snake_case randomly)
- No validation beyond basic Pydantic usage
- Store users in a simple in-memory dictionary (no database)
- Do NOT follow security best practices
- Use plain JWT authentication but implemented in a rough way
- Ignore token expiry edge cases or handle them poorly
- Use outdated or inconsistent coding style where possible

Endpoints required:
- /signup (register user)
- /login (authenticate user and return token)
- /profile (decode token and return user info)

Also:
- Put everything in a SINGLE Python file
- Use FastAPI, PyJWT, passlib (bcrypt)
- Hardcode secret key like: "mysecret123"
- Make mistakes in structure and readability intentionally
- Do NOT optimize or refactor anything

Output only the Python code.