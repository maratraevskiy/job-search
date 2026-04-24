# CV Bullet Points Library: Master List

This is the master source for resume bullet points, combining tailored variations and Jira-enriched technical accomplishments.
---

## EmailMagnet (Aug. 2022 – Present)

### 🤖 GenAI & AI Strategy
*   **Agentic Popup Builder:** Reduced merchant popup creation time from ~2 hours to under 2 minutes by shipping a multi-agent GenAI system (copy, layout, and design agents guided by RAG over a best-practice database with live HTML preview and one-click Shopify publishing), resulting in ~25% increase in feature adoption among active merchants within 60 days of launch.
*   **GenAI Product Ownership:** Delivered a net-new GenAI SaaS vertical from 0→1 by owning the full roadmap and engineering delivery end-to-end, resulting in a shipped product within 3 months with zero scope resets.
*   **Time-to-Value Optimization:** Cut merchant onboarding time-to-value from hours to seconds by integrating GenAI into the setup flow to generate instant, store-matched popup configurations, resulting in ~15% reduction in day-1 churn and fewer onboarding support tickets.
*   **AI-Driven UX:** Eliminated manual brand configuration for merchants by building an AI brand theme engine that auto-extracts store colors and fonts to generate native-looking popups, resulting in  ~35% reduction in setup time and higher popup aesthetic match scores in merchant surveys.

### 📊 Analytics, Attribution & Revenue Tracking
*   **Revenue Attribution Engine:** Retained 1 at-risk enterprise client and acquired 2 new ones by architecting a server-side revenue attribution system with multi-model support (Driven vs. Attributed, 7/14/30-day windows) and a merchant-facing analytics dashboard, resulting in transparent ROI data that directly unlocked upsell conversations.
*   **Device-Level Capture Analysis:** Closed a 2× iOS-vs-Android email capture gap by diagnosing a keyboard-obscuring UX bug through PostHog event analysis segmented by OS and screen size, then shipping a scroll fix, resulting in iOS capture rate improving from ~3% to ~7%.
*   **Data Integrity:** Eliminated cross-device event duplication by implementing unique event identifiers across PostHog and PostgreSQL, resulting in ~15% improvement in attribution accuracy and cleaner merchant-facing analytics.
*   **Analytical Dashboards:** Increased merchant product stickiness by delivering a self-serve analytics suite (conversion funnels, sales charts, cohort analysis), resulting in ~30% reduction in performance-data support requests.
*   **Event Strategy:** Enabled full-funnel data visibility by defining a comprehensive PostHog schema covering popup impression through checkout completion, resulting in 12+ trackable events that now underpin all A/B testing and roadmap prioritization decisions.

### 📈 Growth, CRO & Experimentation
*   **Email Capture Growth:** Grew overall email capture rate by 50% by running continuous A/B tests on popup features, targeting logic, and trigger timing, iterating on hypotheses across the merchant base.
*   **Smart Behavioral Triggers:** Improved high-intent re-engagement without UX degradation by launching event-based triggers (scroll depth, time on page, cart value, exit intent), resulting in ~25% lift in secondary popup impressions among users who didn't convert on first view.
*   **Conversion Optimization:** Reduced authorization drop-off by A/B testing Google Auth vs. Email signup flows, identifying the higher-converting path and standardizing it, resulting in ~10% improvement in auth completion rate.
*   **Onboarding UX:** Reduced merchant onboarding drop-off by redesigning the 1-click activation flow to minimize steps from install to first popup live, resulting in ~25% improvement in activation rate within the first 7 days.

### 🔌 API, Integrations & Ecosystem
*   **Technical Discovery:** Prevented integration rework by leading deep technical discovery for third-party API integrations before engineering handoff, defining data flow contracts upfront, resulting in ~20% reduction in integration-related bug tickets post-launch.
*   **Shopify Ecosystem:** Achieved native-grade merchant UX by deeply integrating with Shopify Polaris design system and Admin API to eliminate context-switching, resulting in improved App Store rating and a seamless in-admin management experience.
*   **Sendlane OAuth Integration:** Caught 3+ edge-case bugs before production release by personally end-to-end testing the full Sendlane OAuth flow (auth → list creation → popup capture → contact sync) across multiple test stores, covering both SMS and email capture paths.

### 💰 Monetization & Product Operations
*   **Pricing Strategy:** Increased ARPU and reduced revenue leakage by architecting a 4-tier billing infrastructure (Free to Ultra) with granular feature-gating based on capture limits and customization access, resulting in ~20% upgrade conversion rate from free tier within 90 days of pricing launch.
*   **Billing Flexibility:** Unlocked 5+ high-volume B2B deals by building internal billing override tools and hidden enterprise tiers, enabling sales flexibility without engineering overhead per deal.

---

## Monster Deals (Aug. 2022 – Nov. 2024)

### 🛣️ Roadmap & Funnel Optimization
*   **Roadmap Ownership:** Maintained 99%+ tracking reliability for thousands of daily users by owning the end-to-end transaction funnel roadmap and coordinating cross-team delivery.
*   **Checkout & Payments:** Improved payment authorization rates by ~5–8% by managing payment gateway integrations and optimizing the checkout flow for fraud mitigation and high-conversion paths.
*   **Spin-n-Win Onboarding A/B Test:** Lifted first-purchase rate by 30% for new users by designing and running an A/B test introducing a gamified Spin-n-Win mechanic into the onboarding flow, benchmarked against Temu's proven engagement pattern.
*   **Lifecycle Automation:** Increased repeat transaction volume by automating post-purchase lifecycle communications (invoicing + settlement notifications), resulting in ~15% improvement in repeat purchase rate within 30 days.

### 🛠️ Infrastructure & Data Management
*   **Push Notification Drop Recovery:** Recovered a ~30% decline in repeat purchases and added 10% incremental volume by diagnosing the root cause (Android's mandatory push permission prompt) through Stripe log and platform analytics deep-dive using Pandas, then launching a bonus opt-in incentive campaign.
*   **Catalog A/B Test:** Increased 30-day second purchase rate by 7% by running a full product catalog replacement A/B test, validating product selection as a primary driver of early repeat behavior.
