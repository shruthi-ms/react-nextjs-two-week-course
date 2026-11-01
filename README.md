# React & Next.js — A Two-Week Foundations Course

Learn React 19 and Next.js 16 in 14 days, from first principles to interview-ready. The whole course is one HTML file: no install, no build step, and it works offline.

Each day explains the mental model first, then the syntax, then a hands-on lab, then interview questions to check that the idea stuck.

## Getting started

**Read it locally**

1. Download or clone this repository.
2. Open `index.html` in any modern browser.

**Read it online**

If GitHub Pages is enabled for this repository, the course is at:

```
https://shruthi-ms.github.io/react-nextjs-two-week-course/
```

To enable it: **Settings → Pages → Build and deployment → Deploy from a branch**, choose `main` and `/ (root)`, then save.

## What each day contains

- **Outcomes:** what you will be able to do by the end of the day.
- **Concepts in plain language:** everyday analogies, such as closures as a backpack, the Rules of Hooks as numbered lockers, and Server Actions as a pneumatic tube.
- **Memory hooks:** one-liners worth putting on flash cards, such as *UI = f(state)* and *keys are name tags, not seat numbers*.
- **Common traps and jargon busters:** frequent mistakes and technical terms explained simply.
- **A hands-on lab:** the solution is hidden until you click to reveal it.
- **Interview corner:** questions with model answers.
- **References:** links to the official React and Next.js documentation.

## Syllabus

| Day | Topic | You build |
|---|---|---|
| 0 | Tooling setup | Node, editor and browser tools |
| 1 | Modern JavaScript for React | A data-transformation drill |
| 2 | Thinking in React: JSX, components, purity | A static profile card |
| 3 | Props, children, conditionals, lists and keys | A product catalogue |
| 4 | State, events, immutability, forms | A todo app |
| 5 | The render cycle and `useEffect` | A user directory with live search |
| 6 | `useRef`, `useReducer`, Context, custom hooks | A shopping cart |
| 7 | Performance, error boundaries, React 19 Actions | **Project:** Expense Tracker |
| 8 | Rendering strategies and the App Router | A blog skeleton |
| 9 | Server Components vs Client Components | A product detail page |
| 10 | Data fetching, streaming, caching (`'use cache'`) | A streaming dashboard |
| 11 | Server Actions, forms, Route Handlers | A guestbook with an API |
| 12 | `proxy.ts`, authentication, metadata, optimisation | A protected dashboard |
| 13 | Styling, accessibility, testing, deployment | Tests and a production build |
| 14 | Capstone and interview readiness | **Capstone:** "Shelf", a full-stack book app |

**Appendices:** a jargon dictionary, a 30-question rapid-fire bank, cheat sheets (hooks, where state should live, server vs client, caching decisions) and a reading list.

## Features of the page

- Classic, low-colour layout designed for long reading sessions.
- Sidebar navigation that highlights the section you are reading.
- Progress tracking: tick each day as complete, and your browser remembers it (stored in `localStorage`).
- A Copy button on every code block.
- Works on mobile, and prints cleanly.

## Prerequisites

- Basic HTML and CSS.
- Some JavaScript (variables, functions, loops). Day 1 covers the parts React relies on.
- Node.js 20.9 or newer for the labs.

Plan for 3 to 4 focused hours a day. Days 7 and 14 are project days and take longer.

## Versions

The course targets **React 19.x** and **Next.js 16.x** (written October 2026). Next.js caching and some API names have changed between major versions, and the course points out where they differ. If the course and the official documentation disagree, follow the documentation for the version you have installed.

## Contributing

Corrections and improvements are welcome. Please open an issue or a pull request, and mention the React or Next.js version you tested against.

## License

Released under the [MIT License](LICENSE).
