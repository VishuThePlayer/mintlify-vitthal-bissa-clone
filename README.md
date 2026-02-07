# Mintlify Documentation Website Clone

A desktop-first documentation-style website inspired by the [Mintlify website](https://mintlify.com), created using only HTML and CSS.

##  Screenshots

### Full Page Overview
![Mintlify Clone - Full Page](./screenshots/cypherninjaa.github.io_Mintlify-Clone_.png)


##  Sections Recreated

All 10 required sections have been implemented:

1. **Top Navigation Bar** - Logo, navigation links (Resources, Documentation, Customers, Blog, Pricing), and CTA buttons (Contact sales, Start for free)

2. **Hero Section** - Main headline with italic styling, short description, email input with CTA button, and gradient background with decorative clouds

3. **Documentation Preview Section** - Sidebar-style navigation with icons, main content area with tabs, search bar, quickstart cards, and right sidebar table of contents

4. **Trusted By / Logos Section** - Company logos row featuring Anthropic, Coinbase, Microsoft, Perplexity, HubSpot, X, PayPal, and Lovable

5. **Feature Highlights** - Three feature cards showcasing:
   - LLMS.TXT & MCP - "Built for both people and AI"
   - Agent - "Self-updating knowledge management"
   - Assistant - "Intelligent assistance for your users"

6. **Intelligent Assistant / UI Preview** - Large UI mockup with enterprise description and CTA

7. **Enterprise Features Section** - Two feature blocks (Partnership & Compliance) with company logos

8. **Case Studies / Customer Stories** - Card-based layout featuring Perplexity, X, Cognition, Vercel, Lovable, and Replit

9. **Final Call-To-Action** - Strong heading with dual CTA buttons and pricing/quickstart cards

10. **Footer** - Multi-column links organized by category (Explore, Resources, Documentation, Company, Legal), social links, security badges, and copyright info

##  Design Specifications

### Fonts

- **Primary Font:** Inter (Google Fonts)
- **Weights Used:** 400 (Regular), 500 (Medium), 600 (Semibold), 700 (Bold)
- **Monospace:** SF Mono, Monaco, Courier New (for code blocks)

### Colors

| Color               | Hex Code  | Usage                                   |
| ------------------- | --------- | --------------------------------------- |
| Primary Green       | `#0D9373` | Brand color, CTAs, active states, links |
| Dark Green          | `#0a7a5f` | Hover states                            |
| Teal Gradient Start | `#0f766e` | Hero background                         |
| Teal Gradient Mid   | `#14b8a6` | Hero background                         |
| Light Teal          | `#5eead4` | Hero background end                     |
| Dark Text           | `#0f172a` | Headings, primary text                  |
| Gray Text           | `#64748b` | Secondary text, descriptions            |
| Light Gray          | `#f1f5f9` | Backgrounds, inputs                     |
| Section Background  | `#f8fafc` | Alternating sections                    |
| Border Gray         | `#e2e8f0` | Borders, dividers                       |
| White               | `#ffffff` | Cards, main background                  |
| Success Green       | `#22c55e` | Status indicators                       |
| Cloud Yellow        | `#fef3c7` | Hero cloud decoration                   |

### Spacing

- Container max-width: 1280px
- Section padding: 100px vertical, 40px horizontal
- Card padding: 24-32px
- Button padding: 10px 20px
- Gap spacing: 8px, 12px, 16px, 24px, 32px, 48px, 64px

### Border Radius

- Small: 4px, 6px
- Medium: 8px
- Large: 12px, 16px

##  File Structure

```
Mintlify/
├── index.html          # Main HTML file
├── styles.css          # All CSS styles
├── README.md           # This documentation file
└── screenshots/        # Output screenshots (add your own)
    └── preview.png
```

##  Technical Details

- **No JavaScript** - Pure HTML/CSS implementation
- **No TailwindCSS** - Custom CSS styles
- **No animations** - Static design as per requirements
- **Desktop-only** - Optimized for 1280px+ viewport width
- **Semantic HTML** - Proper use of header, nav, section, footer elements

##  External Resources

- **Font:** [Inter from Google Fonts](https://fonts.google.com/specimen/Inter)
- **Company Logos:** Referenced from Mintlify's CDN
- **Icons:** Inline SVG icons

##  How to View

1. Clone this repository
2. Open `index.html` in any modern web browser
3. View at 1280px width or larger for best experience

##  Notes

- The website is designed for desktop viewing (1280px+ width)
- Company logos are loaded from Mintlify's CDN for visual accuracy
- All interactive elements (hover states) are CSS-only
- Color scheme and typography closely match the original Mintlify design

##  Author
Vikash,
Created for Web Dev Cohort 2026 Assignment

---

© 2026 - This is an educational project recreating the Mintlify website design.
