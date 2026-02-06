# Mintlify Documentation Website Recreation

A desktop-first documentation-style website inspired by the Mintlify website. This project recreates the structure, layout, and design aesthetic of Mintlify's marketing site using only HTML and CSS.

## 🎯 Project Overview

This is a static website recreation that captures the essence of Mintlify's modern documentation platform design. The project focuses on structural accuracy, readability, and maintaining the clean, professional look that Mintlify is known for.

## 📋 Sections Recreated

### 1. **Top Navigation Bar**
- Mintlify logo (SVG-based)
- Navigation links (Resources, Documentation, Customers, Blog, Pricing)
- Primary CTAs ("Contact sales" and "Start for free" buttons)
- Sticky positioning with backdrop blur effect

### 2. **Hero Section**
- Badge announcement for new features
- Main headline: "The Intelligent Knowledge Platform"
- Descriptive subtitle about AI-powered documentation
- Email input field with CTA button
- Hero illustration placeholder with gradient overlay

### 3. **Features Introduction**
- "Built for the intelligence age" section
- Brief description of AI integration

### 4. **Documentation Preview Section**
- Left sidebar navigation with three sections:
  - Getting Started
  - Features
  - Components
- Main content area with three feature cards:
  - LLMs.txt & MCP (green accent)
  - Agent (purple accent)
  - Assistant (blue accent)
- Each card includes icon, title, subtitle, and description

### 5. **Trusted By / Company Logos**
- Horizontal logo grid featuring:
  - Anthropic
  - Coinbase
  - HubSpot
  - Zapier
  - AT&T

### 6. **Enterprise Features Section**
- Enterprise badge
- Section title and description
- Call-to-action link
- Two feature cards:
  - Build with partnership
  - Compliance and access control

### 7. **Featured Customer Story**
- Dark background highlight card
- Anthropic customer story
- Statistics display (2M+ monthly developers, 3+ products)
- Image placeholder

### 8. **Customer Stories Grid**
- Section title: "Unlock knowledge for any industry"
- 3-column grid of customer case studies
- 6 customer cards featuring:
  - Perplexity
  - X
  - Kalshi
  - Cognition
  - Together AI
  - Laravel
- Each card includes image, title, and "Read story" link
- Hover effects for interactivity

### 9. **Final Call-To-Action**
- Large heading: "Make documentation your winning advantage"
- CTA buttons
- Two feature boxes:
  - Pricing on your terms
  - Start building
- Links to additional resources

### 10. **Footer**
- 5-column layout with sections:
  - explore
  - resources
  - documentation
  - company
  - legal
- Security badge (SOC II)
- System status indicator
- Copyright information

## 🎨 Design Details

### **Colors Used**

```css
Primary Colors:
- Primary Green: #10B981
- Primary Dark: #059669

Background Colors:
- White: #FFFFFF
- Secondary Background: #F9FAFB
- Dark Background: #0A0A0A

Text Colors:
- Primary Text: #111827
- Secondary Text: #6B7280
- Tertiary Text: #9CA3AF

Accent Colors:
- Purple: #8B5CF6
- Blue: #3B82F6

Borders:
- Border Color: #E5E7EB
```

### **Typography**

- **Font Family**: Inter (Google Fonts)
- **Font Weights**: 300, 400, 500, 600, 700, 800
- **Heading Sizes**:
  - Hero Title: 4rem (64px)
  - Section Title: 2.5rem (40px)
  - CTA Title: 3rem (48px)
  - Highlight Title: 2rem (32px)

### **Spacing System**

```css
--spacing-xs: 0.5rem (8px)
--spacing-sm: 0.75rem (12px)
--spacing-md: 1rem (16px)
--spacing-lg: 1.5rem (24px)
--spacing-xl: 2rem (32px)
--spacing-2xl: 3rem (48px)
--spacing-3xl: 4rem (64px)
--spacing-4xl: 6rem (96px)
```

### **Border Radius**

```css
--radius-sm: 0.375rem (6px)
--radius-md: 0.5rem (8px)
--radius-lg: 0.75rem (12px)
--radius-xl: 1rem (16px)
```

## 🛠️ Technical Specifications

### **Technologies Used**
- HTML5 (Semantic markup)
- CSS3 (Custom properties, Grid, Flexbox)
- Google Fonts (Inter font family)

### **Key Features**
- CSS Grid for complex layouts
- Flexbox for component alignment
- CSS Custom Properties (variables) for maintainable styling
- Semantic HTML structure
- Accessible markup
- Clean, organized CSS with clear section comments

### **No Usage Of:**
- JavaScript
- TailwindCSS or other CSS frameworks
- Animations or transitions (minimal hover effects only)
- Responsive design (desktop-first, no mobile optimization)

## 📁 File Structure

```
mintlify-recreation/
├── index.html          # Main HTML file
├── styles.css          # CSS stylesheet
└── README.md          # This file
```

## 🚀 How to Run

1. Clone this repository
2. Open `index.html` in a modern web browser
3. View at desktop resolution (1400px+ recommended)

```bash
git clone [repository-url]
cd mintlify-recreation
# Open index.html in your browser
```

## 📸 Screenshots

*(Screenshots would be added here showing the final output)*

## 🎯 Design Fidelity

### **What Was Matched:**
- Overall layout structure and spacing
- Color scheme and brand colors
- Typography hierarchy and font choices
- Component styles (cards, buttons, badges)
- Navigation structure
- Footer organization
- Section arrangements

### **Limitations:**
- Images are placeholders (SVG data URIs)
- Icons are simplified SVG shapes
- No actual logo SVGs (used simplified versions)
- No animations or interactive elements beyond hover states
- Desktop-only design (no responsive breakpoints implemented for assignment requirements)

## 📚 Resources Referenced

- Mintlify Official Website: https://www.mintlify.com/
- Mintlify Documentation: https://www.mintlify.com/docs
- Inter Font: https://fonts.google.com/specimen/Inter
- Design inspiration from Mintlify's blog posts on design philosophy

## 🔍 Code Quality

- Semantic HTML5 elements
- BEM-inspired CSS naming conventions
- Organized CSS with clear sections
- CSS variables for maintainability
- Comments for major sections
- Clean, readable code structure

## 💡 Future Enhancements

If this were to be expanded beyond the assignment requirements:
- Add actual Mintlify brand assets and logos
- Implement responsive design for mobile and tablet
- Add subtle animations and transitions
- Include interactive navigation dropdowns
- Integrate real images from Mintlify's website
- Add JavaScript for enhanced interactivity

## 📝 Notes

This recreation focuses on structural accuracy and layout fidelity to the original Mintlify website. While actual images and some interactive features are simplified, the core design language, spacing, typography, and component structure closely mirror the original design.

## 📄 License

This is an educational project created for learning purposes. All design inspiration belongs to Mintlify, Inc.

---

**Created by:** [Your Name]  
**Date:** February 2026  
**Assignment:** Mintlify Website Recreation
