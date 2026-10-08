# FDE Trainer

A practice tool for the fetch–decode–execute cycle (OCR A Level Computer Science, H446). Students are asked what the CPU does next before each step, then watch it happen on a full CPU and RAM diagram.

## Features

### Practice modes
- **What happens next?** — predict each step of the cycle before it is animated
- **Missions** — write short LMC programs to a brief (for example, input a number and output it), then check them against test data and watch them run
- **Bug hunts** — fix programs that don't do what they should, with a hint for each
- Optional value questions such as "What will the MAR hold?"
- Score, streak and best ever tracked

### The diagram
- Von Neumann CPU with ALU, control unit, accumulator, PC, MAR, MDR, CIR and the three buses
16 locations of RAM in assembly or binary, with a trace table
- Ready-made programs, or practise on your own program from the editor

### Extra tabs
- **Build the CPU** and **Inside the RAM**, as in Inside the CPU

## How to Use

1. Open `index.html` in any modern browser (Chrome, Firefox, Edge, Safari). Nothing to install, no login.
2. Choose a program under **Practise on** and press **Start**
3. Before each step, pick what you think the CPU does next
4. Watch the step happen and see whether you were right

## Use Cases

- Independent practice after the FDE cycle has been taught
- Starter or plenary quizzes
- Homework and revision

## Tech

- A single HTML file: HTML, CSS and plain JavaScript
- No libraries, no build step, no backend
- Uses the browser's local storage to remember your best score
- Light and dark themes

---

## License

Copyright © Neil Southin. Free for personal use. Schools, colleges, and organisations wishing to use this in classrooms or on a VLE must get in touch first — see [LICENSE.md](LICENSE.md) for full details or email **southinn@colchsfc.ac.uk**.
