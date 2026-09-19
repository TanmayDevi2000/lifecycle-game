# The Lifecycle Game

A browser reconstruction of the lifecycle board game fielded in summer 2026
with 855 women in Rajasthan and Haryana, for the paper *Son Preference and
Fertility Decisions* (Tanmay Devi, Rice University).

**Play it:** https://tanmaydevi2000.github.io/lifecycle-game/

Three rounds, a few minutes. You advise a fictional woman, Rekha, one year at
a time, from her starting age to 43.

## Privacy

Nothing you do here leaves your browser. No choices are submitted or stored on
a server, no analytics are loaded, and no personal details are asked for. The
only state kept is a single `sessionStorage` entry so a reload does not lose
your place; it is gone when the tab closes.

## About this repository

This holds the **built site only** — the compiled output that GitHub Pages
serves. The source project (React + TypeScript + Vite, with its unit tests,
end-to-end tests and the protocol crosswalk against the fielded SurveyCTO
form) lives with the paper's research files and is not published here.

To update the site: rebuild the source and replace the contents of this
repository with the new `dist/`.
