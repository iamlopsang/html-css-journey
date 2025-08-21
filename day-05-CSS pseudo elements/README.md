Day 5 – CSS Pseudo Elements ✨
📝 What I Learned

    CSS pseudo-elements let us style specific parts of an element without adding extra HTML.

## Common pseudo-elements:

    -::first-letter → styles the first letter of a block.

    -::first-line → styles the first line of a paragraph.

    -::selection → styles highlighted/selected text.

    -::before and ::after → insert content before/after elements.

## Code Examples
    - Styling text parts

     h2::first-letter {
            font-size: 2em;
            color: rgba(0, 183, 255, 0.918);
    }

    p::first-line {
        font-weight: bold;
        color: rgba(179, 14, 194, 0.945);
    }

    p::selection {
        background-color: rgba(255, 0, 0, 0.5);
        color: white;       
    }   


    - Adding extra content with ::before and ::after

    .one::before {
    content: "✔ ";
    }
    .one::after {
        content: " 🍎";
    }

    .two::before {
        content: "✔ ";
    }
    .two::after {
        content: " 🍊";
    }


🎯 Output Preview

    -The first letter of the heading is bigger and colored.

    -The first line of the paragraph is bold and purple.

    -Selected text changes background and font color.

    -A check mark ✔ appears before each list item, and a fruit emoji 🍎 🍊 🍉 appears after them.
