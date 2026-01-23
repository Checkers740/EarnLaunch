

# EarnLaunch – Professional Landing Page



EarnLaunch is a modular, corporate-style landing page designed to convert visitors into sign-ups for Earntrix via a referral link. Inspired by marketplace platforms like Jumia, it’s clean, responsive, and mobile-friendly.

---

## 🚀 Features

- ✅ **Professional Design** – Clean, marketplace-style UI
- ✅ **Responsive Layout** – Works on desktop, tablet, and mobile
- ✅ **Modular Components** – Header, Hero, Trust, Footer separated for easy updates
- ✅ **Single CTA** – Redirects users to Earntrix referral link
- ✅ **Trust Focused** – Secure registration, mobile-friendly, daily opportunities
- ✅ **Easy to Customize** – Update referral link, branding, colors, or add sections

---

## 📁 Project Structure

earnlaunch/ │ ├── index.html           # Main entry file ├── css/ │   ├── base.css         # Typography, colors, reset │   ├── layout.css       # Grids, containers, spacing │   └── components.css   # Header, hero, buttons, trust cards, footer ├── js/ │   ├── main.js          # Loads components dynamically │   └── redirect.js      # Handles CTA button redirect └── components/ ├── header.html      # Header markup ├── hero.html        # Hero section markup ├── trust.html       # Trust / benefits section └── footer.html      # Footer markup

---

## 🛠 Installation

1. Clone the repository:
   ```bash
   git clone ishttps://github.com/sjcheckers/EarnLaunch.git

2. Open index.html in a browser or upload to your hosting service.


3. The Start Earning button redirects to:

https://earntrix.com/user/register.php?ref=WatchandEarn




---

🎨 Customization

Change referral link: js/redirect.js → window.location.href

Change colors/branding: css/base.css → CSS variables

Add new sections: Create HTML files in components/ and load in js/main.js



---

⚠ Disclaimer

Promotional landing page only

Not officially affiliated with Earntrix



---

💡 Future Enhancements

Floating WhatsApp button for live support

Testimonials or FAQ sections

Analytics (Google Analytics / Facebook Pixel)

SEO and OpenGraph meta tags


Author: Steve Checkers 
https://github.com/sjcheckers/EarnLaunch
