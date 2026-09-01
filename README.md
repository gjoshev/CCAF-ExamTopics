# CCA-F Quiz

Lightweight TypeScript + React + Vite app containing all 134 questions extracted from the supplied PDF.

- Click A/B/C/D to answer; selected correct answers are green, incorrect answers red.
- Correct answers are hidden until “Show correct answer” is clicked.
- Live score, progress, previous/next navigation and reset.
- Passing score: 720, requiring 42 correct under the supplied scale.
- Score uses `min(1000, 100 + (Correct / 60) * 900)`.

Run with `npm install` then `npm run dev`.
