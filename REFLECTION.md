/*
Ghaji Mahbub
CSCI 39548
Professor Arezoo Bybordi
EMPLID 24127489
*/

QUESTIONS
 1. Difference between flex-direction: row and flex-direction: column

Answer:
In CSS Flexbox the flex-direction: row arranges flex items horizontally side by side along the main axis and on the contrary, for flex-direction: column it aligns items vertically stacked on top of each other.


2. Why is it important to use relative units (like %, vh, or rem) instead of fixed pixels (px) for
responsive design?

Answer: It is important to use relative units in order to scale fluidly across varying device screen sizes and respect user accessibility font settings. In case of fixed pixels it remains rigid and can cause overflow or readability issues on different displays.


USE OF AI
Answer: Gemini AI. Prompt used- 1st Prompt : "Can I work on the same files for my assignment 2 or do I need to move those files somewhere separate?"

2nd Prompt : How to fix my project showcase image sizes from being distorted?

PIECE OF CODE USED
.project-img {
  width: 100%;
  height: 160px;
  object-fit: cover;
  object-position: center;
  background-color: #f6f8fa;
  border-bottom: 1px solid #d0d7de;
  display: block;
}

MODIFICATIONS:
Instead of overwriting or keeping the old homework files in place I manually backed up and moved the original assignment 1 files into a separate local folder. 
