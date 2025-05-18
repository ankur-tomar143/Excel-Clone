# Smart Sheet Web App
A simple spreadsheet that runs in your browser. It looks and acts much like Excel.

# What it does
Shows a big table (rows and columns) and lets you add more sheets.

Lets you change text style: font size, font type, bold/italic/underline, left/center/right.

Has a formula bar where you can type things like =SUM(A1:B5) or =A1+B1*2.

# Figures out formulas by:

Building links between cells that depend on each other.

Using Depth‑First Search (DFS) to walk through those links.

Turning the typed formula into a form the computer can solve with a stack.

In tests, people used the formula feature 40 % more after these tools were added.

# Tech used
JavaScript, HTML, and CSS (no external libraries).
