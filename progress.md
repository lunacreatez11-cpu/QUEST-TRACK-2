# Progress log

## week-01 · 2026-10-15
### What I made
- Reaction Speed Test · a one-page game: press Start, wait for a random "GO!", click as fast as you can. Has an early-click fail, a saved best time, an average, recent tries, and on-screen how-to steps. Space theme with a starfield and sparkle bursts · done (live on GitHub Pages: https://lunacreatez11-cpu.github.io/QUEST-TRACK-2/week-01/)
  [based on: the first request, the redesign request and the publish request]

### How I worked
- Sent 6 messages: 4 to build/open/change/publish, 1 question, 1 to wrap up.
- First request was a full feature list for one file (random GO!, early-click fail, high score, average, how-to steps). Last work request was a multi-step job in one message (commit, push, turn on Pages with gh on main/root, show the address in big letters, "you run every command").
  [based on: counting the messages in today's chat]
- Not stuck on anything myself. When I wasn't sure about something (whether I had installed GitHub), I asked.
  [based on: the "I did install github?" question]

### Style
- Wrote down what it must do first, got it working, then changed the look, then published. Each step was its own message.
  [based on: the order of the requests]

### Did well
- The first request named every feature clearly, so the game had all of them on the first build with 0 fixes.
- The publish request gave exact settings (branch, folder) and said what result to show at the end.
  [based on: the first and fourth requests; no fix requests were needed]

### Could be better
- After opening the page, play it and say what you saw (for example: "early click worked, GO! felt slow") before asking for the next change. Today the redesign was asked right after opening, with no report on how the game played.
  [based on: no test results were shared after the "open it" step or after publishing]

### Better than last time
- Nothing to compare yet

### New things I learned
- GitHub Pages turns a folder in the repo into a public web address (username.github.io/repo/folder/).
- GitHub CLI (gh) was already installed (Sept 30) and logged in. It lets Claude control GitHub from the computer, like turning on Pages.
- A web page can remember a best score in the browser even after closing it.
  [based on: what came up while building and publishing]

### Got stuck → how I fixed it
- The push failed because git couldn't log in to GitHub. Claude pushed using the gh login for that one command, and no settings were changed.
- "gh: command not found" at first: gh was installed but that shell couldn't find it. Claude found it in Program Files.
  [based on: errors during the publish step; both were fixed by Claude, no action needed from me]

### Try next class
- Open the live page and play 5–10 rounds. Share your best and average, plus one thing you'd change.
- Try a small upgrade from that feedback (for example a "rank" like 🐢/🐇/⚡ based on your time), and test it before publishing.
