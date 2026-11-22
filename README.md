# Calculating Your Network Score — Team 6 · Digitas Pitch Interactive Demo

An interactive, executive-ready **Customer Journey Integration Health & Network Score Dashboard** built for the Team 6 Digitas Pitch brand diagnostic presentation.

> **DEMO PROTOTYPE NOTICE:** Built for Team 6 pitch simulation and interactive demonstration purposes. Atelier is calibrated at a baseline Network Score of **62 / 100** (Moderate Integration Tier) with an identifiable financial leakage of **-$24,000,000 / year**. Real enterprise beauty brands (Sephora, Ulta Beauty, L'Oréal, Fenty Beauty, Glossier, Rare Beauty) are evaluated using distinct, authentic benchmark parameters calibrated to their business model and distribution channel.

## 🌐 Live Website (GitHub Pages)
Once GitHub Pages is enabled in this repository's **Settings → Pages**, the live interactive site is accessible at:
```
https://<YOUR-GITHUB-USERNAME>.github.io/atelier-dashboard/
```

---

## ⚡ Core Pitch Model & Formula

### 1. Three-Stage Customer Journey Handoffs (Equal Weight = 33.3 pts each)
Each handoff stage is scored out of **33.3 points** using the exact formula:
$$\text{Points} = 33.3 \times \frac{\text{Benchmark}}{\text{Customers Lost}}$$

| Hand-off Stage | Customers Lost | Benchmark | Points (out of 33.3) | Diagnostic Status |
| :--- | :---: | :---: | :---: | :--- |
| **Search → Social** | **14%** | **10%** | **23.8** | Moderate friction in paid/organic campaign routing |
| **Social → CRM** | **27%** | **15%** | **18.5** | **Primary Bottleneck ($24M Gap)** — severe drop-off in email/SMS capture |
| **CRM → Commerce** | **19%** | **11%** | **19.3** | High cart abandonment and delayed automated triggers |
| **TOTAL NETWORK SCORE** | — | — | **62 / 100** | **Moderate Integration Tier (60–79)** |

---

### 2. $24 Million Financial Loss Formula (Atelier Baseline)
Atelier's primary leakage occurs in the **Social → CRM** handoff, leaking **$24M annually**:

$$\mathbf{1,000,000\text{ customers}} \times (27\% - 15\%) \times \$200 = \mathbf{\$24,000,000 / \text{yr}}$$

- **Target Customer Cohort:** 1,000,000 prospective customers entering the social funnel.
- **Excess Customer Drop:** 27% lost vs. 15% benchmark = **12% excess loss** (120,000 lost customers).
- **Annual Customer Value:** \$200 average order / lifetime value.
- **Recoverable Opportunity at 50% Benchmark Closure:** **+$12,000,000 / yr revenue** (**+$8,400,000 / yr gross profit** at 70% gross margin).

---

### 3. Dynamic Brand-Specific Benchmarks & Randomization
Selecting any brand dynamically updates the slide replica, benchmark ticks, progress bars, and financial formula pill:
- **Atelier Skincare:** Baseline Demo · 62 / 100 · Bottleneck: Social → CRM (-$24M/yr)
- **Sephora:** Omnichannel Prestige Retailer · 83 / 100 · Bottleneck: CRM → Commerce (-$59M/yr BOPIS & Cart Gap)
- **Ulta Beauty:** Mass + Prestige Rewards Powerhouse · 83 / 100 · Bottleneck: CRM → Commerce (-$40.8M/yr Points Checkout Friction)
- **L'Oréal Group:** Global Conglomerate Portfolio · 72 / 100 · Bottleneck: Social → CRM (-$52.3M/yr Brand Silo Leakage)
- **Fenty Beauty:** Social Velocity + Hybrid Retail · 76 / 100 · Bottleneck: CRM → Commerce (-$11.4M/yr Retail Redirect)
- **Glossier:** Community-First DTC · 79 / 100 · Bottleneck: CRM → Commerce (-$4.52M/yr Shipping Threshold Friction)
- **Rare Beauty:** TikTok Viral Brand · 76 / 100 · Bottleneck: CRM → Commerce (-$8.32M/yr Shade Stockout Friction)

> **🎲 Live Simulation:** Click **"🎲 Randomize Benchmarks"** in the pitch card to simulate realistic market fluctuations. Atelier includes an instant **"↺ Reset"** button to return to the canonical pitch numbers.

---

## 🎨 Key Features & Branding
- **Team 6 Brand Identity & Unicorn Logo:** Precision-cropped rearing unicorn insignia with zero glow artifacts on pure black background.
- **Pixel-Perfect Flush Layout:** Grid containers and metric cards are strictly aligned with `grid-auto-rows: 1fr` and `align-items: stretch;`.
- **Slide Replica Hero Visual:** Visual reproduction of the slide deck showing horizontal comparative progress bars, benchmark tick lines, and the glowing financial callout badge.
- **Dynamic Brand Selector:** Side-by-side diagnostic switching between Atelier and industry benchmarks (Sephora, Ulta Beauty, L'Oréal, Fenty Beauty, Glossier, Rare Beauty).
- **High-Contrast Dark Mode:** Chic Digitas Pitch palette featuring **Neon Pink (`#ff007f`)**, **Vivid Orange (`#ff5500`)**, and **White** on **Pure Black (`#000000`)**.

---

## 🚀 How to Host on GitHub Pages
1. Open your repository on [github.com](https://github.com).
2. Click **Add file** $\rightarrow$ **Upload files**.
3. Drag and drop all files from `C:\Users\bakie\.gemini\antigravity\scratch\atelier-dashboard\`.
4. Click **Commit changes**.
5. Wait **30 seconds**, then visit your live GitHub Pages link.
