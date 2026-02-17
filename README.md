# Velocity Portal

Velocity is a high-performance web navigation interface engineered for speed, clarity, and modern aesthetics. It provides a streamlined gateway to core sub-modules through a high-contrast, distraction-free environment.

## 💎 Design Philosophy

The Velocity interface is built on the principles of **Precision** and **Performance**:
* **Zero-Distraction UI:** Elimination of non-essential visual elements to prioritize user workflow.
* **Motion Engineering:** Optimized CSS hardware acceleration for fluid interaction states.
* **Deep-Black Architecture:** A true-black background (#000000) designed for OLED efficiency and reduced eye strain.

## 🛠 Technical Specifications

This project is a lightweight, frontend-only implementation designed for rapid deployment and maximum compatibility.

* **Architecture:** Static HTML5 / CSS3 (No external dependencies)
* **Styling:** Custom CSS Variables with a focus on Glassmorphism and Flexbox Grid systems.
* **Optimization:** Zero-JS footprint for near-instantaneous DOM rendering.

## 🚀 Static Hosting & Deployment

Velocity is optimized for **static hosting**, meaning it requires no server-side processing (Node.js, PHP, Python) to function. This allows for 100% uptime and global distribution via CDN.

### Recommended Platforms
* **GitHub Pages:** Deploy directly from your repository settings.
* **Vercel / Netlify:** Connect your branch for automated CI/CD.
* **Cloudflare Pages:** Ideal for high-speed edge delivery.

### Deployment Steps
1. Ensure `index.html`, `mathworksheets.html`, and `mathstudents.html` are in the root directory.
2. Push your code to a GitHub repository.
3. Enable static hosting in your provider's dashboard.
4. The site will be live instantly with zero configuration required.

## ⚙️ Configuration

The visual identity of the portal is controlled via a centralized `:root` CSS block. To modify the corporate identity colors:

```css
:root {
    --bg: #000000;      /* Primary Surface */
    --accent: #0070f3;  /* Brand Identity (Electric Blue) */
    --text: #ffffff;    /* Primary Typography */
}
