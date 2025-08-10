# Happy Rakhi Bandhan

**Short Description**  
This is a small static **GitHub Pages** project made to create personalized Rakhi (Raksha Bandhan) wishes — you can enter your name to generate a shareable link, and visitors opening that link will see a message with your name.

---

## Technologies Used

- **HTML** — `index.html` (main page)
- **CSS** — `style.css`, `sugar.css` (design and animations)
- **JavaScript** — `main.js` (interactive functions like generating links, reading URL parameters, copying to clipboard)
- **Images** — stored in the `img/` folder (Rakhi, QR code, etc.)
- The project is **fully static** (no backend) — easy to host on GitHub Pages.

---

## File Structure

- `index.html` — main webpage
- `style.css` — custom styles
- `sugar.css` — extra CSS (animations / effects)
- `main.js` — JavaScript logic (generating link from input, reading `name` from URL, clipboard copy, etc.)
- `img/` — all images and QR codes

---

## Features & How They Work

1. **Generate Link**  
   - User enters their name.  
   - JavaScript takes that name and creates a shareable URL (e.g., `https://adityajyoti2002.github.io/Happy-Rakhi-Bandhan/?name=Aditya`).  
   - The link can be copied to the clipboard or shared directly.

2. **Animated Name Display**  
   - When a visitor opens the link with a `name` parameter, `main.js` reads it and displays the name with CSS glow/shining effects.

3. **Donate Now / QR Code**  
   - Clicking the "Donate" button displays a QR code (or opens its image link) so people can scan and donate.


---

## How to Clone and Run Locally (Step-by-Step)

> **Note:** Since this is a static website, it works without a backend. You can open `index.html` directly, but using a local HTTP server is recommended for better compatibility.

1. Open Terminal/Command Prompt and clone the repo:

```bash
# Clone the repository
git clone https://github.com/AdityaJyoti2002/Happy-Rakhi-Bandhan.git

cd Happy-Rakhi-Bandhan
