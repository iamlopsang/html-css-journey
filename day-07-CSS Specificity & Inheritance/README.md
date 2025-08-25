# Day 7 – CSS Specificity & Inheritance 🎯

## 📝 What I Learned:
    - **Specificity** is how browsers decide which CSS rule to apply when there are multiple matches.
    - **Inheritance** means some properties (like `color`, `font-family`) are passed down from parent to child elements.

        - CSS rules are applied in the following order of priority:

            1. Inline styles (inside the element) → highest priority
            2. ID selectors (`#id`)
            3. Class selectors (`.class`), attribute selectors (`[attr]`), and pseudo-classes (`:hover`)
            4. Element selectors (`p`, `div`, `h1`, etc.)
    - The `!important` keyword overrides all normal rules (but should be avoided unless necessary).

## 📊 Specificity Calculation:
    #-Specificity is calculated as a **4-part value (a-b-c-d)**:

    - a → Inline styles (`style=""`)
    - b → IDs (`#id`)
    - c → Classes, attributes, pseudo-classes
    - d → Elements and pseudo-elements

| Selector          | Specificity Value | Explanation |
|-------------------|------------------|-------------|
| `p`               | 0-0-0-1          | Element selector |
| `.highlight`      | 0-0-1-0          | Class selector |
| `.container p`    | 0-0-1-1          | Class + element |
| `#unique`         | 0-1-0-0          | ID selector |
| Inline style      | 1-0-0-0          | Directly inside element |
| `#unique !important` | Overrides all | Special rule |

## 📂 Example Files:

    - `index.html` → Demonstrates specificity conflicts and inheritance
    - `styles.css` → External CSS with rules for `p`, `.highlight`, `.container p`, and `#unique`

## 💡 Key Takeaways:
    - If two rules have the (same specificity), the (last one written) is applied.
    - IDs are stronger than classes, which are stronger than elements.
    - Use (!important sparingly) (only when you really need to force override).
    - Always try to write (clean, maintainable CSS) instead of relying on `!important`.

---

✅ This example showed:
    - Element, Class, ID, and Descendant selectors  
    - Inheritance from parent (`.container`) to children  
    - Conflict resolution between multiple selectors  
    - Use of `!important` to override all rules  

