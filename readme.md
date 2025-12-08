
<div align="center">
  <div style="padding: 18px 22px; border-radius: 22px; backdrop-filter: blur(14px); background: rgba(255,255,255,0.06); border: 1px solid rgba(255,255,255,0.18); box-shadow: 0 18px 40px rgba(0,0,0,0.26); max-width: 980px;">
    <h1 style="margin: 0 0 12px; font-size: 34px;">Hi, I'm Tonmoy — Web Designer & Web Developer</h1>
    <p style="margin: 0; font-size: 16px; line-height: 1.6;">Crafting fast, beautiful, animated web experiences with a glassmorphic twist — in both English & Bangla.</p>
    <p style="margin: 8px 0 0; font-size: 14px; opacity: 0.82;">\ud83d\udca1 Light / Dark aware · \ud83c\udf08 Glass Morphism · \ud83c\udfa8 Motion-friendly · \ud83c\udf0d Multilingual</p>
  </div>
</div>

---

## Quick Links

- Portfolio: [https://tonmoy.dev](https://tonmoy.dev)
- Dribbble: [https://dribbble.com/tonmoy](https://dribbble.com/tonmoy)
- LinkedIn: [https://linkedin.com/in/tonmoy](https://linkedin.com/in/tonmoy)
- Email: [hello@tonmoy.dev](mailto:hello@tonmoy.dev)

## About / আমার সম্পর্কে

**EN:** I design and build modern, responsive sites and design systems that balance aesthetics with performance. I love glassmorphism, soft lighting, and subtle, purposeful motion.

**BN:** আমি ইংরেজি ও বাংলা—দুই ভাষাতেই আধুনিক, রেসপনসিভ ওয়েবসাইট ও ডিজাইন সিস্টেম তৈরি করি। গ্লাসমরফিজম, কোমল লাইটিং আর সূক্ষ্ম এনিমেশন আমার পছন্দ।

## What I Do

- Design Systems & UI Kits (Figma → Web)
- Frontend Engineering (React / Next.js / Astro / Svelte)
- Motion & Micro-interactions (Framer Motion, GSAP)
- Performance & Accessibility (Core Web Vitals, a11y)
- Theming: Light/Dark & glassy surfaces with safe contrasts

## Skills Snapshot / দক্ষতা

`HTML` · `CSS / Tailwind` · `TypeScript` · `React` · `Next.js` · `Astro` · `Svelte` · `Framer Motion` · `GSAP` · `Three.js` · `Node.js` · `UX Writing` · `Figma`

## Featured Work / কাজের নমুনা

- **Lumina Dashboard** — Glassmorphic admin UI with adaptive light/dark, animated charts.
- **Verse Studio Site** — Portfolio with scroll-triggered motion, 90+ Lighthouse.
- **Bilingual Landing** — বাংলা/English toggle, RTL-safe components, fluid typography.
- **Motion Kit** — Reusable animation tokens for Framer Motion & GSAP.

## Design Language

- **Glass Morphism:** Layered translucent cards, soft blur, subtle borders, specular highlights.
- **Light/Dark:** Token-driven palettes with consistent contrast ratios; prefers-color-scheme aware.
- **Motion:** Easing-curves first (easeOutQuad, cubic-bezier), 180–260ms micro-interactions, staggered reveals.
- **Effects:** Ambient gradients, frosted cards, focus-visible rings, safe drop shadows.

## Animation & Effects Hints (Markdown-safe)

- Use SVG with `prefers-reduced-motion` fallbacks for GIF/MP4 embeds.
- Leverage Framer Motion variants for staggered lists and glass cards.
- Apply `backdrop-filter: blur(12px)` with `background: rgba(255,255,255,0.04)` for frosted layers.
- Respect reduced motion: gate heavy transitions behind media queries.

## Multilingual / দ্বিভাষিক কনটেন্ট

- Copy defaults to English with Bangla mirrors for key sections.
- Typography: Pair a humanist Latin with a clear Bengali typeface; align cap-height & baseline.
- Provide language toggle and persist preference (localStorage / cookies).

## Tooling & Stack

- UI: Figma, Penpot, Illustrator, Protopie
- FE: Next.js, Astro, Vite, Tailwind, Framer Motion, GSAP
- QA: Storybook, Playwright, Lighthouse CI, Axe
- Deploy: Vercel, Netlify, Cloudflare Pages

## Availability / যোগাযোগ

**EN:** Open for freelance, collaborations, and design/dev consulting.

**BN:** ফ্রিল্যান্স, কল্যাব বা কনসালটিং-এর জন্য যোগাযোগ করতে পারেন।

- Email: [hello@tonmoy.dev](mailto:hello@tonmoy.dev)
- Calendly: [Book a call](https://calendly.com/tonmoy)

## Badges & Stats

![Profile views](https://komarev.com/ghpvc/?username=tonmoy&style=for-the-badge&color=0f172a)
![GitHub Streak](https://streak-stats.demolab.com?user=tonmoy&theme=transparent&hide_border=true)
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=tonmoy&layout=compact&theme=transparent&hide_border=true)

## Sample Motion Tokens (for Framer Motion)

```ts
const glassCard = {
  hidden: { opacity: 0, y: 24, filter: "blur(6px)" },
  show: {
    opacity: 1,
    y: 0,
    filter: "blur(0px)",
    transition: {
      type: "spring",
      stiffness: 160,
      damping: 18,
      staggerChildren: 0.08,
    },
  },
};
```

## Light/Dark CSS Tokens (Glass)

```css
:root {
  --surface: rgba(255, 255, 255, 0.06);
  --border: rgba(255, 255, 255, 0.18);
  --shadow: 0 18px 40px rgba(0, 0, 0, 0.26);
}
@media (prefers-color-scheme: light) {
  :root {
    --surface: rgba(255, 255, 255, 0.72);
    --border: rgba(255, 255, 255, 0.55);
    --shadow: 0 18px 40px rgba(0, 0, 0, 0.1);
  }
}
.card {
  background: var(--surface);
  border: 1px solid var(--border);
  box-shadow: var(--shadow);
  backdrop-filter: blur(14px);
}
```

## How to Reuse This README

1. Replace links/usernames. 2) Swap badges with your stats. 3) Update projects list. 4) Keep bilingual sections or localize fully. 5) Adjust motion tokens to match your stack.

---

<div align="center" style="opacity:0.85; font-size: 14px;">Designed for a glassy, animated, bilingual GitHub profile — light & dark ready.</div>
