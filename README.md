# Assistant Workbench

A small shared workspace for asking AI assistants to inspect a project, compare ideas, and leave clear handoffs.

## How we use this repository

- Keep the `main` branch as the source of truth.
- Start with read-only requests: inspect, explain, research, and recommend.
- Put handoff notes in `handoffs/` so another assistant can continue from the same facts.
- Treat suggestions as drafts. The owner decides whether to make changes or take external actions.
- Do not put passwords, API keys, private customer data, or anything confidential here.

## A simple GitHub guide

- A **repository** (repo) is the project folder plus its change history.
- A **commit** is a saved snapshot with a short description.
- A **branch** is a separate draft line of work; it leaves `main` alone.
- A **pull request** (PR) is a proposal to bring a branch's changes into `main`. Review it before merging.
- **Read access** lets someone view and copy the project. **Write access** can change it.

## First exercise

Ask one assistant to read this repository and explain its contents. Ask the other to review that explanation against the files. Save a short result in `handoffs/` only after reviewing it yourself.

## Read-only setup

For the simplest read-only trial, make this repository public and keep it free of sensitive information. Anyone can then read it, while you retain ownership. When connecting an assistant, review the GitHub permission screen and grant access only to this repository and only the permissions needed to read it. If an integration asks for write access, do not approve that grant for this trial.

If the repository must be private, use an organization-owned repository and grant the assistant's GitHub App the **Read** role (or selected-repository, read-only app permissions). A private repository owned by a personal GitHub account does not support read-only collaborator access: personal-account collaborators get read/write access. See GitHub's [personal repository permissions](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/repository-access-and-collaboration/permission-levels-for-a-personal-account-repository).

## Handoffs

Copy `handoffs/TEMPLATE.md` for each task. Include what was asked, what was checked, links to evidence, what remains uncertain, and the suggested next step.
