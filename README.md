# Tiki Tykes Play Place - MVP Website

A professional, responsive website for Tiki Tykes Play Place, a premium beach-themed indoor play center for children ages 0-5 in Amelia Island, Florida.

## 🌊 Project Overview

Tiki Tykes Play Place is a community-centered destination where families can connect, children can explore and play, and parents can relax in a safe, engaging environment. This website serves as the digital front door for the business, providing information, booking capabilities, and member management.

### Key Features
- **Beach/Island Theme:** Reflects the coastal charm of Amelia Island
- **Age-Appropriate Zones:** Separate areas for different developmental stages
- **Community Focus:** Emphasis on family connections and local partnerships
- **Premium Experience:** High-quality amenities for both children and parents

## 🚀 Built With

- **[Astro](https://astro.build/)** - Modern static site generator
- **TypeScript** - Type-safe JavaScript
- **CSS3** - Modern styling with responsive design
- **HTML5** - Semantic markup for accessibility

## 📋 Current Features

### ✅ Completed
- **Responsive Design:** Mobile-first approach with tablet and desktop optimization
- **Navigation:** Fixed navigation with smooth scrolling and mobile menu
- **Hero Section:** Compelling introduction with clear value proposition
- **About Section:** Company story, mission, and values
- **Services Section:** Detailed play area descriptions and additional amenities
- **Pricing Section:** Clear membership tiers and service pricing
- **Contact Section:** Business information, hours, and contact form placeholder
- **Member Portal:** Login placeholder with integration requirements
- **SEO Optimization:** Meta tags, semantic HTML, and accessibility features

### 🔧 Integration Placeholders
- **Payment Processing:** Stripe/Square integration notes
- **Booking System:** Acuity Scheduling/Calendly recommendations
- **Contact Forms:** Formspree/Netlify Forms setup guides
- **Email Marketing:** Mailchimp/ConvertKit integration plans
- **Member Management:** MindBody/WellnessLiving options

## 🎯 Target Audience

### Primary
- **Families with children ages 0-5**
- **Parents aged 25-40**
- **Residents of Amelia Island, Fernandina Beach, and Yulee**
- **Dual-income households and stay-at-home parents**

### Secondary
- **New and expecting mothers**
- **Grandparents and caregivers**
- **Affluent tourists with young children**
- **Homeschool families and parent groups**

## 💰 Business Model

### Revenue Streams
1. **Memberships:** Monthly ($59) and Family ($99) recurring plans
2. **Drop-in Visits:** $15 per child for occasional visitors
3. **Birthday Parties:** Starting at $349 for complete packages
4. **Classes & Programs:** $20-40 per session for enrichment activities
5. **Private Events:** $200/hour for exclusive facility access
6. **Retail & Snacks:** Branded merchandise and healthy food options

### Key Differentiators
- **Premium themed environment** with island/beach aesthetics
- **Climate-controlled comfort** for year-round play
- **Community focus** with local partnerships
- **Parent amenities** including coffee bar and comfortable seating
- **Safety-first approach** with age-appropriate zones

## 🛠️ Development Setup

### Prerequisites
- Node.js 16+ and npm
- Git for version control

### Installation
```bash
# Clone the repository
git clone <repository-url>
cd tiki-tykes-play-place

# Install dependencies
npm install

# Start development server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview
```

### Project Structure
```
src/
├── components/          # Reusable UI components
│   ├── Hero.astro      # Homepage hero section
│   ├── About.astro     # About section
│   ├── Services.astro  # Play areas and services
│   ├── Pricing.astro   # Membership and pricing
│   └── Contact.astro   # Contact information
├── layouts/            # Page layouts
│   └── Layout.astro    # Main layout with navigation
├── pages/              # Route pages
│   ├── index.astro     # Homepage
│   └── member-portal.astro # Member portal
└── assets/             # Static assets (to be added)
```

## 🎨 Design System

### Color Palette
- **Primary Blue:** #4a90e2 (Ocean blue)
- **Secondary Blue:** #67b8db (Sky blue)
- **Accent Gold:** #ffd700 (Warm gold)
- **Text Dark:** #2c3e50 (Navy)
- **Background:** #f8f9fa (Light gray)

### Typography
- **Primary Font:** Arial, sans-serif
- **Headings:** Bold weights for hierarchy
- **Body Text:** Regular weight, 1.6 line height

### Responsive Breakpoints
- **Mobile:** < 768px
- **Tablet:** 768px - 1024px
- **Desktop:** > 1024px

## 📱 Key Pages

### Homepage (`/`)
- Hero section with value proposition
- About section with company story
- Services overview with themed play areas
- Pricing tiers and membership options
- Contact information and pre-opening notice

### Member Portal (`/member-portal`)
- Login functionality (requires integration)
- Account management features
- Membership benefits overview
- Integration requirements documentation

## 🔗 Required Integrations

### Payment Processing
- **Stripe** (recommended) or **Square**
- Recurring billing for memberships
- One-time payments for drop-ins and parties
- PCI compliance for security

### Booking & Scheduling
- **Acuity Scheduling** or **Calendly**
- Party booking system
- Class registration
- Automated confirmations

### Member Management
- **MindBody** or **WellnessLiving** (all-in-one)
- **Auth0** + custom solution (flexibility)
- Check-in system
- Usage tracking

### Communication
- **Formspree** or **Netlify Forms** (contact forms)
- **Mailchimp** or **ConvertKit** (email marketing)
- **Twilio** (SMS notifications)

## 📊 Analytics & Tracking

### Recommended Tools
- **Google Analytics 4:** Website performance
- **Facebook Pixel:** Social media advertising
- **Hotjar:** User behavior analysis
- **Google Search Console:** SEO monitoring

## 🔒 Security & Compliance

### Requirements
- **SSL Certificate** for HTTPS
- **PCI DSS Compliance** for payments
- **GDPR Compliance** for data protection
- **Liability Waivers** for play center operations

## 📈 SEO Strategy

### On-Page Optimization
- Semantic HTML structure
- Optimized meta tags and descriptions
- Local keyword targeting (Amelia Island, Fernandina Beach)
- Schema markup for rich snippets

### Local SEO
- Google My Business optimization
- Local directory listings
- Community partnership mentions
- Location-specific content

## 🎯 Next Steps

See [TODO.md](./TODO.md) for a comprehensive list of remaining tasks and development priorities.

### Immediate Priorities
1. **Payment Processing Integration** (Stripe setup)
2. **Professional Photography** (play areas and families)
3. **Contact Form Implementation** (Formspree or similar)
4. **Google My Business Setup** (local SEO)
5. **Additional Page Development** (parties, classes, policies)

### Business Launch Requirements
1. **Location Finalization** (lease signing and address)
2. **Legal Compliance** (permits, insurance, waivers)
3. **Staff Hiring** (play specialists and management)
4. **Marketing Launch** (social media and community outreach)

## 🤝 Contributing

This project is currently in development for Tiki Tykes Play Place. For questions or contributions, please contact the development team.

## 📞 Contact

**Tiki Tykes Play Place**
- Email: info@tikitykes.com
- Phone: (904) 555-PLAY
- Location: Amelia Island, FL 32034

---

**Note:** This website is currently in MVP development phase. Many features require external service integrations and will be implemented as the business approaches its launch date.
