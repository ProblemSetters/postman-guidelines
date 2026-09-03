# Instructions

The Postman app is to be built referring to a sample calendar repo. Your repo must keep the same structure, setup flow, formatting, and coding conventions as that sample. The validator in `skills/validate/SKILL.md` checks all of it against `GUIDELINES.md`.

## 1. Clone and study the Node sample

Clone the React + Express (Node/MERN) sample calendar repo as a reference before you begin. Use it to understand the app's structure, setup flow, formatting, coding conventions, and UI quality, then build the Postman app in this repository. The sample is a reference only; it is not the app destination.

```bash
git clone https://github.com/ProblemSetters/coderepo-react-node-calendar.git ../coderepo-react-node-calendar-reference
```

## 2. Keep the project contract in this app repo

These files already belong at the root of this app repository:

1. `AGENTS.md`, before you open an AI assistant. It starts transcript logging.
2. `GUIDELINES.md`. The acceptance contract.
3. `skills/validate/`. The validator, which expects `GUIDELINES.md` at the repo root.

Add these two lines to `.gitattributes` so neither file ships in the HackerRank export:

```text
GUIDELINES.md export-ignore
skills/ export-ignore linguist-documentation
```

## 3. Run and inspect the sample before building

Run the cloned sample and inspect its frontend, backend, manifests, scripts, configuration, and README so you understand the standards you must preserve while building the Postman app.
```bash
bun install && bash setup.sh --seed
```

```bash
bun start
```

Prerequisites, ports, seeded credentials, and commands are in the sample's README.

## 4. Keep what the sample gives you

- **Stack and dependencies.** Same frameworks, database layer, build tool, package manager, and lockfile. Versions at least as recent as the sample. Any new dependency needs a written reason.
- **Setup and run flow.** Same `hackerrank.yml` commands, same ports, same seed-and-reset on start, same `.env.example` handling, same read-only paths.
- **Layout.** Feature folders in the frontend and backend, exactly as the sample groups them. Route, controller, service, and repository stay separate.
- **Formatting and hygiene.** The sample's Prettier config and editor config. No dead code, no debugging output, no external media, American English throughout.
- **UI quality.** The sample's design system, theme, responsive behavior, and state handling (loading, empty, validation, error).

When in doubt, open the matching file in the sample and do it that way.

## 5. Before you submit

1. Copy the log file named in `AGENTS.md` into `transcripts/`.
2. Put any skill you wrote under `skills/`.
3. Run the validator and fix every `FAIL`.
4. Add `content.team@problemsetters.com` as a collaborator and post on Discord.
