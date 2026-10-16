# SmartCart AI — Scope and architecture

## Intended users
Customers shopping for vegetables, fruits, groceries, ready-to-cook foods, dairy and household essentials.

## Current architecture
Single-page static web application; in-memory product catalog; rule-based recommendation triggers; localStorage for demo state. No third-party dependencies.

## Product recommendation scenarios
- Cart complementary item: dosa mix → curd; toor dal → drumstick; rice → toor dal; tomato → onion.
- Fruit purchase → banana suggestion when not already in cart.
- Recipe-based cart assembly with missing ingredients only.
- Budget display, savings sorting and daily-essentials labels.
- Pop-up suppression for dismissed or repeated recommendation headings during a session; opt-out switch.

## Production modules not yet implemented
Identity and consent, secure customer profiles, real-time inventory, regional pricing, payment and delivery, offer validation, personalized ML ranking, contextual bandit for pop-up timing, replenishment forecasting, allergen and nutrition verification, audit logs, analytics and model monitoring.

## Suggested evaluation
Recommendation Precision@K, NDCG, CTR, cart add rate, conversion rate, opt-out rate, pop-up dismissal rate, budget adherence, recommendation latency and food waste reduction.
