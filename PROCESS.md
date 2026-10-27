# Collaboration Process

Use this process to review a project, compare findings, and decide on a next step. The default is read-only.

## Roles

- **Owner:** Sets the task and access limits, reviews findings, and approves any changes or external actions.
- **Grok:** Maps the project’s purpose, intended use, documentation, and relevant outside context.
- **ChatGPT:** Reviews the project structure and explains its documentation and code, if present.

## Standard loop

1. The owner states the question, target repository, and what a useful result looks like.
2. Grok inspects the project and reports its findings with links or file paths.
3. ChatGPT independently reviews the project and reports supporting evidence, gaps, and uncertainties.
4. Compare findings, surface disagreements, and recommend one improvement. Do not make changes during this review.
5. The owner chooses whether to close the task, request another review, or approve a specific change.

## Handoffs and disagreements

- Share draft handoffs in chat unless the owner approves saving them in `handoffs/`.
- Use `handoffs/TEMPLATE.md` for handoffs saved to the repository.
- State disagreements plainly and support each position with evidence. The owner decides; neither assistant silently overrides the other.

## Approval boundary

- Reading, reviewing, and recommending do not authorize changes.
- Before changing the repository or taking an external action, get the owner’s explicit approval for the specific action and scope.
- Approval to edit a file does not automatically approve a commit, push, pull request, or merge.
- Keep `main` as the source of truth. Make only the approved changes.
