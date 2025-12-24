# Mission: Build a Modern User Dashboard

**Objective**: Create a complete, interactive, and semantic HTML dashboard for user account management. You will build this file from scratch, following best practices for forms, semantic structure, and accessibility.

**Goal**: The final output must match the provided reference designs (or the provided `index.html` structure) exactly.

---

## Phase 1: The Blueprint (Document Structure)

1.  **Initialize the Document**:
    *   Start with a standard HTML5 declaration `<!DOCTYPE html>`.
    *   Set the root `<html>` element with `lang="en"`.
    *   Create the `<head>` and `<body>` sections.

2.  **Head Configuration**:
    *   Set the character set to `UTF-8`.
    *   Configure the viewport for responsive design: `width=device-width, initial-scale=1.0`.
    *   Set the `<title>` to **Modern User Dashboard**.
    *   Link the external stylesheet `style.css`.
    *   Import the **Inter** font from Google Fonts (weights 400, 500, 600, 700).

---

## Phase 2: Navigation & Branding

3.  **Create the Header**:
    *   Use the `<header>` semantic tag.
    *   Inside, add a `<nav>` element.
    *   Create a `.logo` div containing the text "UserDash" with a span `.dot` for the period.

4.  **Navigation Menu**:
    *   Add a `<ul>` list inside the `<nav>`.
    *   Create three list items with links:
        *   Profile (`#profile`) - mark as `.active`
        *   Settings (`#settings`)
        *   Contact (`#feedback`)

---

## Phase 3: The Profile Section (Text Inputs)

5.  **Main Container**:
    *   Wrap all following content in a `<main>` tag.

6.  **Profile Layout**:
    *   Create a `<section>` with `id="profile"`.
    *   Add a `.section-header` with an `<h2>` "Personal Information" and a `.subtitle` paragraph.

7.  **Profile Form**:
    *   Create a `<form>` pointing to `/update-profile` (POST method).
    *   **Full Name**: specific Input type `text`, placeholder "e.g. John Doe".
    *   **Email**: specific Input type `email`.
    *   **Grid Layout**: Create a `.form-grid` container for Phone and Birthdate.
        *   **Phone**: Input type `tel`.
        *   **Date of Birth**: Input type `date`.
    *   Add a submit button with class `.btn-primary`: "Update Information".

---

## Phase 4: Security Section (Passwords)

8.  **Security Area**:
    *   Create a `<section>` with `id="security"`.
    *   Add header "Security" and subtitle "Manage your password and account security."

9.  **Password Form**:
    *   Create a `<form>` pointing to `/change-password`.
    *   **Current Password**: Input type `password`.
    *   **New Password**: Input type `password`.
    *   Add a "Change Password" submit button.

---

## Phase 5: Settings (Radios & Checkboxes)

10. **Settings Area**:
    *   Create a `<section>` with `id="settings"`.
    *   Add header "Settings".

11. **Theme Selection (Radios)**:
    *   Use a `.radio-group-wrapper`.
    *   Create two options: "Light Mode" (checked by default) and "Dark Mode".
    *   *Tip*: Nest the `<input type="radio">` inside the `<label>` for better UX.

12. **Notifications (Checkboxes)**:
    *   Use a `.checkbox-group-wrapper`.
    *   Create options for:
        *   "Receive newsletter via Email" (checked).
        *   "Receive SMS notifications".

---

## Phase 6: Feedback (Select & Range)

13. **Feedback Area**:
    *   Create a `<section>` with `id="feedback"`.
    *   Add header "Feedback".

14. **Feedback Form**:
    *   Create a `<form>` pointing to `/submit-feedback`.
    *   **Department Dropdown**: Use a `<select>` with options: Technical Support, Sales Department, Human Resources.
    *   **Rating Slider**: Use a `<div class="range-wrapper">` containing an `<input type="range">` (0-10) and an `<output>` element that updates via JS/oninput.
    *   **Message**: Use a `<textarea>` with `rows="5"`.

---

## Phase 7: The Danger Zone

15. **Danger Section**:
    *   Create a `<section>` with class `.danger-zone`.
    *   Add an `<h2>` "⚠️ Danger Zone" and a `.danger-text` subtitle.

16. **Delete Account**:
    *   Create a form for deletion.
    *   Add a **Confirmation Checkbox**: "I confirm that I want to delete my account" (required attribute).
    *   Add a submit button with class `.btn-danger`: "Delete Account".

---

## Phase 8: Footer

17. **Footer**:
    *   Add a `<footer>` outside the `<main>` tag.
    *   Include a copyright notice.

---

## ✅ Checklist for Success

[ ] Document uses correct semantic tags (`nav`, `main`, `section`, `footer`).
[ ] All distinct input types are used effectively (`email`, `tel`, `date`, `password`, `range`).
[ ] Forms have correct `action` and `method` attributes.
[ ] Labels are correctly associated with inputs (using `for` or nesting).
[ ] The Danger Zone is visually distinct (handled by CSS, but structure matters).
