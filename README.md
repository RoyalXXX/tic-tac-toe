# tic-tac-toe

A lightweight Tic-Tac-Toe game written in C++ using WinAPI and GDI+.

Despite its small size of just 72 KB, the game offers flexible board configurations, customizable win conditions, and detailed engine search statistics.

<img width="802" height="530" alt="scr" src="https://github.com/user-attachments/assets/7c654aee-7e80-40d2-94b9-a08f7e262190" />

## Features

- **Flexible board size:** Choose any board size from `3×3` to `11×11`.
- **Custom win condition:** Set the number of consecutive marks required to win.
- **Selectable starting player:** Choose who makes the first move.
- **Configurable engine time limit:** Set the maximum thinking time per move in milliseconds.
- **Detailed engine statistics:** After each engine move, the following information is displayed:
  - **Position evaluation** — the engine's assessment of the current position.
  - **Search depth** — the depth reached during the search.
  - **Nodes searched** — the number of nodes evaluated.
  - **Thinking time** — the time spent calculating the move.

## Technical Details

| Property | Value |
| --- | --- |
| Language | C++ |
| API | WinAPI |
| Graphics | GDI+ |
| Application size | 72 KB |
| Operating system | Windows 10 (64-bit) or later |
| Display support | High DPI |
