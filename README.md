# Spears Family Tree

A shared, interactive family tree for the Spears Family Reunion. Built to be viewed on any device and printed on canvas.

## Live Site

[https://phoenixkey87-cmyk.github.io/spears-family-tree/](https://phoenixkey87-cmyk.github.io/spears-family-tree/)

## How It Works

- **View the tree** — Open the link on any device (phone, tablet, or computer)
- **Click a name** — A popup appears with options to:
  - **Add a child** (son, daughter, grandson, granddaughter) under that person
  - **Edit** the name
  - **Delete** the name from the tree
- **Type in blank fields** — Fill in names in the write-in sections
- **Auto-saves** — All changes sync to Firebase in real-time so everyone sees the same tree
- **"Saved" indicator** — A small toast appears in the bottom-right corner when data is saved

## Family Coverage

The tree traces from our deepest roots in Africa through Liberty, Mississippi:

- **Unknown from Africa** > Admiral Spears > Winter Spears > **Mingo Spears & Priscilla Joyner Chandler**
- All 11 children of Mingo & Priscilla
- **Charlie "Charley" Boatner Spears Branch** — 16 children with Mattie Walls and Bertha Avery, plus grandchildren and great-grandchildren
- **Mingo Spears Sr. & Mary Maxwell Branch** — Matthew, Earl, Eddie, Mingo Jr., Allen, Rosetta, Etta, Hettie, Lena
- **Next Generations** — blank write-in sections for family to add themselves

## For the Canvas Print

When ready to print on large canvas:
1. Open the HTML file
2. Change the CSS `@page` size and `body` max-width to your canvas dimensions (e.g., 36in x 48in)
3. Print to PDF or directly to a large-format printer

## Tech Stack

- Single HTML file (no build tools needed)
- Firebase Realtime Database for shared data
- Responsive CSS grid layout
- Vanilla JavaScript

## Contributing

Family members can add names directly on the live site. For structural changes (new sections, layout updates), edit `index.html` and push to this repo.
