# Day 6 – HTML Forms: Basic Input

## ✅ What I Learned

    -How to create an HTML form using the '<form>' tag.
    -How to use '<label>' for describing input fields.
    -How to create text, email, and password input fields.
    -How to add placeholders and 'required' attributes.
    -How to create a submit button.

## 🛠 HTML Concepts Used

    -'<form>' with 'action' and 'method' attributes.
    -'<label>' with 'for' attribute to link labels and inputs.
    -'<input>' types: 'text', 'email', and 'password'.
    -'placeholder' for hint text inside inputs.
    -'required' attribute for basic validation.
    -'<button>' to submit the form.

 ## 📌 Example
 
```html
<form action="" method="post">
  <label for="name">Name:</label>
  <input type="text" id="name" name="name" placeholder="Peter Parker" required>
  
  <label for="email">Email:</label>
  <input type="email" id="email" name="email" placeholder="peter@gmail.com" required>
  
  <label for="password">Password:</label>
  <input type="password" id="password" name="password" placeholder="********" required>
  
  <button type="submit">Submit</button>
</form>

## 📁 Project Files:

day-06-html-forms-basic-input/
├── index.html
└── README.md