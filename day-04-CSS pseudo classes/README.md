# Day 4 – CSS Pseudo-classes 🎭

## 📚 What I Practiced

    - Learned how **pseudo-classes** allow styling elements in **special states**.
    - Covered three main areas:

        1. **Link states** → `:link`, `:visited`, `:hover`, `:active`

        2. **Structural states** → `:first-child`, `:last-child`, `:nth-child(n)`, `:not()`

        3. **User interaction / Form states** → `:hover`, `:checked`, `:disabled`

## 🖼 Examples from this project

    - `a:link { color: blue; }` → styles default link

    - `a:hover { color: dark red; font-size: 1.1em; }` → enlarges when hovered

    - `li:first-child { color: blue; }` → first list item styled differently

    - `li:nth-child(3n) { color: red; }` → every 3rd list item is red

    - `button:hover { background: cyan; }` → button changes on hover

    - `input:checked { background: green; }` → checkbox changes when checked

    - `input:disabled { background: red; }` → disabled input styled red

## ✅ Outcome
    - Practiced **interactive link styling**
    - Learned how to style **specific list items**  
    - Explored **form states** (checked/disabled)
    - Added **hover effects** for better UI experience

## 📂 Files
    - `index.html` → HTML with links, list, button, and form
    - `styles.css` → CSS using pseudo-classes
