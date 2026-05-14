# 📋 Advanced Form Validation

A sleek, modern registration form with real-time client-side validation, dark/light theme toggle, and animated glassmorphism UI — built with pure HTML, CSS, and JavaScript.

![HTML](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

---

## ✨ Features

- **Form Validation** — Validates name (min. 3 chars), email format, and password (min. 6 chars) on submit
- **Visual Feedback** — Green border for valid fields, red border + error message for invalid ones
- **Password Toggle** — Show/hide password with a single click
- **Dark / Light Mode** — Toggle between themes with smooth transitions
- **Glassmorphism UI** — Frosted-glass card design with animated floating background circles
- **Success Message** — Animated confirmation on successful submission, auto-resets after 3 seconds
- **No Dependencies** — Zero external libraries; pure vanilla HTML/CSS/JS

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/memon744/task-06.git
cd advanced-form-validation
```

### 2. Open in your browser

Simply open `index.html` directly in any modern browser — no build step or server required.

```bash
open index.html        # macOS
start index.html       # Windows
xdg-open index.html    # Linux
```

---

## 📁 Project Structure

```
advanced-form-validation/
└── index.html    # All HTML, CSS, and JS in a single file
```

---

## 🖼️ Preview

| Dark Mode | Light Mode |
|-----------|------------|
| Deep navy glassmorphism background | Soft light gray background |

---

## 🧪 Validation Rules

| Field    | Rule                              |
|----------|-----------------------------------|
| Name     | Minimum 3 characters              |
| Email    | Must match standard email format  |
| Password | Minimum 6 characters              |

---

## 🛠️ How It Works

1. The user fills in the **Name**, **Email**, and **Password** fields.
2. On clicking **Submit**, each field is validated:
   - ✅ Valid → green border, error hidden
   - ❌ Invalid → red border, error message shown
3. If all fields pass, a **success banner** appears and the form resets after 3 seconds.
4. The **Show/Hide** toggle on the password field switches `input[type]` between `password` and `text`.
5. The **theme button** toggles a `.light` class on `<body>`, switching the entire color scheme via CSS overrides.

---

## 🎨 UI Details

- **Background:** Fixed dark (`#0f172a`) with three animated translucent circles using CSS `@keyframes float`
- **Card:** `backdrop-filter: blur(18px)` glassmorphism with `rgba` white background
- **Inputs:** Scale slightly on focus with a glowing white `box-shadow`
- **Animations:** Fade-in on page load (`fadeIn`), pop-in on success message (`pop`)

---

## 🌐 Browser Support

Works in all modern browsers that support `backdrop-filter`:

| Chrome | Firefox | Safari | Edge |
|--------|---------|--------|------|
| ✅ 76+ | ✅ 103+ | ✅ 9+  | ✅ 79+ |

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

## 🙌 Contributing

Contributions, issues, and feature requests are welcome! Feel free to open an issue or submit a pull request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -m 'Add some feature'`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Open a Pull Request
