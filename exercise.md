# Assignment: Building a Modern User Dashboard

## 🎯 Objective
In this assignment, you will build the HTML structure for a **Modern User Dashboard**. The goal is to master **Semantic HTML5** tags and create robust **HTML Forms** capable of handling various types of user input (text, passwords, dates, choices, and ranges).

## 🛠️ Prerequisites
* Basic understanding of HTML document structure.
* Knowledge of form elements (`<form>`, `<input>`, `<label>`, `<select>`, `<textarea>`).
* Understanding of attributes (`type`, `name`, `id`, `value`, `placeholder`, `required`).

---

## 📝 Step-by-Step Instructions

### Step 1: Project Setup & Head
Create a new file named `index.html`. Set up the standard HTML5 boilerplate.
* **Meta Tags:** Include `viewport` for responsiveness.
* **Title:** Set the title to "Modern User Dashboard".
* **Resources:** Link an external stylesheet (`style.css`) and the **Inter** font from Google Fonts.

### Step 2: Semantic Structure & Navigation
Avoid using `<div>` for everything. Use semantic tags to define the layout.
1.  **Header:** Create a `<header>` element.
2.  **Navigation:** Inside the header, use a `<nav>` element.
    * Add a logo text (e.g., "UserDash").
    * Create a list (`<ul>`) of links (`<a>`) for "Profile", "Settings", and "Contact".
    * *Tip:* Add a class `active` to the current link.

### Step 3: Profile Section (Text & Date Inputs)
Create a `<main>` tag to hold the dashboard content.
1.  Create a `<section>` with `id="profile"`.
2.  **Form Structure:** Open a `<form>` element.
3.  **Inputs:** Create fields for **Full Name**, **Email**, **Phone Number**, and **Date of Birth**.
    * **Accessibility:** Every `<input>` must have a corresponding `<label>`. Use the `for` attribute on the label and `id` on the input to link them.
    * **Attributes:** Use `type="email"` for email validation and `type="tel"` for phone numbers. Use `required` for mandatory fields.

### Step 4: Security Section (Passwords)
Create a new `<section>` with `id="security"`.
1.  **Password Fields:** Create a form for changing passwords.
2.  **Input Type:** Strictly use `type="password"` to mask the characters.
3.  Include fields for "Current Password" and "New Password".

### Step 5: Settings (Radios & Checkboxes)
Create a `<section>` with `id="settings"`. This section focuses on selection controls.
1.  **Radio Buttons (Theme Selection):**
    * Use `type="radio"` for "Light Mode" and "Dark Mode".
    * **Crucial:** Both inputs must have the **same `name` attribute** (e.g., `name="theme"`) so only one can be selected at a time.
2.  **Checkboxes (Notifications):**
    * Use `type="checkbox"` for "Newsletter" and "SMS".
    * Checkboxes allow multiple selections, so they can function independently.

### Step 6: Feedback (Selects & Ranges)
Create a `<section>` with `id="feedback"`.
1.  **Dropdown:** Use the `<select>` and `<option>` tags to create a dropdown menu for choosing a department (Support, Sales, HR).
2.  **Range Slider:** Use `<input type="range">` to let users rate the service from 0 to 10.
    * *Bonus:* Add an `<output>` tag to display the live value of the slider.
3.  **Text Area:** Use `<textarea>` for the message body (allow at least 5 rows).

### Step 7: The "Danger Zone"
Create a final section for critical actions (like deleting an account).
1.  Use a class like `danger-zone` to semantically indicate importance.
2.  Add a confirmation checkbox ("I confirm I want to delete...").
3.  Add a submit button with a specific class (e.g., `btn-danger`).

### Step 8: Footer
Outside of the `<main>` tag, add a `<footer>` containing the copyright information.

---

## ✅ Success Criteria

To receive full marks, your submission must meet the following requirements:

* **Structure:**
    * [ ] The document uses semantic tags: `<header>`, `<nav>`, `<main>`, `<section>`, and `<footer>`.
    * [ ] Indentation is clean and consistent.
* **Forms & Accessibility:**
    * [ ] All forms have a correct `action` and `method` attribute.
    * [ ] **Every input field has an associated `<label>`.**
    * [ ] The `for` attribute on the label matches the `id` on the input.
* **Input Types:**
    * [ ] Correct input types are used (`email`, `password`, `tel`, `date`, `range`).
    * [ ] `radio` buttons for the theme share the same `name` attribute.
    * [ ] `checkbox` inputs are used for multi-select options.
* **Attributes:**
    * [ ] The `required` attribute is present on essential fields (Name, Email, Passwords).
    * [ ] Placeholders provide helpful hints where necessary.
