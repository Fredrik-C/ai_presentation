# Memorybank Instructions
- Start by searching `memorybank` folder for which `<feature>_masterplan.md` are available, if multiple, prompt the user which one we should work with and read that memory bank.
- Read corresponding `<feature>_decisions.md`.
- Prompt the user with a list of uncompleted tracks to select which track we should work with. The list should be ordered as in the plan.
- Read the relevant `<feature>_track_<name>.md' with implementation detals. Use checkmarks for progress.
- Track descissions as a bullet list in `<feature>_decisions.md`.

# Implementation instructions
- There must be tests covering the added functionality
- IMPORTANT: All tests must pass before task is completed
- When task is completed, promt the user for acceptance.
- If completion is accepted
    1. Set as completed in `<feature>_masterplan.md`
    2. Update progress in `<feature>_track_<name>.md'
    3. Start a new task with `new_task`