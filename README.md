# 💻 SCSS Starter Kit by Vaibhav

A reusable and customizable SCSS project setup with Bootstrap integration, custom mixins, variables, animations, spacing utilities, and typography. This boilerplate is designed to speed up your frontend development process with a well-organized folder structure and clean modular code.

---

## 📁 Folder Structure

scss-setup-kit/
│
├── css/ # Compiled CSS files (ignored in Git)
│
├── scss/ # Main SCSS folder
│ ├── bootstrap/ # Bootstrap source SCSS files (optional override)
│ ├── _animation.scss # Predefined animation keyframes
│ ├── _button.scss # Button styling
│ ├── _custom-mixin.scss# Reusable SCSS mixins
│ ├── _custom-variables.scss # Custom variables for color, spacing, etc.
│ ├── _spacing.scss # Utility spacing classes
│ ├── _typography.scss # Fonts, headings, text styles
│ └── style.scss # Main SCSS entry file that imports all above
│
├── index.html # Demo HTML file to test compiled CSS
└── .gitignore # Git ignored files like compiled CSS


```bash

sass scss/style.scss css/style.css --watch

```
This command compiles the SCSS files in the `scss` folder and outputs the compiled CSS in
