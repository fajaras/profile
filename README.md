# Professional Profile Website

A sleek, responsive, and modern personal profile and consulting website crafted with **Tailwind CSS**, **HTML5**, and **Vanilla JavaScript**.

---

## 🌟 Features Included

- **Dark & Light Mode**: Built-in toggle with persistent `localStorage` preference and system-theme auto-detection.
- **Glassmorphism Header**: Sticky blurred navigation with active section highlighting as you scroll.
- **Executive Hero Section**: Value proposition headline, live availability status pill, key performance metrics, and quick CTA buttons.
- **About & Core Competencies**: Overview narrative, 4 strategic value pillars, and a 1-click **"Print / Save Profile"** trigger.
- **Consulting Services & Methodology**: 4 detailed service cards with features, plus a 4-stage engagement framework (Discovery &rarr; Blueprint &rarr; Sprints &rarr; Handoff).
- **Track Record & Case Studies**: Concrete project metrics (-43% latency, $350k/yr cloud savings, 3.5x dispatch speed).
- **Client Testimonials**: Verified endorsement quotes with ratings.
- **Interactive Contact Form**: Client inquiry form with instant submission feedback and floating toast alert.
- **Zero Build Step Required**: Works right out of the box in any browser.

---

## 🚀 How to View the Website

### Option 1: Direct File Open
Simply double-click [`index.html`](file:///C:/Users/fajar/profile-website/index.html) to open it in your default browser (Chrome, Edge, etc.).

### Option 2: Local HTTP Server (Node.js)
If you prefer testing with a local web server, run this in your terminal:

```powershell
cd C:\Users\fajar\profile-website
npx serve .
```
Then visit `http://localhost:3000` in your web browser.

---

## ✏️ How to Customize Your Details

Open [`index.html`](file:///C:/Users/fajar/profile-website/index.html) in your editor and customize the following:

1. **Name & Title**:
   - Search for `Fajar Pratama` and replace it with your full name.
   - Update `Consultant & Advisor` or your specific job title.
2. **Contact Email & Location**:
   - Update `fajar.consulting@example.com` to your real email address.
   - Update `Jakarta, Indonesia` to your current city or working timezone.
3. **Services & Pricing**:
   - Edit the cards under `<section id="services">` to reflect your specific consulting packages or technical specialties.
4. **Social Links**:
   - Search for `https://linkedin.com`, `https://twitter.com`, and `https://github.com` in the footer to add your profile URLs.
5. **Photo / Avatar**:
   - Replace the `FP` placeholder initials in the Hero profile card with your own photo by adding an `<img src="assets/images/your-photo.jpg" class="w-20 h-20 rounded-2xl object-cover" alt="Profile">`.

---

## 🌐 Free Hosting Recommendations

You can deploy this website for free in under 2 minutes:
- **GitHub Pages**: Push this directory to a GitHub repository and turn on GitHub Pages.
- **Vercel / Netlify**: Drag and drop the `profile-website` folder directly into Vercel or Netlify.
- **Cloudflare Pages**: Connect your repository or direct upload for ultra-fast worldwide edge hosting.
