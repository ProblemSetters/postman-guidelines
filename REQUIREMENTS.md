# Requirements

## Overview

Build a Postman-inspired API app that helps developers create, organize, and analyze HTTP requests. Think beyond a request form and a pretty JSON viewer.

The app is full-stack. It keeps the React frontend and the backend of the sample calendar repo you clone (Spring Boot, Express, or Django), and it persists data in MongoDB. Every feature you ship must work end to end: a usable screen, a real API call, a backend handler, and stored data.

Pick five to ten features from the list below, or add your own of the same weight. Fewer than five is under scope. More than ten spreads the work too thin.

## Feature set

- **API request builder.** Compose a request with method, URL, query params, headers, and body. Send it and see the response.
- **Request collections.** Save requests into named collections and folders. Rename, reorder, duplicate, and delete them.
- **Environment management.** Define named environments with variables (base URL, tokens). Switch the active environment and resolve `{{variable}}` placeholders at send time.
- **Authentication support.** Attach auth to a request or a whole collection: bearer token, basic auth, API key in header or query.
- **HTTP response analysis.** Show status, timing, size, headers, and a formatted body (JSON, XML, HTML, plain text). Search and collapse inside the body.
- **Request history.** Record every sent request with its response. Re-open, re-send, or save a history entry into a collection.
- **Import and export.** Bring in a Postman collection or an OpenAPI file, and export your collections in a shareable format.
- **Test assertions.** Write simple checks against a response (status equals, body path contains) and see pass or fail after each send.
- **Code snippet generation.** Produce a curl, fetch, or language-native snippet for the current request.
- **Workspaces and sharing.** Group collections and environments per workspace and share a workspace with another seeded user.

## Acceptance criteria

- **Five to ten features**, each working end to end through the UI, the API, and MongoDB.
- **Human judgment is visible.** AI can write the code. Feature selection, architecture, and production readiness must be your own decisions, and the transcripts should show it.
- **Modern, polished UI.** Responsive, keyboard accessible, with loading, empty, validation, and error states where they apply.
- **Clean checkout works.** The app installs, builds, and starts without errors using the commands in `hackerrank.yml`.
- **Current stack.** Dependency versions are at least as recent as the sample calendar repo. Do not downgrade, and do not swap out the declared stack.
- **Matches the sample repo in scope, structure, and quality.** Use the calendar app as the bar for what "done" looks like.
