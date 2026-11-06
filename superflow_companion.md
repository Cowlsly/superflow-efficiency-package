# Superflow Workflow Companion File

This file accompanies the main Superflow prompt. It is loaded with it and defines the efficiency package additions.

## Purpose
Make Superflow more efficient by preferring root/main writes, practical completion over pure minimalism, recorded changes, and final documentation updates.

## Preexisting Files This Companion Uses
- prompts/implementer.md (base)
- prompts/testing-guidelines.md
- SKILL.md
- references/phase2/workflow.json
- .superflow/test-env.json (if present)
- llms.txt / CLAUDE.md (if present)

## Efficiency Package Rules
1. Prefer writing working code directly into the current branch or main when the git mode allows (trunk_based, solo_single_pr).
2. Complete the feature. Supporting code required for integration is in scope.
3. Practical TDD: batch related tests when faster. Observe red-green where practical.
4. Record every create / move / delete / modify in the final report and commit messages.
5. Final mandatory step: amend all necessary documentation (README, llms.txt, CLAUDE.md, CHANGELOG) so the repo stays accurate. Delete dead docs or update stale ones. Record the changes.

## Last Step (Required)
Before marking DONE:
- Amend every affected documentation file.
- Create, move, delete, or modify any supporting files needed.
- Record all changes in the report and in the commit message.
- Ensure the free version has no Shizuku; pro notes go only in the private repo plan.

This companion is part of the Superflow efficiency package.
