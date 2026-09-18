# white label conversational ai: how agencies rebrand and rebill AI agents without owning the tech stack

Most people typing "white label conversational ai" into Google are not shopping for a chatbot. They are agencies trying to answer a narrower, more commercial question: can I sell AI lead qualification to clients under my own brand, keep the margin, and never mention the vendor?

That question has two halves. The branding half is the easy part. The billing half is where most platforms quietly fall apart, because removing a "Powered by" badge does not mean you get to set client prices, invoice through the tool, or keep the spread between what you charge and what the AI actually costs you.

CloseBot sits on the agency side of that line. It is a conversational AI built for appointment setting inside a CRM, and its Agency plan exists specifically so an agency can white label the client experience and rebill every cost underneath it. Here is how the pieces actually fit together, what the plans cost, and where this approach stops making sense.

## White label is four different things, and vendors blur them

A useful way to audit any platform in this category is to check which level it reaches.

1. **Badge removal.** The chat widget stops advertising the vendor. Cheap, common, and almost worthless on its own.
2. **Branded deployment.** Your logo, your colors, your domain on the client-facing side.
3. **Branded client platform.** Clients log in under your brand and see their own data, not yours.
4. **Full reseller setup.** You control client accounts, markups and billing, and the vendor's cost passes through you rather than landing on the client's card.

Plenty of tools stop at level one and call it white label. CloseBot's Agency plan targets level four, and the pricing model is the evidence: agencies pay a flat rate per message and bill clients whatever they want on top.

## CloseBot's white label lives on the Agency plan

The white label client portal is not a $99 add-on bolted to a business plan. It is part of the Agency track, and CloseBot's own FAQ is blunt about it: a Business plan does not give you the re-billing and white labeling view, even during the 7-day agency trial.

On an Agency account you get:

- A white-labeled client portal running on the domain of your choice, with your colors and logo
- Re-billing on four separate cost categories: user seats, knowledge library storage, message volume, and AI provider token costs
- One dashboard showing revenue earned per category, plus per-client breakdowns
- Agent ownership staying with you, the agency

That last point is a design decision worth understanding rather than just reading as a feature. In CloseBot V2, only you and your team build and edit agents. Clients log in, fill in variables you predefined, and upload content to their knowledge base. A gym client fills in its amenities and services; it does not get to restructure the conversation logic and break it at 11pm on a Friday.

CloseBot says it moved this way after polling top resellers and reviewing usage data, and it markets the change as protecting the agency relationship rather than competing with it. Read cynically or not, the effect is the same: the client churns less when they cannot break the thing.

👉 [See how the Agency plan handles white label and rebilling](https://app.closebot.com/a?fpr=li87)

## Every CloseBot plan, side by side

Prices below are the ones currently listed on CloseBot's official plans page, month to month, with the annual figures the same page displays. Nothing here is a limited-time promotion.

| Plan | Who it's for | Core configuration | Price | Billing cycle | Get started |
| --- | --- | --- | --- | --- | --- |
| **Free** | Testing the builder, low lead volume | 1 agent, 100 monthly messages, 1 user seat, 1 MB upload storage, unlimited account connections | $0 | Always free | [Start on the free plan](https://app.closebot.com/a?fpr=li87) |
| **Core (Business)** | Companies running AI on their own pipeline | Message allowance scales from the base tier upward; 15+ templates (50+ on annual), human support, 1 seat included at $5 per extra seat, add-on storage and agents | From $64/mo; $53/mo equivalent on annual billing, shown as $640/yr on the entry tier | Monthly or annual, no contract | [Compare Core business pricing](https://app.closebot.com/a?fpr=li87) |
| **Agency** | Agencies selling AI setting to clients under their own brand | White label client portal, rebill on seats, storage, messages and tokens, unlimited agents for client accounts, 15+ templates, human support | $397/mo monthly; roughly $331/mo equivalent on annual billing | Monthly or annual, no contract | [Start the Agency plan trial](https://app.closebot.com/a?fpr=li87) |
| **Growth** | Teams needing SLAs, compliance paperwork, or heavy volume | HIPAA compliant, quarterly audits, 99.99% priority uptime, priority support, 50+ templates, custom terms | Custom | Custom | [Request Growth pricing](https://app.closebot.com/a?fpr=li87) |

Two things the table flattens. First, the Core and Agency tracks share a message-volume slider that runs from 100 up to 100K+ replies per month, so the $64 figure is a starting point rather than a fixed price. Second, if you are on the V1 documentation rather than the current plans page, you will see the older job-flow structure — $64/month for 1 job flow, $197 for 3, $297 for 10, $397 for unlimited — which no longer matches how the plans page presents Core.

### What the Core track costs as volume climbs

CloseBot does not publish a static price sheet for every volume tier, but independent reviews that checked the plans page in August 2026 recorded these monthly figures on the business side:

| Messages included | Recorded Core price (monthly billing) |
| --- | --- |
| 100–500 | $64/mo |
| 1,000 | $84/mo |
| 2,000 | $109/mo |
| 5,000 | $176/mo |
| 20,000 | $454/mo |
| 50,000 | $806/mo |
| 100,000 | Roughly $1,059/mo |

Treat those as directional rather than contractual — use the slider on CloseBot's own plans page to confirm your tier. What matters for planning is the shape of the curve: business plans bundle message costs into the base price, and overage beyond your ceiling is charged at a 2x rate drawn from a wallet you top up.

## The rebilling math that decides whether the Agency plan pays for itself

On the Agency plan, CloseBot charges a flat **$0.012 per message**, and you can rebill that at any markup. Storage runs at $0.006 per MB per day. Additional seats cost $5 each and can also be marked up. Token costs from your AI provider are tracked for you and can be rebilled on top.

A simple version: 5,000 client messages in a month costs you about $60 in message fees. If your client package is priced at the $500/month figure CloseBot cites from its own poll of agencies, the platform fee and usage are covered well before the invoice gets uncomfortable. CloseBot's pricing page also states that some agencies bill as little as $100/month per client while others report $10k+ monthly from a single account — a range wide enough to tell you the pricing decision is yours, not theirs.

The point of the model is that your margin scales with usage instead of shrinking as clients grow. That is a different financial shape from platforms where you pay a fixed reseller subscription and then absorb usage costs out of pocket.

One calculation people get wrong: a "message" equals one segment, unless you switch on the Agent Node with unlimited potential (many tools, unlimited instruction size), where billing shifts to token costs and a single reply can consume several segments. Budget conservatively if you plan to build heavy agents with lots of tools.

## What the client actually sees

The client portal is the part your client judges you on, so specifics matter more than the word "white label."

Clients log in through your domain, with your branding, and land on a dashboard showing their agent's performance — responses, interactions, bookings — plus their own usage costs. CloseBot deliberately gives the client different KPIs from the agency dashboard, on the reasoning that clients care about throughput and outcomes, not your revenue breakdown.

They can fill in the variables you defined, upload knowledge base documents, and that is roughly the extent of their control. All of it stays inside your Stripe-connected billing flow: clients pay you, you pay CloseBot.

If you want to see where the branding appears — widget, login page, dashboard, domain, invoices — dig through those surfaces before you sell the service. That is the check that separates a real white label setup from a cosmetic one.

## Where this approach stops being right

CloseBot is text-only. SMS, web chat, WhatsApp, Instagram DM, Facebook Messenger, email — the channels that live inside your CRM. It does not make phone calls, and CloseBot's own positioning recommends pairing it with a separate voice AI product rather than pretending otherwise. If your clients expect inbound calls answered, you are buying two systems.

It also, in practice, wants a CRM underneath it. CloseBot integrates natively with HighLevel and HubSpot and supports custom CRM setups, and it answers conversations flowing through those inboxes. CloseBot lists standalone compatibility in its own comparison table, but if your leads live entirely in Instagram DMs with no CRM anywhere, you are adding a CRM subscription plus a CloseBot subscription to solve a problem a channel-native tool might handle alone.

Three more things to know before you commit:

- No bring-your-own API key. CloseBot frames this as a security decision, so you cannot swap in your own OpenAI or Anthropic key to shave model spend.
- No refunds. You get a free-forever plan under 100 messages a month and a 7-day trial on any paid plan. Use the trial as the actual test, because there is no money-back exit afterward.
- Clients cannot build agents. If a prospect insists on owning their own build, the far better commercial outcome for you is pointing them at a Business account.

## How it compares to other white label platforms

Public list prices for the platforms agencies most often shortlist against CloseBot, checked against vendor pages in mid-September 2026:

| Platform | Entry price for reseller features | White label depth |
| --- | --- | --- |
| Stammer | $197/mo agency plan; $497/mo full SaaS mode | Full reseller, per-client wallets, chat and voice |
| Lety | $97/mo Starter (2 client subaccounts), $297 Standard, $497 Unlimited | Branded portal on paid plans |
| Social Intents | $299/mo, 10 client subaccounts included | Branded portal, strong on live chat and support |
| UChat | $199/mo partner plan plus roughly $10 per client license | White label across dashboard, login, mobile apps |
| Botpress | $89/mo Plus, or $79/mo annual | Webchat only — Studio and Dashboard cannot be white labeled |
| Chatbase | $99/mo branding add-on | Brand removal; client billing stays your problem |
| CloseBot | Free tier; Agency plan at $397/mo with $0.012 per rebillable message | Branded client portal plus four-category rebilling |

The pattern worth noticing: platforms with per-client licensing get expensive as your client count grows, while platforms with per-message rebilling get expensive as usage grows. CloseBot is in the second camp, and it is cheaper than most of the field at low-to-moderate message volumes because the Agency plan is flat and the usage pass-through is transparent.

Also worth flagging honestly: on G2, reviewer summaries highlight ease of use and fast setup as the recurring praise, while the same pros-and-cons page records complaints about limited bot functionality and occasional speed issues. CloseBot has publicly cited 14 G2 awards including a "Most Reliable AI Agent Builder" badge. Read vendor award claims as marketing, and read the complaint column as the useful part.

## Picking a plan without overbuying

- **Under 100 messages a month:** stay on Free. It costs nothing forever and includes unlimited account connections, which is enough to build and test a first agent.
- **You are running your own pipeline, not reselling:** Core. White label features would be dead weight, and the Business plan is the same agent, channels and integrations pointed at your leads instead of a client's.
- **You are selling AI setting as a service:** Agency, on the 7-day trial, before you quote a single client. The white label portal and rebilling view only exist here.
- **You need HIPAA paperwork, SLAs, or quarterly audits:** Growth, custom quoted. If a healthcare or dental client asks for compliance documentation, this is the tier that answers.

One habit worth building before you sign anything: model the total cost per client including the CRM underneath. GoHighLevel starts around $97/month for its entry tier, which means a small client running 1,000 AI messages a month sits somewhere near $180/month all-in before WhatsApp or SMS fees. The Agency plan is not the expensive part of that stack — but it is also not the only line item.

## The realistic setup path

1. Create a free account and build your first agent with the drag-and-drop builder. CloseBot documents a 48-second initial setup and claims most teams take a first agent live the same day.
2. Run conversations through the testing portal before anything touches a real lead. Test the objection handling, not just the happy path.
3. Connect your CRM — HighLevel, HubSpot, or a custom stack — and map qualification answers to custom fields.
4. Create the variables clients will fill in, so one agent serves many accounts in the same niche.
5. Turn on the white label portal: domain, colors, logo.
6. Enable rebilling and set your markups on messages, seats, and storage.
7. Keep Smart FAQ switched on. When an agent cannot answer confidently, it flags you instead of inventing a discount your client does not offer, then re-engages every lead who asked once you answer.

That last feature matters more than its position on the list suggests. A hallucinated offer is the fastest way to lose a client relationship you spent months building.

## FAQ

**Does CloseBot offer white labeling?** Yes, on the Agency plan. The client portal runs on your domain with your branding, and rebilling is available across seats, storage, messages, and tokens. Business plans do not include the white label or rebilling view.

**Can I rebill clients at my own markup?** Yes. You are billed $0.012 per message on the Agency plan and set whatever markup you want when billing clients through your Stripe connection.

**Is there a free trial?** There is a free-forever plan under 100 messages a month, plus a 7-day trial of any paid plan, including Agency. CloseBot states plainly that there are no refunds after that.

**Does CloseBot handle phone calls?** No. It covers text channels inside your CRM. Voice requires a separate product.

**How many languages?** CloseBot states 40+ and counting, tied to the underlying models it uses.

**Does my client need their own CloseBot account?** No. They log into your white-labeled portal. If they eventually want full control to build their own agents, they would need a Business account — which can be set up through your affiliate link so you still benefit.

👉 [Open a free CloseBot account and build your first white label agent](https://app.closebot.com/a?fpr=li87)

The short version: if your agency already sells lead qualification and lives in a CRM, CloseBot's Agency plan gives you the branding, the portal, and the billing plumbing to sell conversational AI as your own product. If your clients only ever message you on Instagram and no CRM exists, you would be buying a platform to solve a problem it was not built to solve — and the honest answer is to look at a channel-native tool instead.
