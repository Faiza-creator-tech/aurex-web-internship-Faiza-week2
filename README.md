# aurex-web-internship-Faiza-week2
AUREX Week 2 Internship — Responsive personal portfolio built with CSS3, Flexbox, and Grid 
# aurex-web-internship-Faiza-week2
AUREX Week 2 Internship — Responsive personal portfolio built with CSS3, Flexbox, and Grid # AUREX Full-Stack Engineering Internship — Week 2

**Intern Name:** Faiza
**Domain:** Full-Stack Web Development
**Week:** Week 2 — CSS3 Fundamentals, Flexbox & Grid, Responsive Web Design

## 🔗 Live Deployment
https://faiza-creator-tech.github.io/aurex-web-internship-Faiza-week2/

## 🛠️ CSS Features & Layout Techniques Implemented
- CSS3 core styling: box model (`box-sizing: border-box`), consistent padding/border/margin spacing, custom purple color theme, typography
- **Flexbox** used for: navigation bar, skills tag list, contact form layout
- **CSS Grid** used for: Education + Experience section (side-by-side on tablet/desktop, stacked on mobile)
- Mobile-first **media queries** at 480px, 768px, and 1024px breakpoints for Mobile, Tablet, and Desktop views

## 📱 Screenshots
| Desktop | Tablet | Mobile |
|---|---|---|
| !
[desktop](screenshot/extra.png) | [tablet](screenshort/tab.png) | [mobile](screenshot/mob.png) |

## 💡 Key Learnings & Challenges
- Learned that CSS selectors need a comma to group multiple elements (e.g. `h1, h2`) — without it, the rule silently fails to apply.
- Understood why spacing values like `gap` need units (`rem`, `px`) or the browser ignores them entirely.
- Flexbox worked well for one-dimensional layouts like the nav bar and form, while Grid was better suited for placing Education and Experience side by side.
- Git/GitHub workflow (fixing remote URLs, branch naming, resolving push conflicts) was a valuable challenge alongside the CSS itself this week.

## ✅ Checklist
- [x] Applied full CSS styling to Week 1 HTML page
- [x] Used Flexbox and CSS Grid for layout
- [x] Implemented responsive design (Desktop / Tablet / Mobile)
- [x] Maintained consistent typography and spacing
- [x] Deployed live on GitHub Pages
- [x] Submitted repo link, live link, screenshots, and reflection
---

## Week 3 — Advanced CSS Grid & Animations

**Intern Name:** Faiza
**Domain:** Full-Stack Web Development
**Week:**Week 3
**Live Deployment Link:**https://faiza-creator-tech.github.io/aurex-web-internship-Faiza-week2/ 

### 🎯 What Was Built
This week, I upgraded my existing portfolio website by adding a new **Projects showcase section** using CSS Grid and animations.

### 🔲 CSS Grid Layout Description
- Used `display: grid` with `grid-template-columns: repeat(auto-fit, minmax(250px, 1fr))` on `.project_gallery`, allowing project cards to automatically resize and reflow responsively — without writing extra media queries.
- Combined Grid with Flexbox inside each card (`display: flex; flex-direction: column`) to properly align content (title, description, tags, button) vertically.

### 🎬 Keyframe Animations Description
- **Fade-in animation** (`@keyframes fadeInUp`) — project cards smoothly animate into view (opacity + position) on page load.
- **Staggered delay** (`nth-child`) — each card animates in with a slight delay after the previous one, creating a polished visual effect.
- **Hover elevation effect** — project cards lift up and gain a deeper shadow on hover (`transform: translateY(-8px)`).
- **Button micro-interaction** — the "View Project" button scales up and changes color on hover, and shrinks slightly on click.

### 📱 Performance & Responsive Testing Outcomes
- **Mobile (< 480px):** Cards stack into a single column, content remains readable and properly spaced, no horizontal scroll.
- **Tablet (768px):** 2 cards automatically fit per row due to the grid's auto-fit behavior.
- **Desktop (1024px+):** 3–4 cards display per row, layout remains clean and balanced.
- Animations and hover effects were tested smoothly across browsers (Chrome, Edge) with no visual glitches.

### ✅ Completed Features Checklist
- [x] CSS Grid project gallery (`auto-fit`, `minmax`)
- [x] Flexbox card layout
- [x] Fade-in keyframe animation
- [x] Staggered card animation
- [x] Hover elevation effect
- [x] Button scale/hover micro-interaction
- [x] Fluid typography (`clamp()`)
- [x] Fully responsive (mobile/tablet/desktop)
- [x] Live deployment updated

### 💭 Weekly Reflection
This week, learning CSS Grid and animations gave me a much better understanding of layout design. The combination of `auto-fit` and `minmax()` felt especially powerful since it reduced the need to write manual media queries. Adding animations made the overall UI feel significantly more professional and interactive.
