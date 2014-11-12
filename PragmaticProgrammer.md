# Pragmatic Programmer: From Journeyman to Master
###### By: Andrew Hunt, David Thomas
![Pragmatic Programmer](http://bks2.books.google.com/books?id=5wBQEp6ruIAC&printsec=frontcover&img=1&zoom=1&edge=curl&imgtk=AFLRE73J5eXHsttYPLsIbkxNyirIq2IUahoFLPuVgHHeXTAXdBskdmCiDDZvZm0V__qtSZRhrDSnrS2iEjOa20hNaw6dnkkIZzy8kOwXKp2-H7OobKs6M6tv9dtGzLAMz552elx7MYW6)

## Ch. 1: A Pragmatic Philosophy
**TODO: re-read all sections for notes**
#### 1: The Cate Ate My Source Code
#### 2: Software Entropy
#### 3: Stone Soup and Boiled Frogs
#### 4: Good-Enough Software
#### 5: Your Knowledge Portfolio
#### 6: Communicate!

## Ch. 2: A Pragmatic Approach
**TODO: re-read sections 7-12 for notes**
#### 7: The Evils of Duplication
#### 8: Orthogonality
#### 9: Reversibility
#### 10: Tracer Bullets
#### 11: Prototypes and Post-it Notes
#### 12: Domain Languages

#### 13: Estimating
  - Tip 18: Estimate to Avoid Surprises
  - Duration Quote estimate in
  - 1–15 days     days
  - 3–8 weeks    weeks
  - 8–30 weeks  months
  - 30+ weeks    think hard before giving an estimate
  - good trick: ask someone who's already done it
  - understand what's being asked
  - model, options
  - break the model into components
  - assign estimated values
  - "three quarters of a second" vs "750 ms"
  - keep track
  - Incremental development
    - Check requirements
    - Analyze risk
    - Design, implement, integrate
    - Validate with the users
  - Tip 19: Iterate the Schedule with the Code
  - Bonus: What to say when asked for an estimate: "I'll get back to you"
  - Slow down and think
  - Challenge: Log estimates. How accurate was I? If error > 50%, where did I go wrong?

## Ch. 3: The Basic Tools
  - Get comfortable with the basic tools. Shell, text editor, version control, glue (e.g. perl, python). Let need drive acquisition. Look out for better way of doing things. 
  - **Tip 20: Keep knowledge in plain-text, e.g. properties**
  - Only issue is that it's out of context

#### 14: The Power of Plain Text
  - Pragmatic Programmers don’t just cut code, or develop object models, or write documentation, or automate the build process we do all of these things.
  - GUIs
    - Pros: WYSIWYG
    - Cons: WYSIAYG
  - **Tip 22: Use a Single Editor Well**
  - Pick a powerful editor and learn it well.

#### 15: Shell Games
  - A workbench
  - Automation, combination
  - *Tip 21: Use the Power of Command Shells*

#### 16: Power Editing

#### 17: Source Code Control
  - Tip 23: Always Use Source Code Control

#### 18. Debugging
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

#### 19. Text Manipulation
- General purpose text manipulation tool
- Take time to master, can be powerful in right hands, can destroy like routers in woodworking
- Unix command shell, awk, sed
- More OO: Python, Tcl, Ruby, Perl
  - PragProg prefer Ruby, Perl
- **Tip 28: Learn a Text Manipulation Language**
