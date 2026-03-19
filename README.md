# Arubu Enoch — Personal Portfolio Website
## Setup & Hosting Guide (for beginners)

---

## 📁 Folder Structure

```
portfolio/
├── index.html        ← Home page
├── services.html     ← Services page
├── contact.html      ← Contact page
├── style.css         ← ALL styles (edit colors here)
├── README.md         ← This file
└── assets/
    └── photo.jpg     ← ⚠️ ADD YOUR PHOTO HERE
```

---

## 🖼️ Step 1 — Add Your Photo

1. Create a folder named `assets` inside the `portfolio` folder
2. Copy your photo (`Portfolio.jpg`) into it
3. Rename it to `photo.jpg`

That's it! Your photo will appear on the Home page hero and About section.

---

## ✉️ Step 2 — Activate the Contact Form (free)

1. Go to **https://formspree.io** in your browser
2. Click **"Get Started Free"** and sign up
3. Click **"New Form"** → name it "Portfolio Contact"
4. Copy the endpoint URL (looks like `https://formspree.io/f/xabc1234`)
5. Open `contact.html` in any text editor (Notepad, VS Code, etc.)
6. Find this line:
   ```
   action="YOUR_FORMSPREE_ENDPOINT"
   ```
7. Replace `YOUR_FORMSPREE_ENDPOINT` with your copied URL
8. Save the file

Now when someone submits the form, the message goes to your email!

---

## 🚀 Step 3 — Host on GitHub Pages (free)

### First time setup:

1. Go to **https://github.com** and create a free account
2. Click the **"+"** button → **"New repository"**
3. Name it exactly: `yourusername.github.io`  
   *(e.g., if your GitHub username is `enocharubu`, name it `enocharubu.github.io`)*
4. Set it to **Public** → click **"Create repository"**

### Upload your files:

5. Click **"uploading an existing file"** on the new repo page
6. Drag ALL files from your `portfolio` folder into the upload area  
   *(Make sure to also create the `assets` folder with your photo)*
7. Click **"Commit changes"**

### Go live:

8. Wait 1–2 minutes
9. Visit `https://yourusername.github.io` — your site is live! 🎉

---

## ✏️ How to Edit Content

All text is inside the HTML files — no special skills needed!

| What to change | File to open |
|---|---|
| Your name / bio / about text | `index.html` |
| Service descriptions | `services.html` |
| Contact info, social links | `contact.html` |
| Colors | `style.css` (look for `:root { --navy ... }`) |

To edit: right-click any `.html` file → "Open with" → Notepad (or VS Code)

---

## 🎨 Changing Colors

Open `style.css` and find this section at the top:

```css
:root {
  --navy:   #455073;   ← Dark blue-grey (main)
  --gold:   #c0904d;   ← Warm orange (accent)
  --blue:   #6077c0;   ← Medium blue (highlight)
}
```

Just change the hex color codes to update the entire site's color scheme.

---



---

## 📬 Support

Questions? Email: enocharubu@gmail.com
