# RoofEdge - Premium Roofing Company Website

## 🏗️ Project Overview

A complete, modern multi-page website for **RoofEdge**, a premium US roofing company. Built with plain HTML, CSS, and vanilla JavaScript following 2026 web design trends.

### Design Philosophy
- **Premium minimalist** aesthetic with luxury appeal
- **Trust-first** approach with certifications and warranties
- **Conversion-focused** with clear CTAs throughout
- **Ultra-fast** mobile-first responsive design
- **Accessible** with ARIA roles and keyboard navigation

---

## 📁 File Structure

```
/
├── index.html                  ✅ Home page
├── services.html               ✅ Services overview
├── roof-replacement.html       ✅ Service detail page
├── emergency-repair.html       ✅ Emergency service detail
├── commercial-roofing.html     📄 Commercial service detail
├── financing.html              📄 Financing options
├── projects.html               📄 Project gallery
├── reviews.html                📄 Customer testimonials
├── about.html                  📄 About the company
├── contact.html                ✅ Contact & estimate form
├── blog.html                   📄 Blog article list
├── blog-article.html           📄 Blog article template
├── privacy-policy.html         📄 Privacy policy
├── terms-of-service.html       📄 Terms of service
├── warranty-policy.html        📄 Warranty information
├── style.css                   ✅ Global stylesheet
├── script.js                   ✅ JavaScript functionality
└── images/                     📁 Image assets folder
```

**Legend:** ✅ Created | 📄 Template provided below

---

## 🎨 Brand Identity

### Colors
- **Primary Blue:** `#0B5FFF` (Roofing Blue)
- **Secondary Orange:** `#FF6A00` (Safety Orange - for emergencies/CTAs)
- **Dark:** `#1A1A1A` (Deep Charcoal)
- **Gray:** `#6B6B6B`
- **Light Gray:** `#F5F5F5`
- **White:** `#FFFFFF`

### Typography
- **Font Stack:** -apple-system, BlinkMacSystemFont, 'Segoe UI', 'Inter', 'SF Pro Display'
- **Weights:** 400 (normal), 500 (medium), 600 (semibold), 700 (bold), 800 (extrabold)

### Tagline
**"Built Strong. Finished Clean."**

### Contact Info
- **Phone:** (555) 013-ROOF
- **Email:** hello@roofedge.com
- **Service Area:** Texas (Austin, Dallas, Houston, San Antonio, etc.)

---

## 🖼️ Image Guide

All images should be placed in the `/images/` folder. Below is a complete list of required images with descriptions:

### Logo & Branding
- `logo-icon.png` - Simple roof edge symbol in blue (32x32px)
- `favicon.png` - Favicon version of logo

### Hero Images
- `hero-home.jpg` - Professional roofing crew on modern suburban home, drone perspective
- `hero-services.jpg` - Wide shot of crew working on roof, bright day
- `hero-replacement.jpg` - Beautiful completed roof replacement
- `hero-emergency.jpg` - Storm damage scenario, dramatic sky

### Service Icons (64x64px, transparent PNG)
- `icon-replacement.png` - Roof with checkmark
- `icon-repair.png` - Roof with wrench/tool
- `icon-emergency.png` - Alert symbol with roof
- `icon-metal.png` - Metal roof profile
- `icon-commercial.png` - Commercial building outline
- `icon-inspection.png` - Magnifying glass over roof
- `icon-pricing.png` - Price tag with checkmark
- `icon-certified.png` - Certificate/badge
- `icon-warranty.png` - Shield with checkmark

### Service Detail Icons
- `icon-age.png`, `icon-curling.png`, `icon-granules.png`, `icon-leak.png`, `icon-sagging.png`, `icon-light.png`

### Service Photos
- `service-replacement.jpg` - New shingle roof installation
- `service-repairs.jpg` - Roofer repairing damaged section
- `service-emergency.jpg` - Storm damage on roof
- `service-metal.jpg` - Standing seam metal roof
- `service-commercial.jpg` - Commercial TPO/flat roof
- `service-inspection.jpg` - Drone hovering over roof
- `service-maintenance.jpg` - Gutter cleaning/maintenance
- `service-gutters.jpg` - New gutter installation
- `service-skylight.jpg` - Skylight in modern roof

### Material Photos
- `material-shingle.jpg` - Architectural asphalt shingles
- `material-metal.jpg` - Metal roofing panels
- `material-tile.jpg` - Clay or concrete tile

### Before/After Images
- `before-1.jpg`, `after-1.jpg` - Residential replacement
- `before-2.jpg`, `after-2.jpg` - Storm damage repair
- `before-3.jpg`, `after-3.jpg` - Commercial roof

### Other Images
- `financing-hero.jpg` - Happy homeowners with new roof
- `insurance-support.jpg` - Roofer with tablet documenting damage
- `map.jpg` - Texas map with highlighted service areas
- `emergency-storm.jpg`, `emergency-leak.jpg`, `emergency-collapse.jpg`

### Certifications (24x24px)
- `cert-bbb.png` - BBB logo
- `cert-gaf.png` - GAF Master Elite logo
- `cert-owens.png` - Owens Corning logo
- `cert-insured.png` - Shield/checkmark icon

### Social Icons (20x20px)
- `social-facebook.png`, `social-instagram.png`, `social-linkedin.png`

---

## 🚀 Features

### Global Features (All Pages)
- ✅ Sticky header with scroll effect
- ✅ Mobile hamburger menu
- ✅ Responsive design (Desktop 1440px / Tablet 768px / Mobile 375px)
- ✅ Footer with certifications, service area, and legal links
- ✅ Mobile sticky bottom CTA bar
- ✅ Desktop sticky CTA widget
- ✅ Accessibility (ARIA roles, keyboard navigation)

### JavaScript Functionality
- ✅ Mobile menu toggle
- ✅ FAQ accordion
- ✅ Image slider/carousel
- ✅ Modal windows
- ✅ Form validation and submission
- ✅ Gallery filtering
- ✅ Scroll animations
- ✅ Active navigation highlighting
- ✅ Smooth scroll for anchors
- ✅ Number counter animation
- ✅ Lazy loading images

### Home Page Features
- Hero split layout with stats
- Services snapshot grid (6 cards)
- "Why RoofEdge" section
- Before/after slider
- Financing teaser
- Reviews carousel
- Service area map
- Trust bar below header

### Interactive Components
- FAQ accordion
- Process timeline
- Material selection cards
- Before/after image comparison
- Project gallery with filters
- Contact form with file upload
- Emergency request form

---

## 📱 Responsive Breakpoints

```css
/* Desktop Large */
@media (min-width: 1440px) { }

/* Tablet */
@media (max-width: 768px) { }

/* Mobile */
@media (max-width: 480px) { }
```

---

## ♿ Accessibility Features

- Semantic HTML5 elements (`<header>`, `<nav>`, `<main>`, `<footer>`)
- ARIA roles and labels
- Alt text for all images
- Keyboard navigation support
- Focus states on interactive elements
- High contrast text (WCAG AA compliant)
- Screen reader friendly
- `loading="lazy"` for images

---

## 🔧 Customization Guide

### Changing Colors
Edit the `:root` variables in `style.css`:

```css
:root {
  --color-primary: #0B5FFF;
  --color-secondary: #FF6A00;
  /* ... etc */
}
```

### Adding Pages
1. Copy an existing HTML file
2. Update content while keeping header/footer consistent
3. Add navigation link in all pages
4. Update footer links if needed

### Image Replacement
Simply replace image files in `/images/` folder with same filename. Comments in HTML describe what each image should show.

---

## 📋 Remaining Pages to Create

Use the templates below to create the remaining pages. Follow the same structure as existing pages (header, hero, content sections, CTA, footer).

### Commercial Roofing (commercial-roofing.html)
- Hero with commercial building image
- Services: TPO, PVC, EPDM, Built-Up, Metal
- Maintenance contracts section
- Facility manager benefits
- Multi-property solutions
- CTA: "Schedule Site Visit"

### Financing (financing.html)
- Hero: "Roof Financing Made Easy"
- Monthly payment calculator examples
- Pre-qualification form
- 0% promo badge
- Partner logos (financing companies)
- FAQ about financing

### Projects (projects.html)
- Filter tabs: All / Residential / Commercial
- Gallery grid with project cards
- Modal popup for project details
- Each card shows: image, location, roof type, duration

### Reviews (reviews.html)
- Overall rating summary (4.9/5 with stars)
- Filter buttons: All / Google / Yelp / Facebook
- Review cards grid
- "Leave a Review" CTA
- Optional: video testimonial embed

### About (about.html)
- Brand story
- Team member cards with photos
- Company values (safety, quality, integrity)
- Certifications showcase
- "Join Our Crew" hiring CTA

### Blog (blog.html)
- Featured article hero
- Blog grid with articles
- Each card: image, title, excerpt, read time, category tag
- Newsletter signup CTA

### Blog Article (blog-article.html)
- Article hero image
- Clean typography for content
- Sidebar: Table of contents, related articles
- CTA banner mid-article

### Privacy Policy (privacy-policy.html)
- Standard privacy policy template
- Sections: Data Collection, Use, Sharing, Rights, Cookies, Contact

### Terms of Service (terms-of-service.html)
- Standard terms template
- Sections: Use, Liabilities, Warranties, Governing Law

### Warranty Policy (warranty-policy.html)
- Warranty coverage details
- Manufacturer vs workmanship warranties
- Exclusions
- Claims process
- Transferability

---

## 🎯 SEO Optimization

Each page includes:
- Unique `<title>` tags
- Meta descriptions
- Semantic HTML structure
- Proper heading hierarchy (h1 → h2 → h3)
- Alt text for images
- Clean URL structure

---

## 🚢 Deployment

1. Upload all files to web server
2. Ensure all image paths point to correct `/images/` folder
3. Replace placeholder images with professional photos
4. Update phone number and email throughout
5. Test on multiple devices and browsers
6. Submit sitemap to Google Search Console

---

## 📞 Support

For customization assistance or questions, refer to inline code comments or modify as needed.

---

## ✅ Checklist for Going Live

- [ ] Replace all placeholder images
- [ ] Update contact information (phone, email, address)
- [ ] Verify all links work
- [ ] Test forms (connect to email/CRM)
- [ ] Add Google Analytics
- [ ] Add live chat widget (optional)
- [ ] Test on all devices/browsers
- [ ] Run accessibility audit
- [ ] Optimize image file sizes
- [ ] Set up SSL certificate (HTTPS)
- [ ] Create XML sitemap
- [ ] Connect to Google Search Console
- [ ] Set up Google My Business

---

**Built with ❤️ for premium roofing services. 2026 Modern Web Standards.**
