# Build Your Own Postman

Guidelines for the HackerRank "Build Your Own Postman" assignment. You build a Postman-inspired API app on top of a sample full-stack calendar repo, and you submit it with your AI transcripts and skills.

This repo does not hold the app. It holds the rules, the requirements, and the verifier. Read the files in the order below.

## Read in this order

1. **[REQUIREMENTS.md](REQUIREMENTS.md)** says what to build. The feature list, the acceptance criteria, and the submission checklist.
2. **[INSTRUCTIONS.md](INSTRUCTIONS.md)** says how to start and how to keep the repo clean. Which calendar repo to clone, what to copy from this repo, the server setup rules, dependency rules, and code hygiene.
3. **[AGENTS.md](AGENTS.md)** turns on transcript logging. Copy it into your cloned repo before you open an AI assistant. It records every turn to a log file that you later export under `/transcripts`.
4. **[GUIDELINES.md](GUIDELINES.md)** is the acceptance contract. Every rule the verifier checks is written here.
5. **[skills/validate/SKILL.md](skills/validate/SKILL.md)** is the verifier. Copy `skills/validate/` into your repo and run it when you are done. It audits structure, stack, dependencies, install, build, start, API behavior, and MongoDB persistence, and it must pass before you submit.

## Sample repos

| Stack | Repo |
|---|---|
| React + Express (MERN) | https://github.com/ProblemSetters/coderepo-react-node-calendar |
| React + Spring Boot | https://github.com/ProblemSetters/coderepo-react-springboot-calendar |
| React + Django | https://github.com/ProblemSetters/coderepo-react-django-calendar |
