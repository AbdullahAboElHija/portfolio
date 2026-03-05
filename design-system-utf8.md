## Design System: Abdullah Abo El-Hija

### Pattern
- **Name:** Portfolio Grid
- **Conversion Focus:**  hover overlay info,  lightbox view, Visuals first. Filter by category. Fast loading essential.
- **CTA Placement:** Project Card Hover + Footer Contact
- **Color Strategy:** Neutral background (let work shine). Text: Black/White. Accent: Minimal.
- **Sections:** 1. Hero (Name/Role), 2. Project Grid (Masonry), 3. About/Philosophy, 4. Contact

### Style
- **Name:** Motion-Driven
- **Keywords:** Animation-heavy, microinteractions, smooth transitions, scroll effects, parallax, entrance anim, page transitions
- **Best For:** Portfolio sites, storytelling platforms, interactive experiences, entertainment apps, creative, SaaS
- **Performance:** ΓÜá Good | **Accessibility:** ΓÜá Prefers-reduced-motion

### Colors
| Role | Hex |
|------|-----|
| Primary | #18181B |
| Secondary | #3F3F46 |
| CTA | #2563EB |
| Background | #FAFAFA |
| Text | #09090B |

*Notes: Monochrome + blue accent*

### Typography
- **Heading:** Archivo
- **Body:** Space Grotesk
- **Mood:** minimal, portfolio, designer, creative, clean, artistic
- **Best For:** Design portfolios, creative professionals, minimalist brands
- **Google Fonts:** https://fonts.google.com/share?selection.family=Archivo:wght@300;400;500;600;700|Space+Grotesk:wght@300;400;500;600;700
- **CSS Import:**
```css
@import url('https://fonts.googleapis.com/css2?family=Archivo:wght@300;400;500;600;700&family=Space+Grotesk:wght@300;400;500;600;700&display=swap');
```

### Key Effects
Scroll anim (Intersection Observer), hover (300-400ms), entrance, parallax (3-5 layers), page transitions

### Avoid (Anti-patterns)
- Corporate templates
- Generic layouts

### Pre-Delivery Checklist
- [ ] No emojis as icons (use SVG: Heroicons/Lucide)
- [ ] cursor-pointer on all clickable elements
- [ ] Hover states with smooth transitions (150-300ms)
- [ ] Light mode: text contrast 4.5:1 minimum
- [ ] Focus states visible for keyboard nav
- [ ] prefers-reduced-motion respected
- [ ] Responsive: 375px, 768px, 1024px, 1440px

