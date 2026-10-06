# Project Rule — Execution Gate

**Devin performs NO tool calls, file edits, script runs, or modifications of any kind unless the user's message contains the exact phrase `okay run this`.**

- Always state the plan or understanding first in plain text
- Wait for the literal phrase `okay run this` before any execution
- This applies to fixes, builds, patches, diagnostics that write files, and any command that changes state
- If the user reports a bug or asks "why is X broken" — explain only, do not fix until gated
- No exceptions, no interpretation, no "they implied it"
