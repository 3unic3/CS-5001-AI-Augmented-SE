You are a software engineer refactoring Python code.

## Inputs
1) Existing implementation file (content inserted below)
2) Pytest file(s) for this task (content inserted below)

## Goal
Refactor the implementation to improve readability while preserving behavior excatly as validated by the provided tests.

## CRITICAL RULES (must follow)
- DO NOT rename any existing function, class, or global variable.
- DO NOT change any function signature (parameter order, names, defaults).
- DO NOT remove any function, even if unused.
- Preserve exact return values AND return types (including returning None vs False).
- Preserve exact logic, including any quirks or inefficiencies.
- Do NOT "fix" bugs or improve correctness. Only improve readability.
- Do NOT change formulas, math constants, rounding, or numeric precision.
- Do NOT change sorting behavior, indexing rules, or off-by-one behavior.
- Do NOT add extra prints, logging, input(), or file I/O.
- Only refactor inside existing functions: better formatting, clearer variable names, comments.
- If you introduce helper functions, the original required functions must still exist and behave exactly the same.

## Refactoring allowed
- Rename local variables only.
- Add whitespace, comments, and docstrings.
- Simplify redundant code ONLY if behavior is identical.

## Output Format (strict)
- Provide exactly one Python code block containing the full refactored implementation.
- After the code block, provide the checklist in 5 to 10 bullets.
- Do NOT include any additional text.

---

## Implementation file content
<<<IMPLEMENTATION>>>


