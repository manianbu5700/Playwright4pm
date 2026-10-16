# Instructions

- Following Playwright test failed.
- Explain why, be concise, respect Playwright best practices.
- Provide a snippet of code with the fix, if possible.

# Test info

- Name: example.spec.js >> get started link
- Location: tests\example.spec.js:11:5

# Error details

```
Error: browserType.launch: Target page, context or browser has been closed
Browser logs:

<launching> C:\Users\Manikandan\AppData\Local\ms-playwright\webkit-2370\Playwright.exe --inspector-pipe --disable-accelerated-compositing --headless --no-startup-window
<launched> pid=23416
Call log:
  - <launching> C:\Users\Manikandan\AppData\Local\ms-playwright\webkit-2370\Playwright.exe --inspector-pipe --disable-accelerated-compositing --headless --no-startup-window
  - <launched> pid=23416
  - [pid=23416] <gracefully close start>
  - [pid=23416] <kill>
  - [pid=23416] <will force kill>
  - [pid=23416] <process did exit: exitCode=3236495362, signal=null>
  - [pid=23416] starting temporary directories cleanup
  - [pid=23416] finished temporary directories cleanup
  - [pid=23416] <gracefully close end>

```