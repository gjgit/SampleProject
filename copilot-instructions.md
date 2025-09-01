# .github/copilot-instructions.md

# Copilot Instructions for This Repository

## SQL Query Rules
- Do not use `SELECT *` in SQL queries. Always list the required columns explicitly for clarity, readability, and performance.
  - Example:  
    ```sql
    SELECT * FROM users;
    ```
  - Example:  
    ```sql
    SELECT id, name, email FROM users;
    ```

## General Guidance
- Prefer explicit, clear, and maintainable code over shortcuts.
- Follow project coding style and best practices.
