# DealerDomus

**A dealership management system, built by a dealership manager.**

I run car dealerships. I built DealerDomus to fix the gaps I deal with on the floor every day: leads that slip through the cracks, appraisals priced on gut feel, deals you can't see the gross on until accounting books them, and a GM who needs six systems to answer one question.

It covers the whole store in eight connected modules that share one login and one set of data.

> 🎥 **Walkthrough video:** [DealerDomus-walkthrough.webm](https://github.com/user-attachments/assets/05672069-7d6e-4771-89d4-358f281e40bc)
[README.md](https://github.com/user-attachments/files/33290795/README.md)<img width="1440" height="900" alt="01-sales-pipeline" src="https://github.com/user-attachments/assets/257a9123-1785-48c5-bb22-4d4d710ec507" />
<img width="1440" height="900" alt="14-insight-store-overview" src="https://github.com/user-attachments/assets/22621580-7ee7-49e9-9cf6-adb97ddc6ad1" />
<img width="1440" height="900" alt="05-market-pricing" src="https://github.com/user-attachments/assets/761252d3-4dd9-4322-b53f-f9701dbe725f" />
<img width="390" height="844" alt="18-phone" src="https://github.com/user-attachments/assets/5f8fad64-9f9e-4c2d-8151-50d48ab5119a" />
<img width="1440" height="900" alt="15-insight-fi-summary" src="https://github.com/user-attachments/assets/ef1e460c-9219-417f-bc09-7858749db38f" />
<img width="1440" height="900" alt="10-parts" src="https://github.com/user-attachments/assets/6abba958-f384-480d-86bc-b3caef80a45e" />
<img width="1440" height="900" alt="06-appraisal" src="https://github.com/user-attachments/assets/3f07ebb2-6177-40ff-b36d-97b8d7358f86" />
<img width="1440" height="900" alt="13-recon" src="https://github.com/user-attachments/assets/a231c690-8f4d-4501-8782-2666ec7b9e72" />
<img width="1328" height="347" alt="07-price-to-market" src="https://github.com/user-attachments/assets/4387ce95-332f-499c-840c-2a0a87bfb1b3" />
<img width="1440" height="900" alt="16-insight-heartbeat" src="https://github.com/user-attachments/assets/c55c0333-8047-4aed-bde5-3e4ae67dd9f1" />
<img width="1440" height="900" alt="03-deal-desk" src="https://github.com/user-attachments/assets/b5421e4b-ea8a-401d-9880-bde2810067ae" />
<img width="1440" height="900" alt="09-service-repair-orders" src="https://github.com/user-attachments/assets/c83abf89-05b4-4ff4-bd02-e2eaf6c91404" />
<img width="1328" height="531" alt="08-price-to-market-graph" src="https://github.com/user-attachments/assets/d8bd6f42-69ac-4774-aa6c-de100d5ee74c" />
<img width="1440" height="900" alt="02-customer-page" src="https://github.com/user-attachments/assets/1c0bd562-48d1-4d49-8a51-89520baf5e5e" />
<img width="1440" height="900" alt="11-accounting" src="https://github.com/user-attachments/assets/fb37d7bb-6d11-4bec-a8c8-f6f3ea1061fc" />
<img width="1440" height="900" alt="04-inventory" src="https://github.com/user-attachments/assets/665c0530-aadd-445c-8dd7-9f540ad7cc27" />
<img width="1440" height="900" alt="17-dark-mode" src="https://github.com/user-attachments/assets/d532ffba-c498-4395-aeb3-63ac2769ea43" />
<img width="1440" height="900" alt="12-financial-statement" src="https://github.com/user-attachments/assets/3d72ac26-ea85-4028-b5c3-2d6ee4e9d28a" />

>
> The source code is private. Screenshots show demo data only, with no real customers. Happy to walk through the code in an interview.

![Sales pipeline](01-sales-pipeline.png)

---

## The modules

| Module | What it does |
|---|---|
| **CRM** | Sales pipeline from new lead to delivered, a page per customer, two-way texting and calls, round-robin lead assignment, response-time tracking, duplicate detection, tasks and appointments |
| **Desk** | Deal desking: price, trades, rebates, taxes and fees, F&I products, payments with real amortization, recap, and commissions |
| **Inventory** | Stock, appraisals with VIN decode, and live market pricing: every car against similar cars for sale nearby |
| **Recon** | Reconditioning board in its own tab: every car through each step, time goals, approvals, and days to frontline |
| **Service** | Repair orders, appointments, technician time, and the customer's service history |
| **Parts** | Stock and bins, parts on repair orders, low-stock reorder, counter tickets, and special orders |
| **Accounting** | Double-entry books that post themselves from deals, repair orders, and parts: financial statements, schedules, payables, bank reconciliation, title tracking, and month-end close |
| **Insight** | Manager reports in their own tab: the GM's store overview, sales, F&I, inventory, service and parts, people and goals, and a live "heartbeat" of today's sales floor |

---

## A closer look

### CRM: one page per customer
Road to the sale, every call, text, and note, trades, credit app, and deals in one place.

![Customer page](02-customer-page.png)

### Desk: deal desking
Price, products, taxes and fees, and the payment, with every line itemized.

![Deal desk](03-deal-desk.png)

### Inventory: market pricing
Each car's % of market, its rank among similar cars nearby, and a suggested price from the store's own rules (target %, aging, gross floor).

![Market pricing](05-market-pricing.png)

### Appraisals and price to market
VIN decode, equipment, recon, book values, and an appraisal calculator that works back from the internet price.

![Appraisal](06-appraisal.png)

Drag the pin to set the internet price against the market, or switch to a graph of price against miles. Every dot is a real listing you can click.

![Price to market: bar](07-price-to-market.png)
![Price to market: graph](08-price-to-market-graph.png)

### Recon
![Recon](13-recon.png)

### Service and parts
![Repair orders](09-service-repair-orders.png)
![Parts](10-parts.png)

### Accounting: books that post themselves
Deals, repair orders, and parts post to a double-entry general ledger automatically. Statements by department, month and year to date.

![Accounting overview](11-accounting.png)
![Financial statement](12-financial-statement.png)

### Insight: the numbers the store runs on
![Store overview](14-insight-store-overview.png)
![F&I summary](15-insight-fi-summary.png)
![Heartbeat](16-insight-heartbeat.png)

### Dark mode and phone
<img src="17-dark-mode.png" width="68%"> <img src="18-phone.png" width="22%">

---

## How it's built

- **Backend:** Node.js and Express, PostgreSQL with versioned migrations, a REST API
- **Frontend:** plain JavaScript, HTML, and CSS, no framework, with light and dark themes and phone layouts
- **Integrations:** Twilio (two-way SMS, calls, and call recording), Google Gemini (AI follow-ups and summaries), MarketCheck (market comparables), NHTSA (VIN decode and recalls)
- **Security:** role-based permissions across 10+ roles, an audit log of every change, and encryption of sensitive fields at rest. Social Security numbers are never sent to the AI
- **Quality:** 230+ automated integration tests run against a real database, plus browser checks of every screen
- **Shipped:** 75+ releases, deployed on Render

Built as the sole product owner: I decided what to build from problems I see in real stores, specified and reviewed every feature, and used AI-assisted development to write the code.
