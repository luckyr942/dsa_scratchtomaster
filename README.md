# DSA Mastery Tracker - June Interview Prep

A fully interactive, browser-based Data Structures & Algorithms (DSA) preparation tracker designed for cracking software engineering internships and full-time roles in June 2026.

## Features

- **91 curated LeetCode problems** across 12 essential patterns
- **Full CRUD operations** — Create, Read, Update, Delete problems dynamically
- **Pattern-wise progress tracking** with visual progress rings
- **Difficulty filtering** — Easy, Medium, Hard
- **Status management** — To Do / In Progress / Solved / Needs Revision
- **Confidence rating** — 1-5 star rating per problem
- **Solved date tracking** — Auto-logs completion dates
- **Day streak counter** — Tracks consecutive solving days
- **Persistent local storage** — All data survives browser refreshes
- **Direct LeetCode links** — Open problems in one click
- **Confetti celebration** — Visual feedback on solving problems

## Problem Breakdown

| Pattern | Easy | Medium | Hard | Total |
|---|---|---|---|---|
| Arrays | 3 | 5 | 2 | 10 |
| Two Pointers | 2 | 3 | 1 | 6 |
| Sliding Window | 1 | 3 | 2 | 6 |
| Binary Search | 2 | 3 | 2 | 7 |
| Linked List | 3 | 3 | 1 | 8 |
| Stack | 2 | 3 | 2 | 7 |
| Trees | 3 | 4 | 2 | 10 |
| Graphs | 0 | 5 | 2 | 7 |
| Heap | 0 | 3 | 2 | 5 |
| Backtracking | 0 | 5 | 1 | 7 |
| DP | 1 | 7 | 3 | 12 |
| Intervals | 0 | 4 | 1 | 5 |
| **Total** | **17** | **48** | **21** | **91** |

## 5-Week Study Plan

### Week 1 (May 30 - Jun 5): Foundations
- **Patterns:** Arrays, Two Pointers, Sliding Window
- **Focus:** Build problem-reading speed, recognize patterns quickly
- **Daily target:** 2-3 problems, 20 minutes max per problem before checking hints

### Week 2 (Jun 6 - Jun 12): Core Structures
- **Patterns:** Binary Search, Linked List, Stack
- **Focus:** Edge cases, space optimization, pointer manipulation
- **Daily target:** 2 problems + 1 system design concept (evening)

### Week 3 (Jun 13 - Jun 19): Advanced Structures
- **Patterns:** Trees, Graphs
- **Focus:** DFS/BFS templates, tree traversals, topological sort
- **Daily target:** 2 problems + mock explain-out-loud sessions

### Week 4 (Jun 20 - Jun 26): Hard Patterns
- **Patterns:** Heap, Backtracking, DP
- **Focus:** Memoization patterns, state space reduction, pruning
- **Daily target:** 1-2 hard problems + revision of week 1-2 basics

### Week 5 (Jun 27 - Jun 30): Final Push
- **Patterns:** Intervals + Full Revision
- **Focus:** Mock interviews, timed sets, weak spot targeting
- **Daily target:** 1 LeetCode contest or timed 5-problem set

## How to Use

### 1. Open the Tracker
Simply open `dsa_mastery_tracker.html` in any modern web browser. No server or installation required.

### 2. Track Your Progress
- **Check off** problems as you solve them (click the checkbox)
- **Rate confidence** using 1-5 stars to identify weak spots
- **Add notes** with your approach, time/space complexity, key insights
- **Update status** — mark as "In Progress" while working, "Needs Revision" for tricky ones

### 3. Filter & Focus
- Use **topic filters** to drill specific patterns
- Use **difficulty filters** to tackle Easy first, then Medium, then Hard
- Click any **pattern progress ring** to filter to that pattern instantly

### 4. Add Custom Problems
Click **"Add Problem"** to add your own problems:
- Custom problem names
- Any pattern/topic
- Your own LeetCode or platform URLs
- Personal notes and confidence ratings

### 5. Edit or Remove
Hover any problem row to reveal:
- **Edit (pen icon)** — Modify name, pattern, difficulty, notes, status
- **Delete (trash icon)** — Remove problems you don't need
- **Open (link icon)** — Jump directly to LeetCode

## Data Persistence

All your progress is saved to the browser's `localStorage`. This means:
- Data survives page refreshes
- Data survives browser restarts
- Each browser maintains its own copy

**To backup/transfer data:** Use browser DevTools (Application/Storage tab) to export `localStorage` data.

## Keyboard Shortcuts

| Action | Shortcut |
|---|---|
| Add new problem | Click top-right "Add Problem" button |
| Toggle solved | Click checkbox on any problem |
| Filter by pattern | Click any pattern progress ring |
| Reset filters | Click "All" in filter bar |

## Tips for Maximum Effectiveness

1. **Don't go pattern-by-pattern initially** — Solve all Easy problems across all patterns first to build pattern recognition instinct
2. **20-minute rule** — Think for 20 minutes without looking at hints, then code, then compare with optimal
3. **Explain out loud** — After solving, explain your solution as if in an interview
4. **Track confidence honestly** — 1-star problems need revision; 5-star problems are interview-ready
5. **Review before bed** — Spend 10 minutes reviewing notes from solved problems

## Tech Stack

- **HTML5** — Semantic structure
- **Tailwind CSS** — Utility-first styling (loaded via CDN)
- **Vanilla JavaScript** — Zero dependencies, pure browser APIs
- **localStorage API** — Client-side persistence
- **Font Awesome** — Icons (loaded via CDN)

## Browser Compatibility

- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+

## License

Free for personal use. Built for the June 2026 interview grind.

---

**Good luck crushing those interviews!**
