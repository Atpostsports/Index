# BetStamp - Sports Betting Picks Website

A professional, modern landing page for BetStamp sports betting picks service featuring three subscription tiers, social media integration, and a clean, conversion-focused design.

## 🎨 Design Features

- **Modern, Bold Aesthetic**: Custom typography with Syne and Outfit fonts
- **Gradient Accents**: Eye-catching orange-to-red primary color scheme
- **Responsive Design**: Mobile-first approach that works on all devices
- **Smooth Animations**: Subtle fade-in effects and hover interactions
- **Social Proof**: Integrated stats, testimonials, and social media links

## 📋 Sections Included

1. **Hero Section** - Bold headline with key statistics (win rate, units, ROI)
2. **Social Media Bar** - Quick links to Twitter, Instagram, and Discord
3. **Pricing Tiers** - Three plans (Essential $69, Professional $129, Championship $249) with discount pricing
4. **Features** - Six key benefits highlighting the service value
5. **Testimonials** - Social proof from satisfied members
6. **CTA Section** - Final conversion push with money-back guarantee
7. **Footer** - Complete site navigation and links

## 🚀 Deploying to GitHub Pages

### Option 1: GitHub UI (Easiest)

1. Create a new repository on GitHub
2. Name it `betstamp-website` (or any name you prefer)
3. Upload the `index.html` file
4. Go to Settings → Pages
5. Under "Source", select "Deploy from a branch"
6. Select "main" branch and "/ (root)" folder
7. Click Save
8. Your site will be live at: `https://yourusername.github.io/betstamp-website`

### Option 2: Command Line

```bash
# Initialize git repository
git init

# Add the HTML file
git add index.html README.md

# Commit
git commit -m "Initial commit: BetStamp website"

# Add your GitHub repository as remote
git remote add origin https://github.com/yourusername/betstamp-website.git

# Push to GitHub
git branch -M main
git push -u origin main

# Enable GitHub Pages in repository settings
```

### Option 3: GitHub Desktop

1. Open GitHub Desktop
2. File → New Repository
3. Name: `betstamp-website`
4. Create Repository
5. Copy `index.html` into the repository folder
6. Commit changes
7. Publish to GitHub
8. Enable GitHub Pages in repository settings on GitHub.com

## 🔗 Customization Guide

### Updating Social Media Links

Find these lines in the HTML and replace with your actual URLs:

```html
<!-- Line ~580 -->
<a href="https://twitter.com/betstamp" target="_blank" class="social-link">
<a href="https://instagram.com/betstamp" target="_blank" class="social-link">
<a href="https://discord.gg/betstamp" target="_blank" class="social-link">
```

### Updating Statistics

Find the hero stats section (around line ~520) and update:

```html
<div class="stat-number">65.4%</div>  <!-- Win Rate -->
<div class="stat-number">+284u</div>  <!-- Units Won -->
<div class="stat-number">8.2%</div>   <!-- ROI -->
```

### Changing Colors

Modify CSS variables at the top of the `<style>` section:

```css
:root {
    --primary: #FF4500;        /* Main brand color */
    --primary-dark: #CC3700;   /* Darker shade */
    --accent: #00D9FF;         /* Accent highlights */
    --success: #00C853;        /* Success/checkmarks */
}
```

### Updating Pricing

Find the pricing cards (around line ~700) and update:
- Monthly prices
- Discount prices for 3, 6, 12 months
- Features list
- Tier names and descriptions

## 📱 Responsive Breakpoints

- Desktop: 968px and above (full layout)
- Tablet: 768px - 967px (adjusted grid)
- Mobile: Below 768px (stacked layout)

## ⚡ Performance Features

- Minimal external dependencies (only Google Fonts)
- Inline CSS for instant load
- Optimized animations
- Lazy loading ready
- No JavaScript frameworks (vanilla JS only)

## 🎯 SEO Optimized

- Semantic HTML5 structure
- Meta descriptions included
- Proper heading hierarchy
- Alt text ready for images (when added)
- Schema markup ready

## 📊 Conversion Optimizations

- **Multiple CTAs**: Throughout the page for easy access
- **Social Proof**: Stats, testimonials, and member count
- **Urgency**: "Most Popular" badge on recommended tier
- **Transparency**: All features clearly listed
- **Clear Value Proposition**: ROI and win rates prominently displayed

## 🔧 Recommended Enhancements

### Add Payment Integration
```html
<!-- Replace button click handlers with Stripe/PayPal -->
<button onclick="checkout('essential')">Select Essential</button>
```

### Add Analytics
```html
<!-- Add before closing </head> tag -->
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_MEASUREMENT_ID"></script>
```

### Add Testimonial Photos
```html
<!-- Replace avatar divs with images -->
<img src="testimonial-1.jpg" class="author-avatar" alt="Marcus R.">
```

### Add Discord Widget
```html
<!-- Add to sidebar or footer -->
<iframe src="https://discord.com/widget?id=YOUR_SERVER_ID" width="350" height="500"></iframe>
```

## 📧 Contact & Support

For customization help or questions:
- Discord:discord.com/channels/1472053481937572054/1472080193685295327
- Email: ATPOSTSPORTS@GMAIL.COM
- Twitter: @ATPOSTSPORTS
