# 🌟 طيف الأمل — Tayf Al-Amal

**موقع تعليمي عربي لأولياء أمور أطفال طيف التوحد**

An Arabic RTL educational website for parents of autistic children, built with Astro and deployed on Vercel.

## 🚀 Tech Stack

- **Framework**: [Astro](https://astro.build) v5 — Static Site Generation
- **Deployment**: [Vercel](https://vercel.com)
- **Language**: Arabic (RTL) — `lang="ar" dir="rtl"`
- **Fonts**: Noto Kufi Arabic (display) + Noto Naskh Arabic (body)
- **Monetization**: Google AdSense

## 📁 Project Structure

```
adsense-aprove/
├── public/
│   ├── favicon.svg
│   ├── robots.txt
│   └── sitemap.xml
├── src/
│   ├── layouts/
│   │   └── BaseLayout.astro     # Main layout (header, footer, SEO, global CSS)
│   └── pages/
│       ├── index.astro           # Homepage
│       ├── about.astro           # About page
│       ├── contact.astro         # Contact page
│       ├── privacy-policy.astro  # Privacy Policy (AdSense required)
│       ├── disclaimer.astro      # Medical Disclaimer
│       ├── articles/
│       │   ├── index.astro                      # Articles listing
│       │   ├── autism-levels-diagnosis.astro     # Article 1
│       │   ├── aba-therapy-home.astro            # Article 2
│       │   ├── visual-schedules-flashcards.astro # Article 3
│       │   ├── social-stories.astro              # Article 4
│       │   ├── apps-books.astro                  # Article 5
│       │   └── autism-faq.astro                  # Article 6
│       └── tools/
│           └── index.astro       # Educational tools page
└── vercel.json                   # Deployment config
```

## 🧑‍💻 Development

```bash
# Install dependencies
npm install

# Start dev server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview
```

## ✅ AdSense Approval Checklist

- [x] Unique, high-quality Arabic content (1800+ words per article)
- [x] About page with author credentials
- [x] Contact page with working form
- [x] Privacy Policy (GDPR + AdSense compliant)
- [x] Medical disclaimer
- [x] All URLs working (no 404s)
- [x] robots.txt configured
- [x] sitemap.xml submitted
- [x] RTL Arabic language properly declared (`lang="ar" dir="rtl"`)
- [x] No duplicate content
- [x] No prohibited content
- [x] AdSense ad slots placed (replace pub-ID and slot IDs)
- [x] Mobile responsive design

## 🔑 Before Going Live

1. Replace `ca-pub-XXXXXXXXXXXXXXXX` with your real AdSense publisher ID
2. Replace `data-ad-slot="XXXXXXXXXX"` with your real ad slot IDs
3. Add the AdSense script tag in `BaseLayout.astro`:
   ```html
   <script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-YOUR_ID" crossorigin="anonymous"></script>
   ```
4. Update `site` URL in `astro.config.mjs` with your real Vercel domain
5. Update `sitemap.xml` URLs with your real domain

## 🌐 Deploy to Vercel

1. Push this folder to a GitHub repository
2. Go to [vercel.com](https://vercel.com) → New Project → Import from GitHub
3. Vercel auto-detects Astro — click Deploy
4. Your site will be live in ~60 seconds

## 📋 Content Topics Covered

1. مستويات طيف التوحد والتشخيص المبكر
2. تقنيات ABA في المنزل
3. الجداول البصرية والبطاقات التعليمية
4. القصص الاجتماعية
5. أفضل التطبيقات والكتب
6. أسئلة شائعة عن التوحد
