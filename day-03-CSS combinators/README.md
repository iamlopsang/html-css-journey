# Day 3 – CSS Combinators 🔗

## 📚 What I Learned
    - A **combinator** defines the relationship between two selectors.
    - There are 4 types of combinators:
        1. **Descendant (space)** – selects all elements inside another.
        2. **Child (>)** – selects only direct children.
        3. **Adjacent sibling (+)** – selects the element immediately after another.
        4. **General sibling (~)** – selects all siblings after another element.

## 🖼 Examples
    - `.parent p {}` → styles all paragraphs inside `.parent`.
    - `.parent > span {}` → styles only direct child spans inside `.parent`.
    - `h2 + p {}` → styles the paragraph immediately after an h2.
    - `h3 ~ p {}` → styles all paragraphs after an h3.

## 📂 Files
    - `index.html` – HTML with nested elements for testing combinators.
    - `styles.css` – CSS rules demonstrating all four combinators.

