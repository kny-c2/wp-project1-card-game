# Blackjack Hub

A beginner's guide to Blackjack, built with **HTML and CSS only**. 

**CSC 4370 Web Programming, Project 1**
Topic track: **Card Gaming Hub** + Extension pack: **Strategy Table Pack**


Live site (CODD): 

---

## Team

| Member | Role | Responsibilities |
|---|---|---|
| Kenny Cao | Project Leader | Shared stylesheet (`css/style.css`), Home page, Table page, Kanban board, development journal, presentation deck, submission |
| Billy Haboon | Team Member | Lobby page, Rules page |
---

## Setup: how to view the site

**Option 1: live site.** Open the CODD link above

**Option 2: run it locally.**
1. Clone the repo:
   ```
   git clone https://github.com/kny-c2/wp-project1-card-game
   ```
2. Open the folder and double-click `index.html`, or right-click it and choose Open With Chrome.

There's nothing to install or build. The site is plain HTML and CSS.

---

## Folder structure

```
├── index.html        Home: what Blackjack is, plus links to every section
├── lobby.html        Lobby
├── table.html        Table: a static Blackjack table with flip cards and a deck
├── rules.html        Rules
├── style.css         Stylesheet every page links to
└── README.md
```

## AI assistance disclosure
We used an AI assistant (Claude) during this project. It helped with:
- Explaining CSS concepts (Grid areas, 3D transforms for the card flip, `perspective`, `backdrop-filter`, custom properties)
- Debugging the card-height bug (a flex row stretching its items, fixed with `align-items: flex-start`)
- Drafting the presentation slide structure
