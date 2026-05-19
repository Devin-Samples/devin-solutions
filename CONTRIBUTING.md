# Contributing to Devin Solutions

This repo is a catalog — it indexes Devin-Powered and Devin-Driven repos in the `Devin-Samples` org. To add your solution:

## Adding a New Entry

1. Fork this repo and create a branch
2. Add your repo to the appropriate table in `README.md`:
   - **Standalone Solutions** for individual Devin-Powered repos (alphabetical order)
   - **Devin-Driven Solutions** for platform-centered strategic content repos (alphabetical order)
   - **Aggregate Collections** for multi-example repos (alphabetical order)
3. Add a corresponding entry to `catalog.yaml`
4. Open a PR with:
   - Link to the repo being indexed
   - Brief description of how Devin is involved (runtime participant or platform-centered narrative)
   - Confirmation that the solution is Devin-Powered (interacts with Devin APIs, triggers sessions, etc.) or Devin-Driven (platform drives organizational transformation)

## Entry Requirements

- The repo must be in the `Devin-Samples` GitHub org
- The solution must be **Devin-Powered** (Devin is a runtime participant) or **Devin-Driven** (the Cognition platform drives organizational transformation)
- The repo must have a README with at minimum: description, prerequisites, and quickstart
- Set the repo description on GitHub to include the `[Devin-Powered]` or `[Devin-Driven]` tag

## catalog.yaml Schema

Each entry in `catalog.yaml` must include:

| Field | Required | Values |
|-------|----------|--------|
| `name` | Yes | Repo name (without org prefix) |
| `url` | Yes | Full GitHub URL |
| `description` | Yes | One-line description |
| `tech_stack` | Yes | Array of primary technologies |
| `type` | Yes | `standalone` or `aggregate` |
| `status` | Yes | `available`, `in-progress`, or `planned` |
| `tags` | No | Array of freeform tags for filtering |
| `layer` | No | `devin-powered` (default) or `devin-driven` |
