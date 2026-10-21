# Little Time Travelers

A simple, child-friendly clock for learning to tell time and exploring how far apart two times are.

**[Open the clock app](https://sword0628.github.io/little-time-travelers/)**

## Move the clock

- Drag the **blue minute hand** to move in one-minute steps. Passing 12 carries the hour forward or backward.
- Drag the **red hour hand** to move in whole-hour steps while keeping the minutes.
- Type directly into the digital clock below the analog face. Both displays stay in sync.
- With a hand selected using Tab, use the arrow keys to move it.

The clock uses a 12-hour cycle without AM/PM. On a touchscreen, drag a hand with your finger.

## Play

Enter **hours** and **minutes**, then choose **Earlier** or **Later**.

For example, starting at **2:40**, choose **1 hour, 40 minutes** and press **Later**:

1. Add 1 hour: **2:40 → 3:40**
2. Add 20 minutes to reach the next hour: **3:40 → 4:00**
3. Add the remaining 20 minutes: **4:00 → 4:20**

The app shows these hops below the controls. Earlier works in the same way, moving backward.

Set hours to **0** for minutes-only practice, or minutes to **0** for hours-only practice. Hours accept **0–12** and minutes accept **0–59**; the total must be greater than zero.

## Practice

Choose the **Practice** tab for a question that crosses an hour boundary.

- Move the hands or type the answer, then press **Check**.
- Press **Hint** for help reaching the hour boundary.
- **Reset** returns the clock to the question's starting time.
- **Next** gives another question.

Practice questions currently use minute durations. Combined hours and minutes are available in Play.

## Run locally

Download `index.html` and open it in a modern browser. It works offline without installation or a build step.

All HTML, styling, and JavaScript are contained in that one file. There is no backend, account system, or external dependency.

## Hosting and updates

The app is hosted with GitHub Pages using **main → / (root)**.

Changes committed to `index.html` on `main` are published automatically by GitHub Pages. Wait for the **pages build and deployment** workflow to finish, then refresh the website.
