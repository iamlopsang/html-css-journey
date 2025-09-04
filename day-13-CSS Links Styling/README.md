# Day 13 – Part 1: Links Styling 🔗

## 📖 What I Learned
    - How to style (HTML links) using CSS.
    - The **four link states**:
        == `a:link` → default state of a link.
        == `a:visited` → after a link has been clicked before.
        == `a:hover` → when the mouse pointer is placed over the link.
        == `a:active` → the moment the link is clicked.
    - How to use CSS properties with links:
        == `color`, `text-decoration`, `transform`, `transition`.

## 🧑‍💻 Practice Work
    - Created a simple webpage with multiple links.
    - Applied (different colors and effects) for each link state.
    - Used `transform: scale()` to make hover and active states interactive.
    - Added smooth animations using `transition`.

## 🎯 Key Takeaways
    - Links are not just plain text – styling them improves (usability) and (user experience).
    - Hover and active effects make links (feel interactive).
    - Always follow the (correct hierarchy order) for link states.

## 📌 Importance of Link Styling Hierarchy
    - The order of link state rules matters in CSS:
        1.`:link`
        2.`:visited`
        3.`:hover`
        4.`:active`

## This order is remembered as {LVHA (LoVe HAte)}:

    - `:hover` must come (after) `:link` and `:visited`, otherwise the hover effect may be overridden.
    - `:active` must come (after) `:hover`, otherwise you won’t see the active effect when clicking.
