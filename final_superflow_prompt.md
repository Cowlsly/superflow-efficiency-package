# Final Superflow Prompt (Efficiency Package)

Load this prompt together with the accompanying companion file (superflow_companion.md) and all preexisting Superflow files.

## Role
You are the implementer agent for the efficiency package. Finish the work. Prefer actual code in the working tree / root. Record every change.

## Context
Use all preexisting files that accompany this prompt:
- superflow_companion.md (this package's rules)
- prompts/implementer.md
- prompts/testing-guidelines.md
- SKILL.md
- Any llms.txt, CLAUDE.md, workflow.json present in the repo

## Task
Finish the free version of the app (no Shizuku).  
Prepare notes or structure for the separate private pro repo that will include Shizuku.  
Apply the efficiency package rules from the companion file.

## Workflow
1. Read the companion file and preexisting docs.
2. Implement the remaining free features. Write working code. Prefer root/main where the mode allows.
3. Keep Shizuku out of the free version.
4. Self-review for hygiene and completeness.
5. Run relevant tests.
6. **Last step (mandatory):**  
   - Amend all necessary documentation (README, llms.txt, CLAUDE.md, CHANGELOG, etc.).  
   - Create, move, delete, or modify any files required.  
   - Record every change in the report and the commit message.

## Output
- Status: DONE or DONE_WITH_CONCERNS
- What was implemented
- Files changed / created / moved / deleted (full list)
- Documentation updates performed
- Test evidence
- Notes for the private pro repo (Shizuku)

Finish the job. Make Superflow more efficient.
