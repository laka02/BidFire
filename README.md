Bidfire1 – How to Run the Project

## Project Overview
This project is a static website made with plain HTML, CSS, and images.  
There is **no backend** and **no build step**. You can open it directly in your browser or use a simple local server.

Main files:
- `index.html` – Home page
- `bidpage.html` – Bidding page
- `aboutus.html` – About Us page
- `contactus.html` – Contact page
- `login.html`, `password.html` – Auth-related pages
- `style.css` – Global styles

All files live in:
`C:\Users\Lakshika Viduranga\Desktop\proooooo\bidfire1-main`

---

## Option 1 – Easiest Way (Open Directly)

1. Open **File Explorer**.
2. Go to the folder:
   `C:\Users\Lakshika Viduranga\Desktop\proooooo\bidfire1-main`
3. **Double-click `index.html`.**
4. Your default browser will open the home page.
5. Use the navigation links on the page to go to:
   - `bidpage.html`
   - `aboutus.html`
   - `contactus.html`
   - other pages as linked.

> Use this option if you just want to quickly preview the site.

---

## Option 2 – Recommended (Run with a Local Server)

Some browsers can restrict certain features (like some paths or future JS) when you open HTML files directly from disk.  
Running a **local server** is closer to how real hosting works.

### 2.1 Using Python (if Python is installed)

1. Open **PowerShell**.
2. Run:

   ```powershell
   cd "C:\Users\Lakshika Viduranga\Desktop\proooooo\bidfire1-main"
   python -m http.server 8000
   ```

3. Open your browser and go to:
   `http://localhost:8000/index.html`

4. To stop the server, go back to the PowerShell window and press `Ctrl + C`.

---

### 2.2 Using Node.js (if Node is installed)

1. Open **PowerShell**.
2. Run:

   ```powershell
   cd "C:\Users\Lakshika Viduranga\Desktop\proooooo\bidfire1-main"
   npx serve . --listen 8000
   ```

3. Open your browser and go to:
   `http://localhost:8000/index.html`

4. To stop the server, go back to the PowerShell window and press `Ctrl + C`.

---

## Folder Structure (Simplified)

- `index.html`
- `bidpage.html`
- `aboutus.html`
- `contactus.html`
- `login.html`
- `password.html`
- `style.css`
- `images/` – All project images

---

## Notes

- You can deploy this project easily to any static hosting (GitHub Pages, Netlify, Vercel, etc.) by uploading the entire `bidfire1-main` folder.
- No extra build tools or dependencies are required.