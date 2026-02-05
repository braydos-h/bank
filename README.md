You are a senior frontend engineer + brand designer. Build a polished, modern, trustworthy demo website for an Australian internet banking startup named “Southern Union Bank” (based in Sydney).

GOALS
- Create a beautiful, premium-feeling marketing site + a demo login page (non-functional auth is fine).
- Style direction: “heritage trust meets modern digital banking” (classic + clean).
- Mobile-first responsive, accessible (WCAG-friendly contrast, labels, focus states).
- Fast load, good typography, strong spacing, tasteful animations.

TECH STACK (choose ONE and generate complete code):
Option A: Next.js (App Router) + Tailwind CSS
Option B: Plain HTML/CSS/JS (no build step)

PAGES / ROUTES
1) Home (/)
   - Hero with headline, subhead, primary CTA (“Open a demo account”), secondary CTA (“View security”)
   - Trust bar (e.g., “Designed in Sydney”, “Bank-grade security patterns”, “24/7 support” — avoid claiming regulated status)
   - Feature grid (e.g., Instant transfers, Smart budgets, Virtual cards, Savings vaults)
   - “How it works” 3-step section
   - Testimonials (clearly marked as sample/demo)
   - Footer with links + disclaimer: “Demo site — features shown are for prototype purposes.”

2) Security (/security)
   - Explain security approach (MFA, device binding, session management, encryption at rest/in transit)
   - Include a simple “Security checklist” component
   - FAQ accordion

3) Pricing (/pricing)
   - 3 tiers (Personal, Plus, Business) with clear comparisons
   - “Most popular” highlight on the middle tier

4) Login Demo (/login)
   - Beautiful login screen with:
     - Email + password inputs
     - “Remember this device”
     - “Forgot password” (dummy)
     - “Continue” button
     - Optional: social login buttons (disabled)
   - After clicking Continue, route to a mock dashboard page (/app) with dummy data (balances, recent transactions, spending donut/chart).
   - No real auth; just store a “loggedIn=true” flag in localStorage for demo navigation.

5) App Mock Dashboard (/app)
   - Top nav, account cards, recent activity table, quick actions (Pay, Transfer, Card controls)
   - Use realistic Australian formatting ($, dates, BSB/account placeholders)
   - Include a “Log out” that clears localStorage and returns to /login

DESIGN REQUIREMENTS
- Brand palette: deep navy + off-white + subtle gold accent (but do not hardcode too many colors; keep tasteful).
- Use a modern serif for headings + clean sans for body (Google Fonts).
- Add subtle motion (hover transitions, section reveal).
- Use SVG icons (Heroicons or inline SVG).
- Include 1–2 high-quality background images and 2–3 supporting images.

FREE STOCK PHOTOS (ONLY)
Use images from these specific sources (provide them as direct URLs in the code and add small attribution in the footer even if not required):
- Unsplash Sydney night / skyline search: https://unsplash.com/s/photos/sydney-night
- Unsplash Sydney skyline search: https://unsplash.com/s/photos/sydney-skyline
- Pexels Sydney Harbour Bridge sunrise photo page: https://www.pexels.com/photo/sydney-harbour-bridge-at-sunrise-31800978/
- Pexels Sydney Opera House sunrise photo page: https://www.pexels.com/photo/sydney-opera-house-at-sunrise-over-harbour-30002035/
- Unsplash “KPMG and Commonwealth bank buildings” photo page: https://unsplash.com/photos/kpmg-and-commonwealth-bank-buildings-3y_JYDl7Czs
- Pexels business meeting search: https://www.pexels.com/search/business%20meeting/

IMPORTANT:
- Download a few images (or use the provided image URLs if hotlinking is acceptable) and wire them into the hero/background/sections.
- If you hotlink, use stable image URLs (e.g., images.unsplash.com). If you need to, explain how to obtain the direct image URLs from those pages.
- Do NOT claim APRA regulation, deposits guaranteed, or anything that implies a banking licence. Keep language “prototype/demo.”

DELIVERABLE
- Output a complete project:
  - file tree
  - all code files
  - instructions to run locally
  - any placeholder env vars (none required)
- Make it look like a real fintech landing page + demo portal.
