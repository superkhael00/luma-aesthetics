# LUMA Skin & Aesthetics Clinic — Portfolio Sample

A static one-page website for a **fictional** Philippine aesthetic clinic, built as a portfolio sample by **Khael Mendoza**.

**Live site:** https://superkhael00.github.io/luma-aesthetics/

## Features
- Editorial hero with arched imagery and soft floating motion
- Treatments with ₱ price ranges + "also on the menu" price list
- Before/after drag slider (mouse, touch and keyboard), labeled as an AI-generated illustration
- 3-question "Find your treatment" quiz with a weighted recommendation and a **Book this** button that pre-fills the booking form
- Testimonials clearly marked as sample content
- FAQ accordion
- Booking form with validation (PH mobile format) — **demo only**: on submit it shows "Portfolio demo — this form is not connected" and sends nothing
- Mobile-friendly, respects reduced-motion settings

## Tech
Plain HTML, CSS and vanilla JavaScript — no build step, no frameworks. Hosted on GitHub Pages.

```
index.html   page structure and content
styles.css   design tokens, layout, responsive rules
script.js    slider, quiz, accordion, mobile menu, demo form
images/      AI-generated images (compressed)
```

## Next step for a real client
The booking form is the natural automation hook: connect it to an n8n / Make webhook → Google Sheets or GoHighLevel → SMS/email confirmation → reminder the day before.

---
*Fictional brand — portfolio sample by Khael Mendoza. Images are AI-generated; prices, people and testimonials are illustrative.*
