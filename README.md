 NthatiGlamour — Premium Hair & Makeup Website

Student Number: ST10486676

A multi-page website for NthatiGlamour, a South African beauty brand offering 
professional makeup services and premium hair products. Built as a front-end 
web development project across three parts.


 Pages

| Page | File | Description |
|------|------|-------------|
| Home | index.html | Hero section, testimonials, accordion FAQ |
| About | about.html | Founder bio, brand story, mission, vision, and core values |
| Products & Services | services.html | Lightbox gallery, filter tabs, pricing tables |
| Book Now | form.html | Appointment booking form with validation and EmailJS |
| Contact | contact.html | Contact form, Leaflet map, business hours, social links |
| Search | search.html | Global search results page |
| 404 | 404.html | Custom page not found |


 Technologies Used

- HTML5 - Semantic page structure
- CSS3 - Custom stylesheet with responsive layout (no frameworks)
- JavaScript (ES6) - Interactivity, validation, dynamic content
- Google Fonts - Cormorant Garamond (display) + Jost (body)
- EmailJS - Browser-based email sending without a backend server
- Leaflet.js - Open source interactive map
- OpenStreetMap - Map tile provider for Leaflet


 Part 2 Features

- Sticky header navigation across all pages
- Responsive grid layout (mobile, tablet, desktop)
- Booking form with fieldsets, dropdowns, date/time pickers, and radio inputs
- Pricing tables for products and services
- Hover animations and smooth CSS transitions
- Consistent branding via CSS custom properties (variables)
- Selectors, Box Model, Flexbox, CSS Grid
- Fluid Typography using clamp()
- Transitions and Animations
- Positioning
- Backgrounds and Visual Effects

 Design Decisions
- Colour palette: Cream, blush, rose, and warm gold chosen to reflect a 
  premium, feminine beauty brand
- Typography: Cormorant Garamond for headings paired with Jost for body text
- Layout: CSS Grid and Flexbox used throughout, no external CSS framework
- CSS variables: All colours and fonts defined as custom properties


 Part 3 Features

JavaScript Files

| File | Page | Purpose |
|------|------|---------|
| animations.js | All pages | Loading screen, scroll animations, back to top, cookie banner |
| contact.js | contact.html | EmailJS contact form, validation, character counter, Leaflet map |
| form.js | form.html | EmailJS booking form, validation, date validation, character counter |
| index.js | index.html | Dynamic testimonial cards, accordion FAQ |
| services.js | services.html | Lightbox gallery, service filter tabs |
| search.js | search.html | Global search results |

 Interactive Elements
- Lightbox gallery on services page - click images to view full size
- Accordion FAQ on homepage - expandable questions and answers
- Service filter tabs on services page - filter by hair or makeup category
- Leaflet interactive map on contact page with location marker
- Global search bar in navbar linking to search results page

 Dynamic Content
- Testimonial cards loaded dynamically from a JavaScript array on homepage
- Service filter dynamically shows and hides cards based on category selection
- Search results page dynamically renders matched content from site data

 Forms
- Full client side validation on both booking and contact forms
- Email format validation using regex
- Phone number format validation using regex
- Future date validation on booking form, past dates rejected
- EmailJS integration for AJAX style submission without page reload
- Success and error messages displayed after submission
- Live character counter on message fields with colour warnings at 400 and 480 characters

 Animations
- Scroll fade in animations using IntersectionObserver API on all pages
- Animated loading screen on all pages
- Navbar scroll effect on all pages
- Back to top button appears after 300px scroll

 SEO
- Meta charset, viewport, description, keywords and author on all pages
- Descriptive title tags on all pages
- robots.txt instructing search engine crawlers
- sitemap.xml listing all pages with last modified dates

Additional Features
- Cookie consent banner with localStorage on all pages
- Custom 404 error page
- Social media links in footer across all pages


 Off-Page SEO Note
Social media links were added to the footer linking to Instagram, Facebook 
and TikTok to demonstrate social media promotion. Since NthatiGlamour is a 
fictional business created for this assessment, these accounts do not exist 
and the links are for demonstration purposes only. Genuine backlinks from 
external websites were not pursued for the same reason.


File Structure

NthatiGlamour/

index.html

 about.html
 
 services.html

 form.html

 contact.html

 search.html

 404.html

 style.css

 robots.txt

 sitemap.xml

 animations.js

 contact.js

 form.js

 index.js

 services.js

 search.js

nthatigl_amour_logo.jpg

 images.jpg

 Nthati Moloi.jpg

 nthatiglamour_products.jpg

 makeup_looks_nthatiglamour.jpg

expert_consultation_nthatiglamour.jpg



 References

Google (2026) *Google Fonts: Cormorant Garamond*. Available at:
https://fonts.google.com/specimen/Cormorant+Garamond
(Accessed: 2026).

Google (2026) *Google Fonts: Jost*. Available at:
https://fonts.google.com/specimen/Jost
(Accessed: 2026).

EmailJS (2026) *EmailJS Browser SDK*. Available at:
https://www.emailjs.com
(Accessed: 2026).

Leaflet (2026) *Leaflet: an open source JavaScript library for 
interactive maps*. Available at:
https://leafletjs.com
(Accessed: 2026).

OpenStreetMap (2026) *OpenStreetMap*. Available at:
https://www.openstreetmap.org
(Accessed: 2026).

