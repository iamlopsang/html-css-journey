# Day 7 – HTML Forms: Input Types and Attributes 📝

## 📝 What I Learned:
    -How to create an HTML form using the '<form>' element
    -Different input types: text, number, email, date, password, file
    -Use of 'min', 'max', 'placeholder', 'required', 'pattern' attributes for validation and guidance
    -How to create radio buttons for selecting one option using '<input type="radio">'
    - How to create checkboxes for selecting multiple options using `<input type="checkbox">`
    -How to create a dropdown select menu using '<select>' and '<option>'
    -Using 'fieldset' and 'legend' to group related form controls for better accessibility
    --Adding a textarea for multiline user input
    -How to create a submit button to send form data

## 💡 Notes:
    - Radio buttons allow the user to select only one option within the group — one can be set as default by adding the `checked` attribute.
    - Checkboxes allow multiple selections — any number can be checked by default with `checked`.   
    - The dropdown `<select>` menu can have a default selected option using the `selected` attribute on an `<option>`.
    - Proper use of labels (`<label>`) with `for` attributes improves form usability and accessibility.
    - Password field uses a regex pattern for basic validation (letters and numbers, minimum 8 characters).

## 🧩 Sample Code:

```html
<form action="" method="post">
  <label for="name">Full Name:</label>
  <input type="text" id="name" name="name" required>
  
  <fieldset>
    <legend>Gender:</legend>
    <label><input type="radio" name="gender" value="male" checked> Male</label>
    <label><input type="radio" name="gender" value="female"> Female</label>
  </fieldset>
  
  <button type="submit">Submit</button>
</form>


## 📁 Project Files:
day-07-html-forms-inputs/
├── index.html
└── README.md