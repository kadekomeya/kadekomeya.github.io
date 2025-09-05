---
layout: essay
type: essay
title: "(2025) TypeScript - A second look"
# All dates must be YYYY-MM-DD format!
date: 2025-09-04
published: true
labels:
  - TypeScript
---
As time goes on, I have become much more familiar to TypeScript's format, which puts its types after it's variable names unlike C#.  

Despite having type security in the IDE, after compliation it no longer has the type security.  
C# keeps the type security due to its runtime nature.  
I have already made a mistake with it in WOD 1 due to assuming that the client who is using the function would also have the type specification constraints transferred to their IDE.
The final result had type-checking at the top of the function, something that my other programming language, C#, does automatically across shared DLLs and separate user IDEs.
It makes sence given that TypeScript is essentially an IDE addon with type security - It simply does not apply the TypeScript type constraints into the compiled JavaScript itself!

I will make sure in the future to add type security to my TypeScript programs, as well as double-check the inputs.
