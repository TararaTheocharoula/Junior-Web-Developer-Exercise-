# 🌟 Number Input Validation

This project demonstrates a simple web-based form with number input validation. It ensures that users enter a number greater than 10 before the form can be successfully submitted.

## ✨ Features

- **📝 HTML Form**: A structured form to input numbers.
- **✅ Validation**: Real-time validation using JavaScript to ensure that the entered number is greater than 10.
- **⚠️ Error Messaging**: User-friendly error messages for invalid inputs.
- **📱 Responsive Design**: A responsive layout supported by an external CSS stylesheet.

---

## 📂 File Structure

```
project-directory/
│
├── index.html   # Main HTML file containing the structure of the form
├── styles.css   # CSS file for styling the form and layout
└── script.js    # JavaScript file for input validation logic
```

### 📄 index.html
Contains the structure of the web page, including the form and input fields.

### 🎨 styles.css
Defines the styles for the page, including the layout, fonts, and error message display.

### 💻 script.js
Includes JavaScript logic to validate the input and display appropriate error messages if the input does not meet the requirements.

---

## 🚀 How to Run

1. Clone or download this repository.
2. Ensure that the following files are in the same directory:
   - `index.html`
   - `styles.css`
   - `script.js`
3. Open the `index.html` file in a web browser to view the form.
4. Enter a number in the input field and click **Submit**.
   - If the number is greater than 10, the form will submit successfully.
   - If the number is 10 or less, an error message will be displayed below the input field.

---

## 🛠️ Validation Logic

The JavaScript file includes an event listener for the form's `submit` event. It checks the following conditions:

1. If the input is empty or not a valid number, an error message is displayed.
2. If the input is less than or equal to 10, an error message is displayed.
3. If the input is valid and greater than 10, the form submits without errors.

---

## 🎨 Customization

To customize this project:

- **🎨 Styling**: Modify `styles.css` to change the appearance of the form.
- **🔧 Validation Rules**: Update the validation logic in `script.js` for different input requirements.
- **➕ Additional Fields**: Add new input fields in `index.html` and update the validation logic as needed.

---

## 💡 Example Use Case

This project can be used as a starter template for web applications requiring basic input validation. For example:

- 🛠️ User registration forms.
- 🗳️ Feedback or survey forms.
- 📊 Data entry portals.

---

## 🛠️ Technologies Used

- **🌐 HTML**: For structuring the web page.
- **🎨 CSS**: For styling the layout and elements.
- **⚙️ JavaScript**: For input validation and interactivity.

---