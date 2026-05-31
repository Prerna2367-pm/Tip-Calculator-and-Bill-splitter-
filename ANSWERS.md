1. How to Run:-

This project uses only HTML, CSS, and JavaScript.

Steps to run:

1. Save the code in a file named "index.html".
2. Open the file in any web browser such as Google Chrome, Microsoft Edge, or Firefox.

No installation or additional software is required.

Deployment URL: Not deployed.



2. Stack & Design Choices

Frontend Stack

I used HTML, CSS, and JavaScript because they are simple and sufficient for building a basic tip calculator. No external libraries or frameworks were needed.

Design Choice 1: Live Calculation

The calculator updates automatically when the user types in any input field using the "onkeyup" event. This allows users to see the results immediately without clicking a Calculate button.

Affected area:

- Bill Amount input
- Tip Percentage input
- Number of People input

Design Choice 2: Simple Layout

I placed all inputs at the top and all results below them. This makes the application easy to understand and use because users enter values first and then immediately see the calculated results underneath.

3. Responsive, Accessibility, and AI Usage

Responsive Design

On a 360px Phone

The application displays all elements in a single vertical column. Users can scroll if needed, and all inputs remain usable.

On a 1440px Laptop

The application appears on the page with extra empty space around it because no fixed-width layout is used.

Accessibility

Implemented

I used clear text labels above each input field so users know what information to enter.

Not Implemented

I did not add advanced accessibility features such as ARIA labels, keyboard focus styling, or screen reader enhancements because this is a beginner-level project.

AI Usage

Tool Used:

- ChatGPT

What I Asked:

- I asked ChatGPT to help me create a simple tip calculator and bill splitter using HTML, CSS, and JavaScript.
- I also asked for help writing the README and project documentation.

What AI Provided:

- A starter version of the tip calculator code.
- Suggestions for calculating the tip amount, grand total, and per-person share.
- Documentation templates for the README and project explanation.

Changes I Made:

- The AI initially generated a more advanced version with preset tip buttons, detailed validation, and additional styling.
- I simplified the code by removing the preset buttons and extra features.
- I kept only three input fields (bill amount, tip percentage, and number of people), basic validation, and a reset button because I wanted the project to remain at a beginner level and easier to understand.

Why I Changed It:

- The original AI-generated solution was more complex than necessary for my current skill level.
- Simplifying the code made it easier to read, explain, and maintain while still meeting the core functionality of the project.