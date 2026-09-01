# NEXUS Affiliate Hub — Next-Gen AI Affiliate & High-Ticket SaaS Tracking Platform

A state-of-the-art, high-converting Affiliate Marketing Network and Tracking Platform inspired by **[nexus-affiliate.com](https://nexus-affiliate.com/)**. Built with an obsidian dark-mode cyberpunk FinTech aesthetic, electric cyan & emerald accents, and interactive client-ready features.

---

## 🚀 Key Features Implemented

### 1. High-Impact Landing Page
- **Hero Section**: Dynamic stats counter ($4.85M+ Paid Out, 52,400+ Affiliates, 540+ Active Programs).
- **Live Payout Marquee Ticker**: Real-time simulated feed of verified creator payouts (e.g. *Sarah K. withdrew $1,280 via Stripe*).
- **Interactive Earnings Simulator**: Sliders for Monthly Traffic (1k–100k+), Conversion Rate (0.5%–10%), and Average Bounty ($50–$1,500). Automatically calculates projected Monthly and Annual earnings with dynamic affiliate tier badges (*Starter*, *Growth*, *Pro Marketer*, *Elite Super-Affiliate*).
- **Curated High-Ticket Offers Preview**: Trending software and asset programs.
- **3-Step Workflow & Social Proof**: Creator reviews and trust signals.

### 2. Offers Marketplace (`/offers`)
- **Instant Search & Multi-Tag Filtering**: Filter by keyword, merchant, or tag.
- **Category Filter Pills**: AI Tools & SaaS, Developer & B2B, Fine Art & Luxury, FinTech & Trading, Courses, E-Commerce.
- **Sort Controls**: Highest Payout ($), Lowest Payout ($), Best Conversion Rate (%), Most Popular.
- **Min Payout Range Slider**: Dynamic threshold filter.
- **"Apply to Promote" Modal**: Allows creators to submit traffic sources and receive instant smart tracking link approval.
- **"Offer Details" Drawer**: Highlights payout terms, cookie duration (60–180 days), target audience, and marketing material assets (email swipes, banners, hooks).

### 3. Affiliate Partner Dashboard (`/dashboard`)
- **Real-Time KPI Cards**: Lifetime Revenue ($18,940), Available Balance ($4,250), Total Clicks (24,800), Conversions (542), CVR (2.19%), Avg EPC ($0.76).
- **Interactive Performance Velocity Chart**: Custom HTML5 Canvas gradient area chart mapping traffic velocity and revenue with 7-Day, 30-Day, and 90-Day range toggles.
- **Active Smart Links Table**:
  - Custom generated referral URLs (`https://nexus-affiliate.com/ref/...`).
  - **1-Click Copy Link** with animated toast notifications.
  - **Mobile Traffic QR Code Generator**: Generates scannable QR codes for mobile traffic acquisition.
- **Instant Stripe Connect Payout Center**: One-click instant withdrawal simulation directly to Stripe Express with automated payout ledger history.

### 4. Merchant Onboarding Portal (`/submit-offer`)
- Multi-field submission form for product creators and SaaS founders to list their programs on the network.
- Submissions dynamically validate and add the new program into the live marketplace catalog.

### 5. Technical Architecture & Attribution (`/how-it-works`)
- Deep-dive into **TrackIt AI** first-party cookieless attribution, bot-fraud shielding, and automated Stripe Connect escrow.

---

## 💻 How to View & Present to Your Client

### Option 1: Double-Click Direct Launch
Simply open `index.html` in any modern web browser (Chrome, Edge, Safari, Firefox, Brave). It runs with zero dependencies or complex build steps.

### Option 2: Live Local Server
If you have VS Code Live Server extension or Python installed:
```bash
# Python 3
python -m http.server 3000
```
Then navigate to `http://localhost:3000` in your browser.

---

## 🎨 Design System Specifications
- **Background**: `#07090E` (Deep Cyber Obsidian)
- **Primary Glow**: `#00D9FF` (Electric Cyan)
- **Secondary Profit Glow**: `#10B981` (Neon Emerald)
- **Cards**: Glassmorphic `rgba(14, 19, 32, 0.75)` with `backdrop-filter: blur(16px)` and subtle cyan borders.
- **Typography**: Inter (Body), Outfit (Headings), JetBrains Mono (Financials & Tracking URLs).
