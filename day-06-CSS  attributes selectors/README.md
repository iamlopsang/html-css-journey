
📘 README – Day 6 (CSS Attribute Selectors)
    ##Day 6 – CSS Attribute Selectors 🎯

📝 What I Learned

    -Attribute selectors allow me to style elements based on their attributes and values.

    -They are useful when I don’t want to add extra classes or IDs.

    -Attribute selectors make CSS more flexible and powerful.

💻 Code Examples
1. Basic Attribute Selector

    p[lang] {
        color: red;
        background-color: lightgray;
    }

        -Styles all <p> elements that have a lang attribute.

2. Exact Match

    button[type="submit"] {
        background-color: green;
    }

        -Styles only buttons with type="submit".

3. Word Match (~=)

    input[value~="this"] {
        background-color: red;
    }

    -Styles inputs whose value contains the word "this".

4. Starts With (^=)

    a[href^="www"] {
         background-color: green;
    }

        -Styles all links starting with "www".

5. Ends With ($=)

    a[href$=".np"] {
        background-color: purple;
    }

    -Styles links ending with .np.

6. Substring Match (*=)

    h2[title*="cond"] {
         background-color: blue;
    }

    -Styles <h2> with title containing "cond".

7. Dash Match (|=)

    p[lang|="en"] {
         background-color: violet;
    }

        -Styles <p> where lang is "en" or starts with "en-" (like en-USA).

🎯 Output Highlights

    -Buttons styled differently depending on their type (button, submit, reset).

    -Links styled based on whether they start with, end with, or contain certain text.

    -Headings and paragraphs styled based on their attributes.
