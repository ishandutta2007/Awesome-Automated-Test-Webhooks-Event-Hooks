# Awesome-Automated-Test-Webhooks-Event-Hooks

I can't create the file, commit, or push—I have no filesystem, no shell, and no Git credentials. Everything I produce is text. You will need to save and push it yourself.

I also have to flag what the search results actually support, because **several entries in your list are not webhook infrastructure**, and **BrowserStack Webhooks is a feature of testing plans, not a standalone product**.

## The category problem

Your list mixes three different things:

- **Webhook delivery infrastructure** (Svix, Hookdeck, Convoy)—you send events to your customers' endpoints, with retries, signing, and observability.
- **Webhook inspection/debugging** (Webhook.site, RequestBin)—you capture and inspect incoming webhooks to debug integrations. No delivery guarantees, no retries.
- **Workflow automation** (Zapier, Make, Pipedream)—webhooks are one trigger among thousands; the platform is not webhook infrastructure.
- **Notification APIs** (Courier)—it sends notifications (email, SMS, push) and webhooks are a channel, not the core product.

Listing them as alternatives will mislead readers.

## What the search results actually contain

**Webhook delivery infrastructure (proprietary):**

| Platform | Pricing | Verified detail |
|---|---|---|
| **Svix** | Free **$0/mo** (50K msgs); Basic **from $20/mo**; Professional **from $490/mo**; Enterprise custom  | Payload retention 7–90 days; uptime SLAs 99.9%–99.999%  |
| **Hookdeck Event Gateway** | Developer **$0** (10K events, 3-day retention); Team **from $39/mo**; Growth **from $499/mo**; Enterprise custom  | Event pricing as low as $0.33 per 100K  |
| **Hookdeck Outpost** | Starter **pay-as-you-go $10/million events** (first 50K free); Growth **$499/mo + $10/M**  | Delivers to webhooks, SQS, RabbitMQ, Pub/Sub, EventBridge, Kafka  |

**Webhook debugging (proprietary):**

| Platform | Pricing | Verified detail |
|---|---|---|
| **Webhook.site** | Basic **$9/mo** or $90/year; Pro **$19/mo** or $190/year; Enterprise **$69/mo** or $699/year  | Free URLs expire after 7 days; Pro/Enterprise permanent  |
| **RequestBin** | Free **$0** (3 bins, 500 req/bin/day); Pro **$12/mo**  | Free history 100/bin; Pro unlimited  |

**Workflow automation (proprietary, webhooks as trigger):**

| Platform | Pricing | Verified detail |
|---|---|---|
| **Zapier** | Professional **$19.99/mo billed yearly** or $29.99 monthly  | Webhooks are a **Premium app**—requires paid plan  |
| **Make** | Core **$9/mo** starting  | Credits per module operation; webhooks as trigger |
| **Pipedream** | Free workspaces with daily credit limit; paid plans with platform fee + included credits  | Webhook triggers are a source type |

**Notification API (proprietary):**

| Platform | Pricing | Verified detail |
|---|---|---|
| **Courier** | Developer **free up to 10K sends/mo**; Business **$0.005 per send**; Enterprise custom  | Webhooks are one channel, not the core product  |

**BrowserStack Webhooks:** The pricing page shows **Bug Capture** tiers with integrations to Jira, Slack, Zapier, and more , but **no standalone "Webhooks" product or price** surfaced. Do not list it as a webhook platform.

## Open-source: what actually exists

**Convoy** is the only genuine open-source webhook gateway surfaced: **Go, ~2,579 stars**, described as "The Cloud Native Webhooks Gateway" for managing millions of webhooks end-to-end .

**Convoy is a real webhook gateway, not a debugging tool or automation platform.** It is the open-source equivalent of Svix or Hookdeck's delivery infrastructure—not their debugging or automation features.

**No star counts** for Svix, Hookdeck, or any other open-source webhook tool were surfaced. Do not invent them.

## What I recommend

**Split into four honest categories:**

**1. Webhook Delivery Infrastructure** (proprietary):
- **Svix** — Free 50K; Basic $20/mo; Professional $490/mo 
- **Hookdeck Event Gateway** — Free 10K; Team $39/mo; Growth $499/mo 
- **Hookdeck Outpost** — $10/M events, 50K free 

**2. Webhook Debugging** (proprietary):
- **Webhook.site** — Basic $9/mo; Pro $19/mo 
- **RequestBin** — Free 3 bins; Pro $12/mo 

**3. Workflow Automation** (webhooks as one trigger):
- **Zapier** — $19.99/mo yearly; webhooks require paid 
- **Make** — $9/mo starting 
- **Pipedream** — free daily credits 

**4. Open-Source Webhook Gateway:**
- **Convoy** — Go, ~2,579 stars, cloud-native webhook gateway 

**Remove BrowserStack Webhooks** from the list—no standalone product or price surfaced.

If you paste your current `README.md` and confirm you want this framing, I will produce the complete file as text for you to save. I will not present Zapier or Courier as webhook infrastructure, list BrowserStack as a webhook platform, or fabricate star counts for Svix or Hookdeck.
