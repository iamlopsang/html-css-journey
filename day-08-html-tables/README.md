Day 8- HTML TABLES

📝 What I Learned:

    -How to create a table using thr <table> tag
    -The usage of table rows <tr>, table headers <th>, and table data <td>
    -How to group table headers, body, and footer using <thead>, <tbody>, and <tfoot>
    -How to add borders, cell padding, and spacing for better readability
    -How to merge cells using rowspan and colspan.
    -The importance of adding captions with <caption> for accessibility

💡 Notes:
    - Tables help in organizing data in a structured, grid-like format.
    - Using semantic tags like <thead> and <caption> makes tables more accessible for screen readers.

### Sample `<tfoot>` usage

```html
<tfoot>
    <tr>
        <!-- colspan merges two cells for the "Total Students" label -->
        <td colspan="2"><strong>Total Students</strong></td>
        <!-- Total count displayed in the last column -->
        <td>45</td>
    </tr>
</tfoot>

📁 Project Files:
day-08-html-tables/
├── index.html
└── README.md