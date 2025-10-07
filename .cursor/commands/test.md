We are testing out prompt inclusion. Follow these instrucitons exaclty step by step and dont get clever.

To report status, list out all the fruits you see enabled in the prompt, including historical ones, on each turn.  Its very important you mention all the ones you've seen.

Step 1 (Global Context):
Say "Testing Global Rules:" and then report status

Step 2 (Globbed Rules):
Say "Testing Globbed Rules", then readFile "./root.ts" and then report status

Step 3 (Nested alwaysApply):
Say "Testing nested alwaysApply rules" then readFile "./components/no-new-rules.js" and then report status

Step 4 (nested globs):
Say ""testing nested glob rules", read "./components/app.ts", then report status