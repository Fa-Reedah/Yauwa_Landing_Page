ANTIGRAVITY OPERATING RULES & PERMISSIONS
CRITICAL DIRECTIVE: You must read and obey these rules before executing any terminal command, running any script, or applying any file edit.

1. AUTO-APPROVE (DO NOT ASK FOR PERMISSION)
You are explicitly authorized to run the following commands and make the following edits without asking me for confirmation. Do not interrupt my workflow for these:

Read-Only Terminal Commands: ls, dir, cat, head, tail, grep, find, pwd, echo.

Git Status & History: git status, git diff, git log, git branch, git remote -v.

Linters & Formatters: ruff check ., black ., prettier, eslint (running checks/formatting only).

Test Suites: Running pytest, unittest, or any local test command.

Safe Python Probing: Running python -c "print(...)" or checking imports (e.g., python -c "import app.main").

Git Staging & Committing: git add <file>, git commit -m "..." (Do not ask to stage or commit, but DO NOT push unless authorized).

Standard File Edits: Applying diffs or editing .py, .html, .css, .js, .md files (as long as you are not deleting entire files or overriding massive blocks of code blindly).

Creating Folders: mkdir -p <directory>.

2. STRICT CONFIRMATION REQUIRED (ALWAYS ASK)
You must stop, explain exactly what you are about to do, and wait for my explicit "Yes" before executing any of the following:

Destructive File Operations: rm, rm -rf, del, or overwriting a file entirely without showing me a diff first.

Destructive Git Operations: git push, git reset --hard, git clean -fd, git rebase, or force pushing.

Database Mutations: Running alembic upgrade head, alembic downgrade, dropping tables, or writing to a production database (e.g., Railway).

Installing Dependencies: pip install, npm install, or modifying requirements.txt / package.json. (Check if the dependency already exists first).

Environment Variables: Modifying .env, reading .env, or exposing API keys/passwords in the terminal output.

Running Untrusted Scripts: Executing a script that downloads files from the internet or makes external POST requests (other than standard API testing).

3. WORKFLOW & BEHAVIORAL CONSTRAINTS
No Unsolicited Pushes: Never run git push unless I explicitly say "push to GitHub".

Never Modify Secrets: Never print, modify, or commit .env, .env.local, or API keys.

No Silent Deletions: If a refactor requires deleting a function, class, or file, you must explicitly point it out in your response before doing it.

Stop Hallucinating: If you don't know the exact command or file path, run a read-only command (ls or grep) to find it first. Do not guess.

Keep Explanations Brief: Do not over-explain code you write. Just state what you did and show the diff.

4. TERMINAL OUTPUT PROTOCOL
When you run an auto-approved command, you do not need to show me the terminal output unless:

The command throws an error.

I ask to see the output.
Otherwise, just proceed to the next step.

