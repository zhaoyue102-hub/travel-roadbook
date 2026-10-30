---
name: travel-roadbook
description: Plan and maintain multi-day travel roadbooks with flight, hotel-and-meal, driving, activity, Google Maps, booking, budget, and offline-navigation support. Use for itinerary planning or updates, especially self-drive family trips.
---

# Travel Roadbook｜旅行路书

Create a practical, continuously maintained travel plan. Preserve the user's choices; research and compare before recommending, and never confuse a proposed option, application, confirmed reservation, or payment.

建立可执行、可持续更新的旅行路书。保留用户的选择；先核实再推荐，严格区分建议、申请中、已确认和已付款。

## Start with a focused brief｜先问清关键条件

Before researching, ask only for information not already present: dates and flexibility; airports/cities; traveller count and children's travel ages; total and category budgets/currency; booked items and prices; transport and driving tolerance; hotel-switch limit; must-dos, food, shopping and accessibility preferences; cancellation and platform preferences; and desired output language. Treat shopping as a real trip requirement: ask for item or brand/category, budget, tax-free needs, luggage-space impact, preferred area/store and acceptable detour. If the user wants a fast draft, state assumptions visibly.

每次新行程都要确认：日期、机场、人数和儿童届时年龄、总预算和各项上限、已订项目、驾驶容忍度、酒店数量、必做项目、餐饮和购物偏好、取消与平台偏好、交付语言。购物须进一步确认品类／品牌、预算、退税、行李空间、目标商圈／门店及可接受绕路。已有资料不重复问。

## Evidence intake and change control｜原始材料与变更控制

- Treat confirmation emails, booking PDFs, screenshots and receipts as source evidence. For each material booking, retain a file/link reference, source date and the extracted facts; never rely only on a hand-written summary. When a confirmation is visibly available, capture or export an offline copy before moving on; if original email access is unavailable, ask the user to provide a screenshot, PDF or exported message rather than assuming the details.
- For every reservation, maintain a current effective record and evidence reference: provider, booking ID, traveller/item, price/currency, payment status, cancellation terms, pickup/meeting location and contact where applicable.
- Record the provider's charged amount and original currency as the source of truth. Put any converted budget value beside it with its rate/date/assumption; never replace the original amount with a converted figure or silently mix currencies in a total.
- When new evidence conflicts with the roadbook, reconcile it before updating. Mark the former booking as `superseded` or `cancelled`, retain its evidence and replacement reason, and identify the currently effective provider. Do not silently overwrite a changed booking.
- After any material change, run an impact check across itinerary, costs, routes, navigation directory, reminders and checklists. State what was updated and what remains to confirm.

每封确认邮件、订单 PDF、截图及收据都是证据来源。每项关键预订都保留文件／链接、来源日期和提取出的关键信息，不能只留手工摘要；无法访问原邮件时，应请用户提供截图、PDF 或导出的邮件。每项预订维护一条当前有效记录及其证据引用；信息变更时，先核对再更新，将旧项标为 `superseded` 或 `cancelled`，保留替换原因和证据，禁止静默覆盖。重大变更后，同步核查日程、费用、路线、导航目录、提醒和清单，并说明已更新和待确认项。

## Research and compare｜研究与比较

- Flights: compare direct flights first, then sensible connections. Compare final price including taxes, baggage, seats and promo conditions; assess arrival/departure timing, first-night driving, and return-car/airport buffer. Present recommended, cheapest, and most comfortable choices separately.
- Promotions: before a user pays for a material booking or insurance policy, check the provider's current official promotions and the checkout path. Distinguish a promo/discount-code field from gift-card or voucher redemption. Record the code, eligibility, discount, expiry if stated, and final post-discount price; never assume a search-result code is applied until the checkout total verifies it.
- Hotels: compare like-for-like party size and room needs. Evaluate room-only, breakfast and breakfast+dinner together with child meals, parking, taxes/onsen fees, nearby dinner cost, night driving, payment and free-cancellation deadline. For booked hotels, inventory included and on-site experiences: facility name, season/hours, reservation/cost, age or equipment requirements, weather dependency and whether it should change check-in/out timing. Explain the best-value choice, cheapest option, and experience-led option.
- Activities: use current official sources for seasonal operation, inventory, age/height/supervision, equipment, cancellation and weather constraints. Maintain a confirmed/pending/to-check status.
- Routing: optimize for minimal backtracking and the user's maximum continuous drive. Use real driving segments, parking/rest/meal buffer, and cluster activities. Give each shopping stop a day, time window, purpose, opening-hours check, parking/pick-up notes and fallback; account for tax-free and luggage needs. Prefer a one-stop mall/hotel complex for food, games, shopping and indoor backup unless detouring materially worsens the day.

## Bookings and reminders｜预订与提醒

- Search, compare and prepare forms within scope. The user completes passwords, MFA and CAPTCHA.
- Immediately before submitting a reservation, payment, cancellation, or irreversible change, request explicit confirmation. Record cost, currency, booking ID, payer, payment timing, and free-cancellation cutoff.
- For travel documents and insurance, make a proactive pre-departure tracker rather than waiting for the user to ask: passport/entry authorization or visa and levy where relevant; travel insurance plan, policy number, coverage dates, emergency-assistance contact, medical/cancellation/vehicle-excess limits, exclusions and purchase deadline. Keep these separate from recommendations until application or payment is confirmed.
- For inventory not yet open, create a tracker with official source, expected/opening window, next-check date, checks required, backup and status. Create an automation only with user permission; it reports results and never books or pays automatically.

## Google Maps｜Google 地图

With the user's browser authorization and correct signed-in account: reuse or create a private Saved List named by the user; save places with Day/activity notes if the interface permits; create one Directions link per travel day; and use My Maps only for an overview. Explain that Saved Lists store places, not live routes. Before reordering accounts or signing out all Google accounts, explain impact and get immediate confirmation.

## Deliverables｜交付物

Use the language selected for that trip; the skill is bilingual but output language is not assumed. Every actual stop must include local official name, official local-language full address, searchable English name, postal code, phone, Google Maps link, and—where applicable—reliably sourced Mapcode. Never invent a Mapcode.

- HTML roadbook: daily itinerary, stay, activities (including hotel facilities), shopping windows, longest drive, route buttons, booking status, costs/cancellation, evidence references, weather alternatives and decision branches.
- Optional XLSX: daily itinerary; all-place navigation directory; costs/payment; hotel-and-meal decision record; shopping plan; pending/opening tracker; booking evidence and change log; contacts and pre-departure checklist.
- Keep HTML, mobile site and XLSX in sync whenever a booking, price, route or confirmed activity changes; record the source evidence and impact check for material replacements. Recalculate the aggregate budget immediately after a confirmed payment, retaining an explicit list of excluded, refundable, cancelled and unpriced items.

## Departure-ready presentation｜出发版路书的呈现标准

Use the roadbook as an execution tool, not a transcript of the planning conversation. Separate the **current departure version** from the **evidence/archive record**.

- The current roadbook shows only the effective itinerary, active bookings, actionable deadlines and genuinely useful fallback choices. Do not leave obsolete hotel comparisons, cancelled options, prior route debates, superseded day counts, or the reasoning that led to a settled choice (for example, “four lakefront nights are enough, so no need for another lake stay”) in the main reading flow. Keep that history, when needed for refund or audit, in a linked offline booking/change record.
- Make every travel day a visually distinct, self-contained card or section. It must put the day/date, base hotel, main sequence, booked timed commitments, driving load, food/parking essentials and a concise Plan B together; the reader should not need to cross-reference a separate discussion to execute the day.
- Give each day one representative image of that day's actual signature landscape or experience. Use the image to orient the reader, not as generic decoration; match it to the day's region/activity and provide a clear source/credit where required.
- Show the main plan first. Then list a small set of optional alternatives in explicit recommendation order (for example `P1 最推荐`, `P2 天气好再选`, `P3 室内／体力不足备选`). Do not present a long unranked attraction dump. Include hiking, hotel facilities, shopping or family-friendly activities only on the relevant day and only when they suit the party's time, weather and driving tolerance.
- Keep the daily narrative concise. Include details that change a decision or prevent a real mistake—reservation time, meeting point, parking, driving/boat duration, likely queues, seasonal or holiday closure, weather and cancellation constraint. Omit old deliberations, social-media trivia and repeated generic descriptions.
- In the overview, show a compact route/calendar and a single live “what is booked / what still needs action” panel. In the budget, show an aggregate total, per-person reference when useful, original-currency line items, conversion assumption, paid/on-arrival status, and a short list of excluded or provisional items.
- Provide a visible deadline panel in the HTML/mobile version for cancellation, modification, payment, visa/entry authorization, insurance certificate, activity release dates and refund follow-up. Create calendar/automation reminders only with the user's permission, but always record the deadline in the roadbook.
- Before final delivery, perform a reader test: from the first screen, a family member should be able to identify where they sleep tonight, the next non-negotiable time, where to drive/park, the best backup, and any deadline that could cost money.

出发版不是规划聊天记录：正文只保留当前有效方案、已订项目、需要行动的截止日和少量真正有用的备选；旧酒店比较、取消订单、路线辩论、已被替换的天数，以及“为什么已经住够／不再需要某体验”这类决策推理都进入离线证据／变更记录。每天必须是一张独立可执行卡：日期、住宿、主线、定时预约、车程、餐饮／停车要点和 Plan B 放在一起，并配当天真实特色风景或体验图。备选按推荐优先级列出，不做无排序景点堆砌。总览必须有当前已订／待办、总费用和显眼截止日；交付前从旅客视角检查能否一屏知道今晚住哪、下一项硬约束、怎么到／停车、下雨怎么办和会损失钱的截止日。

## Safety and accuracy｜安全与准确性

Use official sources for time-sensitive facts. State uncertainty. Do not make a purchase, reveal personal data, change account access, or publish/share a private itinerary without the user's specific authorization.
