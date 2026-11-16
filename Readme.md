# Taskflow

Taskflow helps you stay focused while studying by keeping tasks and a timer together. Plan what you need to do, track your work sessions, and see what’s next without losing focus.

## Features

- **Tasks:** add, complete, edit (pencil button or double-click the text), delete, and clear all completed tasks at once. New tasks go to the top, and finished tasks move to the end of the list so unfinished work stays in view.
- **Timer per task:** choose a length from 1 to 1440 minutes when you add a task. You can pause, resume, or reset it. Timers keep correct time across page reloads and in background tabs.
- **Progress bar:** a bar along the top of each task shrinks as time runs out. It shifts from green to red as the deadline gets close and pulses red when time is up.
- **Countdown in the browser tab:** the tab title shows the timer that will finish soonest, e.g. `⏱ 24:13 · Read chapter 3`, so you can keep an eye on it from other tabs. When a timer runs out, it shows `⏰ Time's up`.
- **Time's-up alerts:** a short chime plays and, if you allow it, a system notification appears.
- **Light and dark themes:** the theme follows your system setting until you pick one with the toggle.
- **Saved in your browser:** tasks and your theme choice are stored in `localStorage`. If the browser blocks storage, a warning tells you changes won't be kept.

## Getting started

Open `index.html` in any modern browser. There's nothing to install and no build step.

Because data is stored locally in your browser, your tasks remain available when you return on the same device and browser. No account is needed; clearing browser storage will remove saved tasks.
