# Sensitive working sessions and sanitized handoffs

Follow the normal collaboration loop in `PROCESS.md`; use this additional procedure when sensitive details are involved.

Use this procedure when a conversation includes details that should not appear in the shared repository.

## 1. Private working conversation

- Share only the sensitive information needed to answer the question.
- Keep the conversation limited to the assistants and account or workspace you trust with that information.
- Don’t assume that “private chat” means information can never be retained or accessed under the service’s settings and policies. Check those settings before sharing anything highly sensitive.
- Each assistant works only from what you provide directly in its conversation. You decide what, if anything, to relay between assistants.

## 2. Work and discuss privately

- The assistant may use the information in the conversation to analyze options, identify trade-offs, and recommend next steps.
- Treat drafts that include sensitive details as private working material. Don’t copy them into the shared repo, issues, pull requests, or other shared spaces.
- If you want another assistant to review the work, prepare a sanitized question or summary first. Share only what you approve.

## 3. Prepare a sanitized handoff

Before anything moves to the shared repo, create a separate version that contains only information safe for public release.

- Retain the useful goals, functional roles, decisions, constraints, and next steps.
- Remove identifiers and operational specifics, including names, locations, device or service details, network and access information, configurations, security weaknesses, and private workflows.
- Check for indirect clues: details that may identify a person, setup, or plan when combined, even if each detail seems harmless alone.
- Don’t include a sensitive attachment or link as supporting evidence.

## 4. Review before sharing or saving

- The assistant should show the proposed sanitized text to you first and flag anything that may still be identifying.
- You review it in context and decide whether it is safe to share.
- Your approval must identify the specific text and destination. Approval to discuss or redact does not approve saving or publishing.
- Repo changes, commits, pushes, pull requests, and other external actions each require your explicit approval as applicable.

## 5. If in doubt

Keep the material in the private conversation. Ask for a more abstract summary, or omit the detail. A useful repo record can say that a decision was made and give its general rationale without exposing the underlying private facts.

## Flow

1. Discuss and analyze privately.
2. Prepare a separate sanitized draft.
3. Review it together for direct and indirect clues.
4. You approve the specific text and destination.
5. Save or share it only as approved.
