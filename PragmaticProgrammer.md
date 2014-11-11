## 3: The Basic Tools
### 18. Debugging
- A moth was literally the first bug
- **Tip 24: Fix the Problem, Not the Blame**
- First rule of debugging, **Tip 25: Don't panic**
- Don't waste any energy on "that can't happen" - it can, it did, and you're wrong :)
- Resist urge to fix symptoms, find root cause
- Set compiler warning levels as high as possible
- Gather all acurate data
- Watch user who reported bug, 3rd party data is inaccurate
- Idea: single command to reproduce bug
- DDD for visual debugging
- Examine memory, address over counter example
- Rubber ducking, forces explicitly stating problem
- **Tip 26: "select" Isn't Broken"** - bug likely in your app, not 3rd party library or OS
- **Tip 27: Don't Assume It--Prove it**
- Debugging checklist
  - Is the problem being reported a direct result of the bug or merely a symptom?
  - Is the bug *really* in the OS, compiler?
  - Unit tests pass? What about with *this* data?
  - Do the conditions that cause the bug exist anywhere else in the system?

### 19. Text Manipulation
