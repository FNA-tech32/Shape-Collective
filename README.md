# Shape Collective — AI Marketing Platform & Agency

> **Shape Collective** is an advanced AI-powered social media and influencer marketing platform & agency built for modern direct-to-consumer (DTC) and Consumer Packaged Goods (CPG) brands. The platform automates creator discovery, streamlines influencer partnership workflows, simplifies product fulfillment and gifting, and delivers actionable, real-time ROI and ROAS analytics.

---

## 🌟 Executive Overview

Shape Collective bridges the gap between enterprise-grade influencer intelligence and effortless campaign execution. By analyzing real engagement insights, audience authenticity metrics, and creator value scoring, Shape Collective empowers marketing teams to eliminate hundreds of manual hours every month while scaling profitable customer acquisition.

### Key Capabilities
- **AI Influencer Discovery**: Search creators using proprietary authenticity metrics, engagement quality scores, and value-based partnership matching.
- **End-to-End Campaign Management**: Centralized dashboards, automated approval workflows, and multi-team collaboration tools.
- **Hassle-Free Product Fulfillment**: Integrated product gifting, sample distribution, and affiliate tracking without operational bottlenecks.
- **Organic Content Amplification**: Social listening, high-performing asset libraries, and rights-cleared reposting to brand accounts.
- **Enterprise ROI Analytics**: Transparent performance tracking, click-through rates, revenue attribution, and ROAS benchmarking.

---

## 🎨 5 Multi-Funnel Design Variants (25 Complete Pages)

The project showcases **five distinct architectural and aesthetic design variants**, each engineered around a specific buyer psychology and conversion funnel methodology. A fixed floating toolbar at the bottom of the viewport enables instant switching between all five design styles across all routes without losing navigation state.

| # | Variant | Funnel Style | Aesthetic & Theme | Primary Focus |
|---|---------|--------------|-------------------|---------------|
| **1** | **The Authority** | Dark Luxury Power Funnel | Obsidian / Amber Gold (`#FF6B00`), Clash Display typography, high-contrast premium cards | Enterprise credibility, high-ticket positioning, elite prestige |
| **2** | **The Trust Builder** | Light Social-Proof Funnel | Crisp White / Royal Blue (`#2563EB`), Plus Jakarta Sans, glassmorphism, trust badges | Client testimonials, case studies, risk-reversal guarantees |
| **3** | **The Closer** | Urgency-Driven Funnel | Energetic Coral Red (`#EF4444`), pulsing CTAs, live availability badges | Conversion velocity, limited-time onboarding, active scarcity |
| **4** | **The Storyteller** | Editorial Narrative Funnel | Deep Emerald / Forest Green (`#059669`), Fraunces serif headlines, drop caps, pull quotes | Brand ethos, founder storytelling, deep narrative engagement |
| **5** | **The Minimalist** | Swiss Direct-Response Funnel | Monochromatic Ink / Warm Amber (`#18181B`), hyper-clean whitespace, sharp borders | Frictionless readability, raw metric clarity, instant action |

---

## 🗺️ Website Structure & Pages

Each of the 5 design variants includes dedicated, fully realized implementations of 5 core pages (25 pages total):

1. **Homepage (`/`)**:
   - Hero section with high-converting CTA hierarchy
   - Cross-platform integration marquee (Google, YouTube, Meta, LinkedIn, TikTok, Reddit, Twitch, Snapchat)
   - Verified case study metrics (e.g. Freeway Phoenix +180% engagement, HeroVation 16.2M views)
   - 4-step "How It Works" feature breakdown
   - Interactive ROI & authenticity comparison matrix
   - Customer proof, testimonials, and comprehensive FAQ accordions

2. **Platform (`/platform`)**:
   - Deep architectural breakdown of the AI Influencer Discovery Engine
   - Workflow automation, centralized campaign management, and creator messaging
   - Product gifting and affiliate fulfillment logistics
   - Content rights, asset approval pipelines, and social media scheduling

3. **Agency (`/agency`)**:
   - White-glove managed agency services for hyper-growth brands
   - Strategic consulting, dedicated campaign managers, and creative direction
   - Case study deep-dives and proven brand scaling methodologies

4. **Pricing (`/pricing`)**:
   - Flexible tiered plans (Starter, Growth, Pro, Enterprise)
   - Interactive Monthly / Annual billing toggle
   - Feature availability matrix across tiers
   - Transparent plan highlights and enterprise sales consultation

5. **Contact (`/contact`)**:
   - Interactive demo booking form with qualification inputs
   - Direct and alternative communication channels
   - Studio headquarters and physical office location
   - Immediate response guarantee and trust signals

---

## 📞 Contact Details & Alternative Channels

Shape Collective provides dedicated communication channels for sales inquiries, technical support, and partnership opportunities:

| Channel | Primary Detail | Alternative Detail | Notes |
|---------|----------------|--------------------|-------|
| **Telephone** | `+1 (800) 592-7427` | `+1 (928) 899-2208` | Direct toll-free & alternate support lines |
| **Email** | `hello@shapecollective.agency` | `support@shapecollective.agency` | General inquiries & dedicated client support |
| **Headquarters** | `520 Broadway, Suite 400` | New York, NY 10012 | Creative studio & executive offices |
| **Website** | `https://www.shapecollective.agency` | `https://shape-collective.vercel.app` | Official web portal & live demo |
| **Business Hours** | Monday – Friday | 9:00 AM – 6:00 PM EST | 24-hour response SLA on demo bookings |

---

## 💻 Tech Stack & Architecture

- **Core Framework**: [React 19](https://react.dev/)
- **Routing**: [React Router v7](https://reactrouter.com/) (`react-router-dom`)
- **Animation & Transitions**: [Framer Motion 12](https://www.framer.com/motion/)
- **Icons**: [React Icons 5](https://react-icons.github.io/react-icons/) (`Hi` Heroicons, `Fa` FontAwesome, `Fa6`)
- **Scroll & Viewport Triggering**: [React Intersection Observer](https://github.com/thebuilder/react-intersection-observer)
- **Styling Architecture**: Scoped CSS modules & Theme CSS files per design variant utilizing CSS Custom Properties (Design Tokens)
- **Content System**: Single-Source-of-Truth architecture in `src/data/content.js`

---

## 📂 Project Directory Structure

```text
Shape-Collective/
├── public/
│   ├── favicon.ico
│   ├── index.html              # SEO metadata, web fonts & title
│   ├── manifest.json           # Web app manifest
│   └── robots.txt
├── src/
│   ├── App.js                  # Master router & floating variant switcher
│   ├── index.js                # React root mount
│   ├── index.css               # Global reset & baseline styling
│   ├── data/
│   │   ├── content.js          # Single source of truth for all copy & metadata
│   │   ├── strategy.js         # Design variant conversion strategies & rationale
│   │   ├── competitors.js      # Competitive landscape & market positioning
│   │   └── competitiveResearch.js # Comprehensive market analysis data
│   └── designs/
│       ├── design1-authority/    # Variant 1: Dark luxury power funnel
│       │   ├── components/       # Header, Footer
│       │   ├── pages/            # Home, Platform, Agency, Pricing, Contact
│       │   └── styles/theme.css  # Authority theme design tokens
│       ├── design2-social-proof/ # Variant 2: Light social-proof funnel
│       │   ├── components/       # Header, Footer
│       │   ├── pages/            # Home, Platform, Agency, Pricing, Contact
│       │   └── styles/theme.css  # Trust Builder theme design tokens
│       ├── design3-urgency/      # Variant 3: Bold urgency-driven funnel
│       │   ├── components/       # Header, Footer
│       │   ├── pages/            # Home, Platform, Agency, Pricing, Contact
│       │   └── styles/theme.css  # Closer theme design tokens
│       ├── design4-storytelling/ # Variant 4: Editorial narrative funnel
│       │   ├── components/       # Header, Footer
│       │   ├── pages/            # Home, Platform, Agency, Pricing, Contact
│       │   └── styles/theme.css  # Storyteller theme design tokens
│       └── design5-minimalist/   # Variant 5: Clean direct-response funnel
│           ├── components/       # Header, Footer
│           ├── pages/            # Home, Platform, Agency, Pricing, Contact
│           └── styles/theme.css  # Minimalist theme design tokens
├── package.json
└── vercel.json                 # SPA rewrite rules for production deployment
```

---

## 🚀 Getting Started

### Prerequisites
- **Node.js**: v18.0.0 or higher
- **npm**: v9.0.0 or higher (or pnpm / yarn)

### 1. Installation
Clone the repository and install all dependencies:
```bash
git clone https://github.com/waseemnasir2k26/cpg-synergy-redesign.git Shape-Collective
cd Shape-Collective
npm install
```

### 2. Run Local Development Server
Start the local development server at `http://localhost:3000`:
```bash
npm start
```
The site will hot-reload automatically when modifying files in `src/`.

### 3. Build for Production
Create an optimized production bundle in the `build/` folder:
```bash
npm run build
```

### 4. Run Test Suite
```bash
npm test
```

---

## ☁️ Deployment

The repository includes a ready-to-deploy [`vercel.json`](vercel.json) configuration that handles client-side routing for Single Page Applications (SPA):

```json
{
  "rewrites": [
    {
      "source": "/(.*)",
      "destination": "/index.html"
    }
  ]
}
```

Deploy instantly with Vercel CLI:
```bash
npm install -g vercel
vercel
```

---

## 📄 License & Legal

© 2026 **Shape Collective LLC**. All rights reserved.
Unauthorized duplication, distribution, or reverse-engineering of proprietary marketing strategies and assets is prohibited.
