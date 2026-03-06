# 🤝 Contributing to TaviNote

Thank you for your interest in contributing to TaviNote!  
We welcome all kinds of contributions, including bug reports, feature proposals, and code improvements.

---

## 📋 How to Contribute

### 🐛 If You Find a Bug

1. First, check [Issues](../../issues) to see if the same bug has already been reported.
2. Create a new Issue and include the following:
   - **What happened** — Expected behavior vs. actual behavior
   - **Steps to reproduce** — How to trigger the bug
   - **Environment** — Browser type and version

### 💡 Proposing a New Feature

1. Propose it in [Issues](../../issues) with the `enhancement` label.
2. Tell us in what situations it would be useful and how it should work.

### 🔧 Modifying or Adding Code

1. **Fork** this repository.
2. Create a new branch.
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. Modify the code.
4. Commit your changes.
   ```bash
   git add .
   git commit -m "✨ feat: Add [something]"
   ```
5. Push the branch.
   ```bash
   git push origin feature/your-feature-name
   ```
6. Create a **Pull Request**.

---

## 📐 Coding Rules

### File Structure
- `index.html` — Screen structure (HTML)
- `style.css` — Visual design (CSS)
- `app.js` — Behavior logic (JavaScript)

### Style Guide
- Please write **comments in English** (if translating, or whatever language the project primarily uses for comments).
- Use CSS custom properties (like `var(--accent)`) and avoid direct color specification.
- Match new features to **existing design patterns**.
- Maintain the format of data saved in `localStorage`.

### Commit Messages
We use emoji prefixes:
- ✨ New Feature -> `✨ feat: ...`
- 🐛 Bug Fix -> `🐛 fix: ...`
- 💄 Design Change -> `💄 ui: ...`
- 📝 Documentation -> `📝 docs: ...`
- ♻️ Refactoring -> `♻️ refactor: ...`

---

## 🧪 How to Test

Since TaviNote is an app that runs only in the browser:

1. Open `index.html` in your browser.
2. Manually verify the operation of the modified feature.
3. Check and ensure that other existing features are not broken.

---

## 💬 If You Have Questions

Please create an Issue or leave a comment on a Pull Request.  
Beginners are also very welcome! If you have any questions, please feel free to ask 😊

---

Thank you! 🌟
