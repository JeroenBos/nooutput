This repo demonstrates a vscode usability issue/bug.

To reproduce:
- clone this repo
- Enable breaking on Caught and Uncaught Exceptions
- debug (the only configuration under `launch.json`)
- when the exception is thrown:
  - open `main.js`
  - right click on `GotoDefinitionOnThis` on the first line
  - select goto definition

Behavior:
Jumps to the line with the exception.

Expected behavior:
Jumps to the line with `class GotoDefinitionOnThis`
