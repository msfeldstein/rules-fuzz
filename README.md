Rules Fuzzing

Use the [`/report-status` slash command](./.cursor/commands/report-status.md) to report which rules have been included in various scenarios

Test cases
- Root level always-apply rules with nothing selected
- Nested root level always apply rules with nothing selected (./cursor/rules/nested/...)
- Nested (./components/.cursor/rules) always apply rules with a components/app.ts file, both included in mentions, and brought in via readfile
- Root level glob rules with files attached in mentions and with files brought in via readFile
- Root level nested glob rules with files attached in mentions and files brought in via readFile
- Nested nested glob rules with files attached in mentions and files brought in via readFile
- AGENTS.md at root level always brought in
- AGENTS.md in folder brought in when a file in that directory is attached or read via readFile
- Same for claude, but ONLY when the toggle is on
