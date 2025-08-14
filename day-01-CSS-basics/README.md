# Day 1 – CSS Basics 🎨

## 📌 What I Learned
### 1. What is CSS?
    CSS (Cascading Style Sheets) is used to style and format HTML pages, controlling things like:
    - Colors
    - Fonts
    - Layouts
    - Backgrounds
    - Spacing

---

## 🖌 Types of CSS

### **1. External CSS**
    - CSS code is stored in a **separate `.css` file**.
    - Linked to the HTML using the `<link>` tag inside `<head>`.
    - **Value:** 
    - Keeps code clean and organized.
    - Makes it easy to update multiple pages at once.
    - Reusable for many HTML files.

    **Example:**
    ```html
        <link rel="stylesheet" href="styles.css">

### **2. Internal CSS

    -CSS code is written inside a <style> tag in the HTML <head>.

    #Value:

    -Good for small projects or when styles are only for one page.
    -No need to create a separate file.

    #Example:
        <style>
        body {
            background-color: lightblue;
        }
        </style>

### **3. Inline CSS

    -CSS code is written directly inside an HTML element’s style attribute.

    #Value:

    -Quick changes without editing CSS files.

    -Useful for testing or overriding styles quickly.

    -Limitation: Not good for large projects; harder to maintain.

    #Example:
        <p style="color: red;">This is red text</p>

🛠 Files Included

    -index.html – HTML file with examples of inline and internal CSS.

    -styles.css – External CSS file that styles the page’s main appearance