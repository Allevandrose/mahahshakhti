# Mahashakti Kenya Limited — Corporate Website

Official corporate website for Mahashakti Kenya Limited, a transformer repair and sales company operating in Kenya in collaboration with Mahashakti Energy Ltd. (India).

🔗 **Live Website:** [https://www.mahashaktikenya.com](https://www.mahashaktikenya.com)

---

## Overview

This is a professional B2B website for an industrial transformer company. The site establishes the company's digital presence, showcases services, and provides contact information for potential clients across Kenya.

**Client:** Mahashakti Kenya Limited  
**Industry:** Electrical / Power Transformers  
**Type:** Corporate B2B Website

---

## Key Features

| Feature | Description |
|---------|-------------|
| **Company Profile** | About Us section with partnership history (Mahashakti Energy Ltd., India) |
| **Service Catalog** | Transformer repair, sales, installation, nationwide delivery |
| **Product Showcase** | Step-up, step-down, distribution, power, and industrial transformers |
| **Contact Information** | Phone, email, and contact form for sales inquiries |
| **SEO Optimized** | Meta tags, robots.txt, sitemap.xml for search engine visibility |
| **Responsive Design** | Tailwind CSS for mobile and desktop compatibility |
| **Interactive Elements** | Alpine.js for lightweight interactivity |

---

## Tech Stack

| Category | Technology |
|----------|------------|
| Markup | HTML5 |
| Styling | Tailwind CSS |
| Interactivity | Alpine.js |
| Hosting | Netlify (custom domain) |
| Version Control | Git + GitHub |

---

## Pages

| Page | File | Description |
|------|------|-------------|
| Home | `index.html` | Hero section, service overview, company highlights |
| About | `about.html` | Company history, mission, partnership details |
| Products | `products.html` | Transformer catalog and specifications |
| Contact | `contact.html` | Contact form, phone, email, location |

---

## Project Structure
mahahshakhti/
├── index.html # Homepage
├── about.html # About Us / Company history
├── products.html # Product catalog
├── contact.html # Contact page
├── robots.txt # Search engine crawling instructions
├── sitemap.xml # XML sitemap for SEO
├── _headers # Netlify headers configuration
├── alpine.js # Alpine.js library (local copy)
├── src/
│ ├── css/ # Custom CSS (if any)
│ └── js/ # Additional JavaScript
└── images/ # All website images

text

---

## SEO Implementation

This site includes comprehensive SEO optimization:

| Asset | Purpose |
|-------|---------|
| `robots.txt` | Directs search engines which pages to crawl |
| `sitemap.xml` | Provides Google with page structure and priorities |
| Meta tags | Title, description, keywords on each page |
| Semantic HTML | Proper heading hierarchy (H1, H2, H3) |
| Alt attributes | Images have descriptive alt text |

---

## Local Setup

```bash
# Clone the repository
git clone https://github.com/Allevandrose/mahahshakhti.git
cd mahahshakhti

# No build step required — it's static HTML
# Simply open index.html in your browser or use a local server
Quick local server (optional):

bash
# Using Python
python -m http.server 8000

# Using VS Code Live Server extension
# Right-click index.html → Open with Live Server
Then visit http://localhost:8000

Deployment
This site is deployed on Netlify with a custom domain:

text
https://www.mahashaktikenya.com
Deployment process:

Push changes to GitHub main branch

Netlify automatically builds and deploys

Custom domain configured via Netlify DNS

Client Context
Detail	Information
Client	Mahashakti Kenya Limited
Parent Company	Mahashakti Energy Ltd. (India)
Year Established	2016
Industry	Transformer manufacturing, repair, and sales
Service Area	Nationwide (Kenya)
This website serves as the primary digital touchpoint for industrial clients seeking transformer solutions.

What I Learned
Building this client site taught me:

Working directly with a non-technical client to understand their business needs

Creating a professional B2B presence appropriate for industrial clients

Implementing SEO best practices (robots.txt, sitemap, meta tags)

Deploying static sites with custom domains on Netlify

Structuring content for credibility (company history, partnership details, service areas)

Optimizing images and assets for fast load times in Kenya

Future Improvements
Add inquiry form with email backend (currently static)

Add project portfolio / case studies section

Implement WhatsApp chat widget for instant client communication

Add Google Analytics for visitor tracking

Create downloadable product brochures (PDF)

Add multilingual support (English + Swahili)

Testing
The site has been tested on:

Browser	Status
Chrome (Desktop + Mobile)	✅
Firefox	✅
Safari	✅
Edge	✅
Opera	✅
Troubleshooting
Issue	Solution
Images not loading	Check file paths in /images/ folder
Contact form not sending	This is a static form. Add a backend service (e.g., Formspree, Netlify Forms)
SEO not working	Verify robots.txt and sitemap.xml are in root directory
Custom domain issues	Check Netlify DNS settings and SSL certificate
Contact
Built for Mahashakti Kenya Limited

Developer: Ibrahim Mulei — ibrahimmulei@gmail.com

GitHub: @Allevandrose

📌 Live Site: https://www.mahashaktikenya.com
🔗 Portfolio: ibrahimmulei.netlify.app
