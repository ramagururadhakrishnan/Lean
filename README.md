# Lean Programming

## Intro
- Lean, originally developed by Microsoft Research and now at FRO.
- Lean is interactive theorem prover and a general-purpose programming language based on dependent type theory.
  - dependent type theory unites the program and proof worlds.
- Lean is strict pure functional programming language.
  - _Strictness_ means that function calls in Lean work similarly to the way they do in most languages: the arguments are fully computed before the function's body begins running.
  - _Purity_ means that Lean programs cannot have side effects such as modifying locations in memory, sending emails, or deleting files without the program's type saying so.
  - _functional language_ in the sense that functions are first-class values like any other and that the execution model is inspired by the evaluation of mathematical expressions.
  - _Dependent types_, make types into a first-class part of the language, allowing types to contain programs and programs to compute types.
