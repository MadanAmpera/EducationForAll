# Education Form All

Project space and repository for the website Education For All

## Requirements Gathered

There are multiple objectives for this website.

1. The primary objective is to provide education content (YouTube videos and Podcasts) to the users (mostly students) in a structured way.
2. The website also has a section for organizations which gives them information about the types of trainings Ankit can provide to their organization, show feedback of previous work and allow them to get in touch with Ankit within this section.
3. The website also serves as a portfolio for Ankit and showcases his achievements and publications.
4. Users both student and corporate can also provide feedback about the material in the website .
5. Ankit also wants to provide updates about his tours on this website and allow users to make appointment to meet him via his Calendly calendar.

---

### A structure of the site

Provided by Ankit and Richa

![Website structure](docs/images/website-structure.png)

---

### Initial Wireframes

Madan developed initial wireframes of the site to visualize the UI/UX of the website

![Initial wireframes](docs/images/initial-wireframes.png)

## Initial System Architecture Diagram

![System Architecture Diagram](docs/images/educationforall.drawio.png)

---

### Development framework - [Nuxt JS](https://nuxt.com/)

Nuxt JS is a frontend framework to build modern websites.

---

### [Decap CMS](https://decapcms.org/)

A content management system is a way to update the content of the site securely. Decap CMS will be coupled with the website and the GitHub repository to update the content.

---

### GitHub

Source code repository and project space to maintain all information about the site. The repository is public at the moment as this allows us to view this space without creating an account for all and also allows us to host the site which is great for demos during the development phase.

---

### [Cloudflare Pages](https://pages.cloudflare.com/)

Cloudflare pages has a free tier where we can host the site for free without any limits on number of requests. The limitations they have for free tier are the number of builds we can do per month (500 builds) and for a small site like ours their limit should be more than enough.

Cloudflare being a global CDN, users will be able to access our site quickly from anywhere in the world. And since our site is static it is even better for delivery speeds and SEO.

Our website will be built using the latest [Jamstack](https://jamstack.org/) architecture and above mentioned components form the core of the architecture and all we need to build and deploy the website.

As for buying the domain name and emails [Namecheap](https://www.namecheap.com/) is one site which we may not commonly know of but the pricing looks very competitive. Request you to search for "domain name providers" and decide on one that suits your needs.

---

## Development plan and Timeline

### ✅ Project Overview

This project aims to build a static website with:

- Decap CMS integration for content management.
- Dynamic content from YouTube and Spotify APIs.
- Automated deployment using Cloudflare Pages and Workers.

**Estimated Duration:** 2–3 months  
**Total Effort:** ~80 hours (20 hrs per phase)  
**Work Allocation:** ~10 hrs/week (freelance alongside regular job)

---

### 🛠 Technologies

- **Frontend:** HTML, CSS, JavaScript (or React/Vue if needed)
- **CMS:** Decap CMS
- **Hosting & CDN:** GitHub Pages (initial), Cloudflare Pages (final)
- **APIs:** YouTube API, Spotify API
- **CI/CD:** Cloudflare Workers for build triggers

---

### 📂 Project Phases & Deliverables

| Phase | Tasks | Deliverables | Estimated Time |
|-------|-------|-------------|----------------|
| **Phase 1** | Requirement gathering, wireframes, tech research | Wireframes & tech stack proposal | 20 hrs |
| **Phase 2** | Scaffold pages, reusable components, integrate Decap CMS | Basic site on GitHub Pages | 20 hrs |
| **Phase 3** | Integrate YouTube & Spotify APIs | Dynamic content pages | 20 hrs |
| **Phase 4** | Setup CI/CD on Cloudflare, build triggers | Fully deployed site | 20 hrs |

---

### 📅 Timeline

- **Week 1–2:** Phase 1 – Requirements & Wireframes  
- **Week 3–4:** Phase 2 – Scaffold & CMS Integration  
- **Week 5–6:** Phase 3 – API Integration  
- **Week 7–8:** Phase 4 – Deployment & Automation  
*(Buffer for feedback and revisions included)*

---

### 🔄 Communication Plan

- Weekly updates via email or short call.
- Demo after each phase for client feedback.

---
