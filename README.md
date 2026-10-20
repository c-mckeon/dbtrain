# Ferry Street

A single-page, password-gated site for learning SQL from scratch. 35 lessons (25 on querying, 10 on building apps with Python: table design, constraints, foreign keys, migrations, indexes, transactions, upserts and SQL injection) run against a real SQLite database (sql.js) in the browser, set in a small record shop.

- `index.html` is the whole site. Open it locally or serve it from any static host (e.g. GitHub Pages).
- The password is set by the `PASSWORD` constant in the script. It is checked in the browser only, so it keeps casual visitors out but is visible in the page source.
