# Lab 12 · Name formatter

**Week 12 · std::string**  
**Theme:** Text is data  
**Type:** Lesson week


## Demo video (required)

Paste a link to a short video of you running this assignment (tool + code + run).
Work without a working video link is incomplete.

**Your demo:** _add your link here_


## Scenario
A string is data you can join, measure, and pass. Read first and last name, build the full name, hand it to a helper, and print the length.

## Goals
- Read first and last with two prompts (`cin >>` still stops at a space)
- A helper that **returns** a string (`banner`, initials, or a label)
- Pass the name as `const std::string&`
- Print `size()`
- Push + short demo + Canvas

## Starter
Use `main.cpp`. `banner` is sketched.

## Environment
VS 2022 · **GitHub Codespaces** · Replit · library machines

## Procedure
1. `#include <string>`
2. Read first and last. Join with a space
3. Finish `banner` so it returns a new string
4. Print the banner and the length
5. Commit, push, short demo, Canvas

## Sample output
```
First: Ada
Last: Lovelace
Hello, Ada Lovelace!
Length: 13
```

## Definition of done
- Join + return + `size()`
- `const std::string&` on the helper
- Repo + short demo + Canvas

## Rubric (100)
| Criterion | Pts |
|-----------|----:|
| Runs correctly on a supported path | 40 |
| Meets prompt requirements | 30 |
| String treated as data | 15 |
| GitHub + short demo video | 15 |

## Scope fence
No `char[]` required. No regex. Two `cin >>` fields are safer than mixing `getline` this week.

## Tips
- `"Ada"` is not `"ada"` — case matters
- The space in `first + " " + last` is yours to add
- `#include <string>` or the type isn’t there

## Help (`/ring`)
After a real try, include: goal · what you tried · exact error · screenshot/repo · OS + tool.

## Getting started

1. Fork this repo on GitHub.
2. Clone your fork.
3. Compile and run:

```bash
g++ -std=c++17 -o program main.cpp && ./program
```

On Windows (Visual Studio), open `main.cpp` and use **Local Windows Debugger**.
4. Record a short demo that shows your tool, your code, and a real run.
5. Paste the video link in the **Demo video** section above.
6. Submit your fork URL on Canvas.
