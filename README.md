# TypeMasterPro

Typing practice tool. Measures speed and accuracy. Built for programmers, students, and anyone who wants to type faster without looking at the keyboard.

## What It Does

Tracks typing speed in words per minute and accuracy percentage in real time. Shows detailed statistics after each session. Highlights recurring errors so you can target them in the next attempt.

## Features

- Real-time WPM counter.
- Accuracy percentage.
- Post-session statistics.
- Error heatmap.
- 14 practice texts, including programming-specific content and special character drills.
- Multiple language support.
- Historical performance graphs.
- Customizable difficulty levels.

## Stack

- JavaScript (ES6+), no frameworks
- CSS3 Grid and Flexbox
- HTML5 semantic markup
- Web Performance API
- Local storage for progress tracking

No backend. The entire application is client-side.

## Running Locally

Open index.html in a browser. No build step required.

## Live Demo

https://xm14.github.io/TypeMasterPro

## Notes

The practice texts are stored in a single file and can be extended without touching the application logic. The error heatmap is generated from a rolling window of the last ten sessions, not the full history. That keeps the visualization readable as the number of sessions grows.

Performance targets: 60 FPS animation, input latency under 100ms, total payload under 500KB. These are measured on a mid-range laptop with a wired keyboard.

## License

MIT. Use, modify, distribute.

## Contact

Email: martinrlab@gmail.com
I try to respond quickly.
