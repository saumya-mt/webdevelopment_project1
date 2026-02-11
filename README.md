# Sudoku Master

Mock Sudoku website for a web dev assignment - HTML and CSS only.

## Links

**Live site:** [https://saumya-mt.github.io/webdevelopment_project1/](https://saumya-mt.github.io/webdevelopment_project1/)

**Repo:** [https://github.com/saumya-mt/webdevelopment_project1](https://github.com/saumya-mt/webdevelopment_project1)

**Collaborators:** None

**Video walkthrough:** https://northeastern-my.sharepoint.com/personal/mishra_sau_northeastern_edu/_layouts/15/stream.aspx?id=%2Fpersonal%2Fmishra%5Fsau%5Fnortheastern%5Fedu%2FDocuments%2FRecordings%2FWeb%20Development%20%2D%20Project1%2D20260207%5F161927%2DMeeting%20Recording%2Emp4&referrer=StreamWebApp%2EWeb&referrerScenario=AddressBarCopied%2Eview%2E1937a831%2Dfe3f%2D4ec5%2Db834%2D0f0ec70ce7ab


---

## Writeup

**What was the most challenging piece? Did you find it easy or challenging to work with HTML and CSS? How long did it take?**

The Sudoku grids were definitely the hardest part. Getting the borders right for the sub-grids took a while. I had to mess with the grid layout a lot and add extra border classes on specific cells. Figuring out the navbar so it stayed fixed but didn’t cover the content was also tricky at first. HTML felt pretty straightforward once the structure was clear, but CSS was where I spent most of my time. I had to look up flex and grid a few times to get things to line up.

**What decisions did you make when making your site mobile friendly?**

I added media queries at 768px and 480px. On smaller screens the navbar stacks vertically instead of staying in a row, and I made the text and padding smaller so everything fits. The Sudoku grid stretches to fill the width so it’s usable on phones. I also bumped up the padding at the top of the page on mobile since the navbar takes more vertical space when it stacks. The high scores table and feature cards stack on top of each other instead of sitting side by side.

**What did you take into account when developing the design? Anything you’re proud of?**

I wanted the colors to feel consistent, so I used a purple/blue gradient and a dark navbar for contrast. I kept the layout simple so it’s easy to read and navigate. I like how the Sudoku grid turned out with the thick borders around the sub-grids—it actually looks like a puzzle. The credits section on the Rules page and the custom scrollbar are small details I added to make it feel more polished.

**Given more time, what would you add?**

I’d add JavaScript to validate the Sudoku inputs (only 1-6 or 1-9), make the timer actually run, and maybe generate puzzles. The login and register pages would need a backend to do anything useful. Dark mode and keyboard shortcuts would be nice. And I’d improve accessibility so more people can use it easily.

**How many hours did you spend on this assignment?**

~12 hrs

**(Optional) Any assumptions?**

I assumed all the selection page games could link to the Hard Game page since that’s what the assignment said. I used fake data for credits, high scores, and authors. For the “no .html in URLs” thing, I used folder paths like `selection/` instead of `selection/index.html`, which should work on GitHub Pages.

**Sources / fonts / icons?**

No external libraries or frameworks. I used system fonts (Segoe UI, etc.) and made the logo as an SVG. 
