Rules Fuzzing

First check the basics with the [`/test` slash command](./.cursor/commands/test.md). It will walk through testing the basics of rule inclusion.

Outputs (rules will coalesce so we just show whats added on each step):
Step 1 (Global Context): 
    - Blueberry (global mdc)
    - Kiwi (root AGENTS.md)

Step 2 (matching glob from root):
    - Pineapple (global glob mdc)

Step 3 :
    - Peach (nested alwaysApply)
