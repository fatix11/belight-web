# BeLight Pro Communitas — Website Requirements

> Reference document for all pre-development, development, and pre-launch requirements.
> Cross off each item as it is completed and confirmed.

---

## 1. Discovery & Strategy

- [ ] Define primary goals of the website (donor acquisition, awareness, partnership, volunteer recruitment)
- [ ] Define target audience segments (international donors, local partners, beneficiaries, government)
- [ ] Define success metrics / KPIs (visits, contact form submissions, donation conversions)
- [ ] Review similar NGO websites for benchmarking (LSM Ethiopia, Water for Good, Drop of Water, Together We Learn)
- [ ] Agree on website tone and voice (warm, hopeful, professional, faith-informed)
- [ ] Confirm primary language(s) — English only, or English + Amharic
- [ ] Confirm organization's legal name and registration details to display on site
- [ ] Identify who owns/manages the site after launch (internal contact person)

---

## 2. Information Architecture

- [ ] Define sitemap (list of all pages)
- [ ] Define navigation structure (top nav, footer nav)
- [ ] Define user flows for each audience segment (donor → donate, partner → contact, visitor → learn)
- [ ] Decide on single-page vs multi-page structure
- [ ] Define page hierarchy and URL structure (e.g. `/about`, `/programs/wash`)

### Suggested Pages
- [ ] Home
- [ ] About Us (mission, vision, values, history)
- [ ] Programs (Education, WASH, Livelihood, Social Protection)
- [ ] Our Team (Board + Staff)
- [ ] Gallery / Impact
- [ ] News / Blog (optional)
- [ ] Donate / Support Us
- [ ] Contact
- [ ] Privacy Policy
- [ ] 404 Error Page

---

## 3. Brand & Design

- [ ] Confirm official logo files (SVG/PNG, light and dark variants)
- [ ] Define primary and secondary brand colors (hex codes)
- [ ] Define typography — heading font, body font, fallback fonts
- [ ] Define spacing, border radius, and visual style guidelines
- [ ] Decide on design system or UI framework (custom CSS, Tailwind, Bootstrap, etc.)
- [ ] Create wireframes for all key pages (low-fidelity first)
- [ ] Create high-fidelity mockups for at least: Home, About, Programs, Contact
- [ ] Get stakeholder sign-off on design before development begins
- [ ] Confirm responsive breakpoints (mobile, tablet, desktop)
- [ ] Confirm mobile-first approach
- [ ] Define image style guidelines (photography tone, overlay treatments)
- [ ] Confirm iconography style (outline, filled, custom)

---

## 4. Content

- [ ] Produce final copy for all pages (approved by org leadership)
- [ ] Confirm organization's official tagline / hero statement
- [ ] Collect high-resolution photos for hero, programs, and gallery sections
- [ ] Collect headshots and bios for all board and staff members
- [ ] Confirm program descriptions for each focus area (Education, WASH, Livelihood, Social Protection)
- [ ] Prepare impact statistics / numbers to display (beneficiaries reached, projects completed, etc.)
- [ ] Prepare testimonials or stories from beneficiaries (if available and consented)
- [ ] Prepare partner/donor logos (if to be displayed)
- [ ] Write meta titles and descriptions for each page (SEO)
- [ ] Prepare content for FAQ section (if included)
- [ ] Confirm contact details: email, phone, LinkedIn, physical address
- [ ] Get consent and releases for all photos of individuals published on site

---

## 5. Technical Requirements

- [ ] Confirm tech stack (HTML/CSS/JS, React, Next.js, CMS, etc.)
- [ ] Confirm hosting platform (Netlify, Vercel, shared hosting, VPS, etc.)
- [ ] Purchase or confirm domain name (e.g. `belightpcngo.org` or `.com`)
- [ ] Set up DNS configuration
- [ ] Set up SSL/TLS certificate (HTTPS — mandatory)
- [ ] Set up version control (Git) — **done**
- [ ] Define folder/project structure
- [ ] Set up local development environment
- [ ] Set up staging/preview environment (for testing before go-live)
- [ ] Confirm browser support targets (Chrome, Firefox, Safari, Edge — latest 2 versions)
- [ ] Confirm minimum mobile screen size support (320px minimum)
- [ ] Decide on CMS or static site (can non-technical staff update content?)
- [ ] Set up contact form with working email delivery
- [ ] Integrate spam protection on forms (e.g. reCAPTCHA or honeypot)
- [ ] Integrate web analytics (Google Analytics 4 or privacy-friendly alternative like Plausible)
- [ ] Decide on donation integration (PayPal, Stripe, local gateway, or external link)
- [ ] Set up social media links (LinkedIn confirmed; others?)
- [ ] Confirm email address(es) to receive form submissions

---

## 6. SEO

- [ ] Define target keywords per page
- [ ] Add meta title and description to every page
- [ ] Add Open Graph tags (for social sharing previews)
- [ ] Add Twitter Card meta tags
- [ ] Generate and submit `sitemap.xml`
- [ ] Add `robots.txt`
- [ ] Add structured data / schema markup (Organization schema at minimum)
- [ ] Ensure all images have descriptive `alt` text
- [ ] Ensure semantic HTML (proper heading hierarchy: H1 → H2 → H3)
- [ ] Register site with Google Search Console
- [ ] Register site with Bing Webmaster Tools

---

## 7. Performance

- [ ] Target Core Web Vitals: LCP < 2.5s, CLS < 0.1, INP < 200ms
- [ ] Compress and optimize all images (use WebP format where possible)
- [ ] Implement lazy loading for images and off-screen content
- [ ] Minify CSS and JavaScript
- [ ] Use a CDN for static assets (Netlify/Vercel handle this automatically)
- [ ] Run Lighthouse audit and achieve score ≥ 90 on Performance, Accessibility, Best Practices, SEO
- [ ] Test load time on slow 3G connection (relevant for Ethiopian context)

---

## 8. Accessibility

- [ ] Follow WCAG 2.1 Level AA standards
- [ ] Ensure sufficient color contrast (minimum 4.5:1 for normal text)
- [ ] All interactive elements are keyboard navigable
- [ ] All images have meaningful `alt` text
- [ ] Forms have proper labels and error messages
- [ ] Focus indicators are visible
- [ ] No content relies solely on color to convey meaning
- [ ] Test with a screen reader (NVDA or VoiceOver)

---

## 9. Security

- [ ] HTTPS enforced (HTTP redirects to HTTPS)
- [ ] Security headers configured (CSP, X-Frame-Options, X-Content-Type-Options, Referrer-Policy)
- [ ] Contact forms protected against spam and injection
- [ ] No sensitive credentials committed to the repository
- [ ] `.gitignore` configured properly (env files, secrets, node_modules)
- [ ] Dependencies kept up to date; no known critical vulnerabilities
- [ ] No unnecessary third-party scripts loaded on site

---

## 10. Legal & Compliance

- [ ] Privacy Policy page written and published
- [ ] Cookie consent banner (if using analytics cookies)
- [ ] Terms of use (if accepting donations or user submissions)
- [ ] Display NGO registration number and authority (ACSO, Proclamation No. 1113/2019)
- [ ] Photo/media consent confirmed for all individuals pictured
- [ ] Donor data handling policy defined (if donations accepted)

---

## 11. Testing

- [ ] Cross-browser testing: Chrome, Firefox, Safari, Edge
- [ ] Cross-device testing: phone (Android + iOS), tablet, desktop
- [ ] All navigation links work and go to correct pages
- [ ] All forms submit correctly and deliver to the right inbox
- [ ] All external links open in a new tab
- [ ] 404 page displays correctly for broken URLs
- [ ] Images load correctly on all pages
- [ ] No console errors in production build
- [ ] Accessibility audit passed (Lighthouse, axe DevTools)
- [ ] Performance audit passed (Lighthouse ≥ 90)
- [ ] Spelling and grammar check on all copy
- [ ] Stakeholder review and sign-off on final build

---

## 12. Deployment

- [ ] Staging environment tested and approved
- [ ] Domain pointed to hosting provider
- [ ] SSL certificate active and valid
- [ ] Redirect `www` → non-www (or vice versa) configured
- [ ] Analytics tracking confirmed working in production
- [ ] Contact form confirmed working in production
- [ ] Run final Lighthouse audit on live site
- [ ] Submit sitemap to Google Search Console
- [ ] Confirm site is not blocked by `robots.txt` in production
- [ ] Set up uptime monitoring (e.g. UptimeRobot — free tier)
- [ ] Document deployment process for future updates

---

## 13. Post-Launch

- [ ] Hand over site credentials and access to org contact person
- [ ] Document how to update content (guide for non-technical staff)
- [ ] Set up regular dependency/security update schedule
- [ ] Review analytics after 30 days and report to stakeholders
- [ ] Gather feedback from real users and plan iteration

---

*Last updated: 2026-06-24*
