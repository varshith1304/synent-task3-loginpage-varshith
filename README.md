# synent-task3-loginpage-varshith
# MarvelVerse – Fan-Made Login Page UI

A clean, modern login page UI designed as a fan-made Marvel-themed website login screen.

## 📖 About the Project

"MarvelVerse" is a concept login page imagined as something a die-hard Marvel fan would build for their own fan website — dark comic-inspired theme with the iconic Marvel red as the accent color, kept simple and easy to read.

## ✨ Features

- Email and Password input fields with focus states
- Show/Hide password toggle (JavaScript powered)
- "Forgot Password?" link
- Login button with hover and click animation
- Simulated login feedback message on submit
- "Sign up" link for new users
- Fully responsive — adapts to mobile screens

## 🛠️ Built With

- HTML5
- CSS3 (custom properties, flexbox, radial gradient background)
- Vanilla JavaScript (password visibility toggle, form submit handling)

## 📁 File Structure

```
marvel-login.html   → Contains all HTML, CSS, and JS in a single file
```

## 🚀 How to Use

1. Download `marvel-login.html`
2. Open it in any web browser
3. Enter any email/password and click **Log In** to see the simulated response message
4. Click **Show/Hide** to toggle password visibility

## 🎨 Customization

| Section | What to Edit |
|---|---|
| Brand | "MarvelVerse" name and tagline text |
| Colors | CSS variables (`--marvel-red`, `--bg-dark`, etc.) at the top of the `<style>` block |
| Form Logic | `<script>` section — connect the `submit` event to a real backend/auth API |

## 🔐 Notes

- This is a **front-end only** UI — there is no real authentication. The login form currently shows a simulated success message.
- To make it functional, connect the `form` submit handler in the `<script>` tag to your backend API (e.g., using `fetch()`).
- No external dependencies or frameworks used — pure HTML, CSS, and JS.
