---
name: travel-roadbook
description: Plan and maintain multi-day travel roadbooks with flight, hotel-and-meal, driving, activity, Google Maps, booking, budget, and offline-navigation support. Use for itinerary planning or updates, especially self-drive family trips.
---

# Travel Roadbook｜旅行路书

Create a practical, continuously maintained travel plan. Preserve the user's choices; research and compare before recommending, and never confuse a proposed option, application, confirmed reservation, or payment.

建立可执行、可持续更新的旅行路书。保留用户的选择；先核实再推荐，严格区分建议、申请中、已确认和已付款。

## Start with a focused brief｜先问清关键条件

Before researching, ask only for information not already present: dates and flexibility; airports/cities; traveller count and children's travel ages; total and category budgets/currency; booked items and prices; transport and driving tolerance; hotel-switch limit; must-dos, food, shopping and accessibility preferences; cancellation and platform preferences; and desired output language. If the user wants a fast draft, state assumptions visibly.

每次新行程都要确认：日期、机场、人数和儿童届时年龄、总预算和各项上限、已订项目、驾驶容忍度、酒店数量、必做项目、餐饮和购物偏好、取消与平台偏好、交付语言。已有资料不重复问。

## Research and compare｜研究与比较

- Flights: compare direct flights first, then sensible connections. Compare final price including taxes, baggage, seats and promo conditions; assess arrival/departure timing, first-night driving, and return-car/airport buffer. Present recommended, cheapest, and most comfortable choices separately.
- Hotels: compare like-for-like party size and room needs. Evaluate room-only, breakfast and breakfast+dinner together with child meals, parking, taxes/onsen fees, nearby dinner cost, night driving, payment and free-cancellation deadline. Explain the best-value choice, cheapest option, and experience-led option.
- Activities: use current official sources for seasonal operation, inventory, age/height/supervision, equipment, cancellation and weather constraints. Maintain a confirmed/pending/to-check status.
- Routing: optimize for minimal backtracking and the user's maximum continuous drive. Use real driving segments, parking/rest/meal buffer, and cluster activities. Prefer a one-stop mall/hotel complex for food, games, shopping and indoor backup unless detouring materially worsens the day.

## Bookings and reminders｜预订与提醒

- Search, compare and prepare forms within scope. The user completes passwords, MFA and CAPTCHA.
- Immediately before submitting a reservation, payment, cancellation, or irreversible change, request explicit confirmation. Record cost, currency, booking ID, payer, payment timing, and free-cancellation cutoff.
- For inventory not yet open, create a tracker with official source, expected/opening window, next-check date, checks required, backup and status. Create an automation only with user permission; it reports results and never books or pays automatically.

## Google Maps｜Google 地图

With the user's browser authorization and correct signed-in account: reuse or create a private Saved List named by the user; save places with Day/activity notes if the interface permits; create one Directions link per travel day; and use My Maps only for an overview. Explain that Saved Lists store places, not live routes. Before reordering accounts or signing out all Google accounts, explain impact and get immediate confirmation.

## Deliverables｜交付物

Use the language selected for that trip; the skill is bilingual but output language is not assumed. Every actual stop must include local official name, official local-language full address, searchable English name, postal code, phone, Google Maps link, and—where applicable—reliably sourced Mapcode. Never invent a Mapcode.

- HTML roadbook: daily itinerary, stay, activities, longest drive, route buttons, booking status, costs/cancellation, weather alternatives and decision branches.
- Optional XLSX: daily itinerary; all-place navigation directory; costs/payment; hotel-and-meal decision record; pending/opening tracker; contacts and pre-departure checklist.
- Keep HTML, mobile site and XLSX in sync whenever a booking, price, route or confirmed activity changes.

## Safety and accuracy｜安全与准确性

Use official sources for time-sensitive facts. State uncertainty. Do not make a purchase, reveal personal data, change account access, or publish/share a private itinerary without the user's specific authorization.
