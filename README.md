# **Survey Form** 
#### learned it from [freeCodeCamp](https://www.freecodecamp.org/) || See it Live at [CodePen](https://codepen.io/shady-ashraf/pen/VwoOZNM)
###### This is one of the required projects to earn your certification. For this project, you will build a survey form to collect data from your users.
---
### **Overview**
The **Survey Form Project** is a simple web-based form designed to collect user feedback. It demonstrates the use of HTML for structuring forms and CSS for styling them, with an emphasis on accessibility, usability, and clean design.

---

### **Table of Contents**
1. [Project Structure](#project-structure)
2. [HTML Details](#html-details)
3. [CSS Details](#css-details)
4. [How to Use](#how-to-use)
5. [Summary of Selectors Used](#Summary-of-Selectors-Used)

---

### **Project Structure**
The project consists of two main files:
- `index.html`: Contains the structure and content of the survey form.
- `styles.css`: Defines the styles and layout for the form elements.

File structure:
```
/
├── index.html
├── styles.css
```

---

### **HTML Details**
The `index.html` file provides the foundation of the survey form, including:

1. **Title and Description:**
   - The `<h1>` element serves as the form's title.
   - The `<p>` element under the title contains a brief description.

2. **Form Structure:**
   - The form is wrapped in a `<form>` element with an ID of `#survey-form`.
   - It includes multiple question types such as text fields, dropdown menus, radio buttons, and checkboxes.

3. **Key Form Elements:**
   - `<label>` tags are used for accessible labeling of inputs.
   - `<input>` fields for name, email, age, and other data.
   - `<select>` dropdowns for role and favorite feature.
   - `<textarea>` for additional comments.
   - `<button>` for form submission.

Example:
```html
<form id="survey-form">
  <label for="name">Name:</label>
  <input id="name" type="text" placeholder="Enter your name" required>
</form>
```

---

### **CSS Details**
The `styles.css` file provides the styling for a clean and responsive form. Key details include:

#### General Styles:
- **Typography:** Consistent font-family and font-size for readability.
- **Layout:** The form is centered on the page using margin and padding.
- **Focus Effects:** Highlight inputs on focus with a subtle box shadow.

#### Specific Styles:
1. **Form Elements:**
   - Inputs, dropdowns, and textarea are styled with consistent padding, borders, and widths.
   - Labels are aligned with inputs for clarity.

2. **Submit Button:**
   - The button has a distinct background color, padding, and hover effect.
   - It is styled to match the overall theme of the form.

Example:
```css
#submit {
  background-color: #4CAF50;
  color: white;
  padding: 10px 20px;
  border: none;
  cursor: pointer;
}
#submit:hover {
  background-color: #45a049;
}
```

---

### **How to Use**
1. **Clone the Project:**
   ```bash
   git clone https://github.com/shadyashraf174/Survey-Form-Certification-Project
   cd Survey-Form-Certification-Project
   ```

2. **Open the Project:**
   Open `index.html` in your preferred browser to view the survey form.

3. **Customization:**
   - Edit the `index.html` file to add or remove form fields.
   - Modify the `styles.css` file to change colors, fonts, or layout.

---

### **Summary of Selectors Used**


### **HTML Structure (Relevant Classes and IDs)**

#### **Tag Selectors**
- `<h1>`: Title of the survey form.
- `<p>`: Descriptions and prompts for form questions.
- `<label>`: Labels associated with form inputs.
- `<input>`: Text fields, radio buttons, checkboxes, and number inputs.
- `<select>`: Dropdown menus.
- `<textarea>`: Text area for additional comments.
- `<button>`: Submit button.

#### **ID Selectors**
- `#title`: ID for the main heading.
- `#description`: ID for the form description.
- `#name-label`: Label for the name input.
- `#email-label`: Label for the email input.
- `#number-label`: Label for the age input.
- `#survey-form`: ID for the entire form.
- `#dropdown`: Dropdown for current role selection.
- `#most-like`: Dropdown for favorite feature selection.
- `#comments`: Textarea for additional feedback.
- `#submit`: Submit button ID.

#### **Class Selectors**
- `.form-group`: Wrapper for each form question.
- `.form-control`: Common styles for form inputs, dropdowns, and textarea.
- `.input-radio`: Radio buttons.
- `.input-checkbox`: Checkboxes.
- `.input-textarea`: Text area styling.
- `.submit-button`: Submit button styles.
- `.clue`: Helper text or optional hints.

---

### **CSS Selectors Used**

#### **1. Tag Selectors**
- `h1`: Styles the survey title (e.g., center alignment, font size).
- `p`: General styling for paragraphs, such as font size and margin.
- `form`: Styles the entire form container with padding and background color.
- `input`, `button`, `select`, `textarea`: Ensures consistent font and spacing across form elements.

#### **2. ID Selectors**
- `#title`: Customizes the survey title (font size and weight).
- `#description`: Italicized description text below the title.
- `#submit`: Styles the submit button for width and background color.

#### **3. Class Selectors**
- `.form-group`: Adds padding and spacing between form questions.
- `.form-control`: Styles inputs and dropdowns with consistent size, padding, and borders.
- `.input-radio, .input-checkbox`: Applies minimum size and spacing for selection inputs.
- `.input-textarea`: Customizes the text area dimensions and resizability.
- `.submit-button`: Defines button appearance with padding, background, and hover effects.

---

### **Combined Selectors and Properties**

#### **General Form Layout**
- `input:focus, .form-control:focus`: Adds focus effects with border highlights and shadow for active form elements.

#### **Form Specificity**
- `.form-group .clue`: Ensures helper text is styled distinctly within form questions.
- `form .submit-button`: Applies button styles specific to the form context.

#### **Optional Features**
- `.clue`:
  - Font size: `0.9rem;`
  - Color: `#797979;`

- `.form-control:focus`:
  - Border color: `#80bdff;`
  - Box shadow: `0 0 0 0.2rem rgba(0, 123, 255, 0.25);`

---

![image](https://github.com/user-attachments/assets/c1bd67d5-136b-4031-9b74-166e91e0754e)

---
