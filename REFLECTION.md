REFLECTION

1. **What part of the code was most confusing and why?**
The most confusing part of the code was understanding how setInterval works in the background. It was confusing at first to see how the animation kept updating without a for or while loop. After breaking it down, I understood that setInterval keeps running the same code on a timer until clearInterval stops it.

2. **How does the animation help visualize asynchronous behavior?**
The animation helps visualize asynchronous behavior by updating the screen over time while the rest of the page remains responsive. The symbols and status message change every few milliseconds using setInterval, which shows that the code runs in the background rather than waiting for each task to complete.

3. **What did you change or improve, and what effect did it have?**
I added a feature that updates the status message while the animation is running. The message changes to “Almost done…” halfway through the animation before it finishes. This improvement makes the loading process clearer to the user and shows that JavaScript can update what you see on the page while the program is running, instead of everything happening at once or needing a refresh.