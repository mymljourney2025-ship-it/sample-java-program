# RR Technosoft - Welcome Page 🎉

A simple, elegant welcome page designed for Mallareddy College Students by RR Technosoft Training Institute.

---

## 🔧 What this contains

- `index.html` — the welcome page with:
  - A curly welcome message (Dancing Script)
  - Big, red **RR TECHNOSOFT** brand heading
  - AI / DevOps icons and a background image
  - Footer showing `KPHB Hyderabad`

---

## 🚀 How to preview

1. Open `index.html` in your browser (double-click the file or right-click > Open with...
2. For live reload while editing, install the **Live Server** extension (VS Code) and click "Go Live".

---

## ✨ Quick customizations

- Change the red accent color:

  Edit the CSS variable near the top of `index.html`:

  ```css
  :root { --accent-red: #e53935; }
  ```

- Replace the background image with a local image:

  Find the `background-image` property in the `body` styles and replace the URL with a relative path:

  ```css
  body { background-image: url('./assets/your-background.jpg'); }
  ```

  Make sure the file exists at the path `assets/your-background.jpg` relative to the `index.html` file.

- Change the curly welcome text or brand text:

  Edit the HTML inside the elements with classes `.welcome` and `.brand`:

  ```html
  <h1 class="welcome">A warm, curly welcome to</h1>
  <div class="brand">RR TECHNOSOFT</div>
  ```

- Swap fonts:

  The page uses Google Fonts (`Dancing Script`, `Inter`) via the `<link>` tag. To change, edit the `<link>` in the `<head>` and update the `font-family` in CSS.

---

## ♿ Accessibility & tips

- Text contrast is improved with a dark overlay; if you swap backgrounds, ensure sufficient contrast by adjusting the overlay in `body::before`.
- Keep important text content in the HTML (not images) so it remains readable and accessible.

---

## 📸 Credits

- Background image: sourced from Unsplash in the current template. Replace with your own image for production use and check licensing requirements.

---

If you'd like, I can:
- Replace the Unsplash image with a local image you provide,
- Change the accent color or provide a few color palette options,
- Export a PDF screenshot of the page for sharing.

Tell me which one you'd like next and I'll do it. ✅