# D&H Trust Machine — Placeholder Tracker

All items marked `<!-- PLACEHOLDER: ... -->` in the codebase are tracked here. Resolve each before launch.

---

## Assets

| # | File | Placeholder | Action Required |
|---|------|-------------|-----------------|
| 1 | `src/components/Nav.astro` | D&H text logo | Replace with actual SVG logo from brand team |
| 2 | `src/pages/about.astro` | Founder photo | Insert photo of Arthur Duhamel & Harry Hawk (historical) |
| 3 | `src/pages/about.astro` | Brett Wright photo | Insert current photo of Brett Wright |
| 4 | `src/pages/about.astro` | Community event photos | Insert photos from charity events |
| 5 | `src/pages/index.astro` | Map image | Embed Google Maps or insert static map image of service area |
| 6 | `src/pages/service-areas/index.astro` | Map image | Same as above |
| 7 | `public/images/` | All images empty | Add all photography (technicians, trucks, install jobs, team) |
| 8 | `public/favicon.svg` | Default Astro favicon | Replace with D&H branded favicon |
| 9 | `src/layouts/BaseLayout.astro` | og-default.jpg | Create Open Graph image (1200×630) for social sharing |

---

## Reviews

| # | File | Placeholder | Action Required |
|---|------|-------------|-----------------|
| 10 | `src/components/ReviewTicker.astro` | Placeholder reviews | Pull real reviews from Google Maps API or enter manually |
| 11 | `src/pages/index.astro` | 3 featured reviews | Replace with real customer names, quotes, and photos |
| 12 | `src/pages/reviews.astro` | 9 review cards | Replace with real Google review data |

---

## Integrations

| # | File | Placeholder | Action Required |
|---|------|-------------|-----------------|
| 13 | `src/pages/contact.astro` | ServiceTitan iframe | **Confirm tenant ID `352742287` is correct before launch** |
| 14 | `src/pages/plumbing.astro` | ServiceTitan iframe | Same as above |
| 15 | `src/pages/reviews.astro` | Google Maps reviews link | Add actual Google Business Profile URL |
| 16 | All social links in `Footer.astro` | `href="#"` | Add real Facebook, Instagram, YouTube URLs |
| 17 | `src/pages/careers.astro` | Application form action | Connect to actual ATS (Jobber, BambooHR, email, etc.) |
| 18 | `src/pages/blog/index.astro` | Blog post cards | Connect to real CMS (Contentful, Sanity, Netlify CMS, etc.) |

---

## SEO & Analytics

| # | File | Placeholder | Action Required |
|---|------|-------------|-----------------|
| 19 | `src/layouts/BaseLayout.astro` | Google Analytics | Add GA4 measurement ID `<!-- PLACEHOLDER: Add GA4 tag -->` |
| 20 | `src/pages/index.astro` | aggregateRating reviewCount | Update review count to match current Google total |
| 21 | `astro.config.mjs` | site URL | Confirm `https://dandhac.com` is the correct live domain |
| 22 | All pages | Canonical URLs | Verify final URL structure matches DNS/redirect config |

---

## Legal

| # | File | Placeholder | Action Required |
|---|------|-------------|-----------------|
| 23 | `src/components/Footer.astro` | Terms & Privacy links | Create or link actual Terms & Conditions and Privacy Policy pages |
| 24 | `src/components/Footer.astro` | BBB seal | Add official BBB seal image from BBB accreditation portal |

---

## Launch Checklist

- [ ] All placeholder assets replaced
- [ ] ServiceTitan tenant ID confirmed
- [ ] Real Google reviews loaded
- [ ] Analytics tag added
- [ ] Forms connected to backend/email
- [ ] Custom domain configured in Vercel
- [ ] `astro build` runs clean (currently: ✅ 29 pages, 0 errors)
- [ ] Google Rich Results Test passes on homepage, FAQ pages, contact page
- [ ] Core Web Vitals tested in PageSpeed Insights
- [ ] Mobile tap-to-call tested on real iOS/Android device
- [ ] BookingBar scroll trigger tested on mobile and desktop
