# NetAcad Landing Page — Recreation

A recreation of the [Cisco Networking Academy](https://www.netacad.com) landing page, built from scratch with pure HTML and CSS (no frameworks, no copied code). The goal of the exercise is pixel-level attention to spacing, typography, colors, and layout — on both desktop and mobile.

## Original vs. my version

| Original                                              | My recreation                                   |
| ----------------------------------------------------- | ----------------------------------------------- |
| ![Original desktop](screenshots/original-desktop.png) | ![Clone desktop](screenshots/clone-desktop.png) |
| ![Original mobile](screenshots/original-mobile.png)   | ![Clone mobile](screenshots/clone-mobile.png)   |

More screenshots:

### More NETACAD screenshots

**Hero section:**

![Hero 1](screenshots/hero-1.jpg)
![Hero 2](screenshots/hero-2.png)
![Hero 3](screenshots/hero-3.png)

**Courses section:**

![Courses](screenshots/course-1.png)

### More CLONE NETACAD screenshots

![Clone hero](screenshots/clone-1.png)
![Clone stats](screenshots/clone-2.png)
![Clone subjects](screenshots/clone-3.png)
![Clone courses](screenshots/clone-4.png)
![Clone academy](screenshots/clone-5.png)
![Clone certified](screenshots/clone-6.png)
![Clone next job](screenshots/clone-7.png)

## Tech

- HTML5 (semantic sections, inline SVG icons drawn by hand)
- CSS3 (Grid, Flexbox, custom properties, responsive breakpoints)
- ~7 lines of JS only for the mobile hamburger menu

## How to run

No install, no build step:

```bash
git clone https://github.com/ItsSelma/netacad-clone.git
```

Open `index.html` in your browser, or use the VS Code **Live Server** extension for auto-reload while comparing against the original.

## Notes

- All design tokens (colors, spacing, type weights) live at the top of `style.css` as CSS variables, tuned against the original using browser DevTools.
- Photos go in `images/` folder, I didn't add images, since I don't want anything that could cause some copyright in my repositories; if an image is missing, a neutral gradient placeholder is shown instead.
- The original uses the proprietary CiscoSans typeface; Inter (thin weights) is used as the closest freely available substitute.
- Educational project — the original design belongs to Cisco Systems, Inc.
