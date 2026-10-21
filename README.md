# Little Time Travelers

A simple, child-friendly clock for learning to tell time and exploring how far apart two times are.

**[Open the clock app](https://sword0628.github.io/little-time-travelers/)**

## Move the clock

- Drag the **blue minute hand** to move in one-minute steps. Passing 12 carries the hour forward or backward.
- Drag the **red hour hand** to move in whole-hour steps while keeping the minutes.
- Type directly into the digital clock below the analog face. Both displays stay in sync.
- With a hand selected using Tab, use the arrow keys to move it.

The clock uses a 12-hour cycle without AM/PM. On a touchscreen, drag a hand with your finger.

## Learn

Enter **hours** and **minutes**, then choose **Earlier** or **Later**.

For example, starting at **4:45**, choose **1 hour, 40 minutes** and press **Later**:

1. Reach the next friendly hour: **4:45 → 5:00** (+15 minutes)
2. Hop whole hours: **5:00 → 6:00** (+1 hour)
3. Finish with the remaining minutes: **6:00 → 6:25** (+25 minutes)

The hops add up to **1 hour 40 minutes**. Earlier follows the same method backward, reaching the previous friendly hour first.

Set hours to **0** for minutes-only practice, or minutes to **0** for hours-only practice. Hours accept **0–12** and minutes accept **0–59**; the total must be greater than zero.

## See the hops

After an Earlier/Later move, switch between two views:

- **Number line:** labeled arrows connect the times. Later moves right; Earlier moves left. Arc spacing is for readability, not to scale.
- **T-chart:** two columns show each hop and the time it reaches.

Tap a hop in either view to move the analog and digital clocks to that step. The selected step stays highlighted when switching views. The sum underneath adds all hop lengths to show the total time.

Minute hops are blue; whole-hour hops are red, matching the clock hands. Both views support keyboard selection.

## Practice

Choose the **Practice** tab for a question that crosses an hour boundary.

- Move the hands or type the answer, then press **Check**.
- A correct answer earns a brief congratulations popup and confetti. It closes automatically; you can also dismiss it with × or Escape. Reduced-motion settings keep the message and skip the confetti.
- Press **Hint** to see only the first hop to the hour boundary, using either teaching view.
- After a correct answer, explore the complete journey in either view.
- **Reset** returns the clock to the question's starting time.
- **Next** gives another question.

Practice questions currently use minute durations. Combined hours and minutes are available in Learn.

## Run locally

Download `index.html` and open it in a modern browser. It works offline without installation or a build step.

All HTML, styling, and JavaScript are contained in that one file. There is no backend, account system, or external dependency.

## Hosting and updates

The app is hosted with GitHub Pages using **main → / (root)**.

Changes committed to `index.html` on `main` are published automatically by GitHub Pages. Wait for the **pages build and deployment** workflow to finish, then refresh the website.
