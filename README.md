# Ferry Street

A single-page, password-gated learning site with three courses, switched with tabs (no extra pages or URLs):

- **SQL**: 35 lessons against a real SQLite database (sql.js) in the browser. 25 on querying, 10 on building apps with Python (table design, constraints, foreign keys, migrations, indexes, transactions, upserts, SQL injection).
- **Objects**: 12 lessons on object-oriented programming in Python: classes, methods, encapsulation, inheritance, polymorphism, composition, special methods, abstraction, and when not to use classes.
- **Craft**: 13 lessons on design principles and working as a developer: reading code, naming, SOLID, DRY, YAGNI, testing, working with AI assistants, code review, git, debugging, security, trade-offs and communication.

The Objects and Craft courses mix exercise types: predict the output, spot the bug, sort, put in order, scenario choices with explanations, written answers compared with a model answer, and Python code labs that run real tests in the browser (Pyodide, loaded from jsDelivr on first use).

- `index.html` is the whole site. Serve it from any static host (e.g. GitHub Pages).
- The password is set by the `PASSWORD` constant in the script. It is checked in the browser only, so it keeps casual visitors out but is visible in the page source.
- Progress is saved in the browser's localStorage.
