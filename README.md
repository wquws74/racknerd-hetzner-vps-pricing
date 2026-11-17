# RackNerd vs Hetzner: Which Is Cheaper After Hetzner's June Price Hike, Is a $21.99/Year VPS Enough, and When Does Hourly Billing Beat Annual Prepay?

Two prices decide most of this comparison. RackNerd's 1 GB KVM special is **$21.99 per year**. Hetzner's cheapest current cloud plan, CX23, is **€5.49–5.99 per month**, roughly **$72 per year**, and it comes with 4 GB of RAM, 40 GB of NVMe storage and 20 TB of monthly transfer.

So at the entry level, a box that stays on all year and fits inside 1 GB costs about a third as much at RackNerd. Push up to 4 GB and pay RackNerd month by month instead of yearly, and the numbers flip: that plan's monthly list price is $24.59, or about $295 a year, against roughly $72–111 a year for a comparable Hetzner shared plan.

The rest of this page covers what each provider actually charges now, how Hetzner's June price adjustment changed the math, what the benchmark grades say about speed and consistency, and the four situations where the cheap answer is the wrong one.

> **Quick pick:** if your server runs 24/7 and 1–2 GB is enough, take RackNerd's annual special and skip the rest. The 1 GB plan is $21.99/year, the 2 GB is $35.99/year, and the price you sign up at is the price you renew at. 👉 [See the current 1 GB and 2 GB annual specials](https://bit.ly/RacKnerd)

## What RackNerd actually charges

The annual specials page is where RackNerd's pricing advantage lives, and everything on it is billed per year rather than per month.

| Plan | vCPU / RAM | SSD | Monthly transfer | Price | Order |
| --- | --- | --- | --- | --- | --- |
| 1 GB KVM | 1 vCore / 1 GB | 20 GB | 3 TB | **$21.99/year** (~$1.83/mo) | [Order the 1 GB annual plan](https://bit.ly/RacKnerd) |
| 2 GB KVM | 2 vCore / 2 GB | 35 GB | 5 TB | **$35.99/year** (~$3.00/mo) | [Order the 2 GB annual plan](https://bit.ly/RacKnerd) |
| 4 GB KVM | 2 vCore / 4 GB | 60 GB | 7 TB | **$59.99/year** (~$5.00/mo) | [Order the 4 GB annual plan](https://bit.ly/RacKnerd) |
| 6 GB KVM | 6 vCore / 6 GB | 100 GB | 12 TB | **$89.99/year** (~$7.50/mo) | [Order the 6 GB annual plan](https://bit.ly/RacKnerd) |
| 8 GB KVM | 7 vCore / 8 GB | 150 GB | 20 TB | **$119.99/year** (~$10.00/mo) | [Order the 8 GB annual plan](https://bit.ly/RacKnerd) |

Every plan includes a 1 Gbps port, full root access and one IPv4 address. Cors and transfer allowances shift slightly between promo batches, and campaign pricing doesn't sit still, so treat the checkout total as the final word.

RackNerd also runs a separate storefront for time-limited campaigns. The New Year 2026 batch opened at **$11.29/year** for 1 vCPU, 1 GB RAM, 20 GB SSD and 2 TB of transfer, and Black Friday batches have historically landed in the same $10–12 band. That price isn't always on offer. When no campaign is running, $21.99 is the floor for a 1 GB box.

Then there's the monthly list, which is a different product in every practical sense:

| Plan | vCPU / RAM | SSD | Transfer | Price |
| --- | --- | --- | --- | --- |
| 512 MB | 1 vCore / 512 MB | 30 GB | 500 GB | $26.99/year |
| 1 GB | 2 vCore / 1 GB | 50 GB | 1 TB | $17.99/month |
| 2 GB | 3 vCore / 2 GB | 75 GB | 2 TB | $20.59/month |
| 4 GB | 4 vCore / 4 GB | 130 GB | 3 TB | $24.59/month |
| 6 GB | 5 vCore / 6 GB | 170 GB | 4 TB | $27.59/month |
| 8 GB | 6 vCore / 8 GB | 220 GB | 5 TB | $36.59/month |

Read those two tables side by side and the conclusion is blunt. A 1 GB server billed monthly costs $215.88 a year, roughly ten times the annual special for the same RAM. A 4 GB server billed monthly costs $295 a year against $59.99 for the annual special. RackNerd's monthly pricing is competitive with nobody. If you can't commit to a year, the entire reason to pick RackNerd disappears, and Hetzner's hourly billing becomes the better fit.

## Does the price jump at renewal?

Not according to RackNerd. The plan pages show a single price with no separate renewal column, and the FAQ describes the VPS specials as lifetime recurring, renewing at the same rate. That matters more than it sounds: plenty of hosts advertise a $10–12 first year and quietly renew at triple, and this one doesn't.

Two things to know before paying. RackNerd's own knowledgebase answers the refund question directly, stating that per their terms of service there are no refunds and no money-back guarantee. And promo pricing depends on which campaign is live, so the $11.29 entry point may not exist on the day you buy. On a $22 purchase neither point is a dealbreaker, but both argue for deciding before checkout rather than after.

👉 [Lock in the 1 GB annual special at $21.99/year](https://bit.ly/RacKnerd)

## Hetzner's side of the ledger after the June price increase

Hetzner raised prices across its cloud lineup on June 15, 2026. Dedicated-vCPU CCX instances in Germany and Finland went up to 2.1x–2.73x their previous monthly rate. Shared AMD CPX plans rose 2.4x–2.75x. Entry-level CX and ARM-based CAX plans went up around 1.3x–1.4x.

Current plan pricing, for reference (Hetzner prices vary by location and move with the euro):

| Plan | vCPU | RAM | Disk | Price/month |
| --- | --- | --- | --- | --- |
| CX23 | 2 shared | 4 GB | 40 GB NVMe | €5.49–5.99 (~$72/yr) |
| CX33 | 4 shared | 8 GB | 80 GB NVMe | €8.49 (~$111/yr) |
| CX43 | 8 shared | 16 GB | 160 GB NVMe | ~$18.35 |
| CCX13 | 2 dedicated | 8 GB | 80 GB NVMe | €42.99–43.49 (~$562/yr) |

The €5.49 and €5.99 figures for CX23 both appear in current sources, which reflects regional pricing and the exchange rate more than any disagreement about the plan itself.

What Hetzner still does better than RackNerd is billing granularity. You pay by the hour, capped at the monthly maximum, so a CI runner that lives for six hours costs six hours. RackNerd has no hourly option at all: you buy a month or a year, and the clock starts whether the machine is doing work or not.

## The annual cost comparison that actually decides it

| Tier | RackNerd | Hetzner | Who wins |
| --- | --- | --- | --- |
| ~1 GB, 1–2 vCPU | $21.99/year | CX23 ≈ $72/year | RackNerd, by about $50/year |
| ~2 GB, 2 vCPU | $35.99/year | CX23 ≈ $72/year | RackNerd, by about $36/year |
| ~4 GB, 2 vCPU | $59.99/year, or $295/year if billed monthly | CX23 ≈ $72/year | RackNerd on annual, Hetzner by a wide margin on monthly |
| ~8 GB | $119.99/year, or $439/year if billed monthly | CX33 ≈ $111/year; CCX13 ≈ $562/year | A wash against CX33, RackNerd against dedicated vCPU |

The 1 GB and 2 GB rows are not close. Paying $72 a year for a 4 GB Hetzner box is reasonable value, but if a 1 GB box runs your service, you're spending $50 you don't need to.

The 4 GB row is where the popular framing falls apart. RackNerd's annual special at $59.99 undercuts Hetzner's CX23 at roughly $72, though Hetzner gives you NVMe instead of SSD and 20 TB of transfer against 7 TB. Switch RackNerd to monthly billing and the same server costs $295 a year, four times the Hetzner plan. The tier doesn't determine the winner. The billing cycle does.

At 8 GB the two land within $10 of each other on annual terms, and Hetzner's hourly billing, NVMe and snapshot support start to look like the better deal for the same money. RackNerd only pulls ahead again against Hetzner's dedicated-vCPU CCX line, where you're paying $562 a year for guaranteed cores.

## What the benchmark grades show, and where they mislead

VPSBenchmarks tested RackNerd's Ryzen 2 vCores 4GB plan in December 2025 and Hetzner's CX23 in August 2026, grading each on an A-to-F scale:

| Plan | Web performance | Raw CPU | Stability | Disk IO | Network |
| --- | --- | --- | --- | --- | --- |
| RackNerd Ryzen 2c/4GB ($24.59/mo) | **B** | D | D | C | E |
| Hetzner CX23 (€5.99) | F | F | E | D | C |
| Hetzner CCX13 (€43.49) | E | E | E | D | C |

RackNerd posts the best web performance grade in that set, and it isn't close. Its nodes run AMD Ryzen 9 7950X chips, a 16-core desktop part boosting to 5.7 GHz, and for single-threaded work like a WordPress page render or a small API it punches well above its price. Hetzner's CX23 is graded F on web performance and raw CPU, and even the far more expensive CCX13 only manages an E.

The other column is the one that gets skipped. Hetzner scores **71 out of 100** on VPSBenchmarks' consistency measure, which tracks variation between two servers of the same type at the same provider; anything above 65 means performance holds steady across instances. RackNerd has no consistency score at all, because there wasn't enough data to compute one. If you're running one box for yourself, that gap doesn't matter. If you're deploying ten and need them to behave identically, it does.

Network is RackNerd's weak spot in these tests, graded E against Hetzner's C. That's worth weighing if you're serving large files or pushing serious bandwidth rather than running a small site. Provisioning speed differs too: Hetzner averaged 32 seconds from order to ready across the tested instances, RackNerd 110 seconds. Neither is slow enough to plan around.

## What RackNerd doesn't have

RackNerd sells a VPS, not a cloud platform, and the gap shows up in specific missing features. There's no block storage to attach extra volumes, no load balancer, no private networking between your servers, no managed firewall beyond the panel-level rules, no DDoS protection and no REST API, Terraform provider or SDK. Storage is SSD in RAID-10 rather than NVMe, and by one directory's count only 37% of RackNerd's plans sit on NVMe against 100% at Hetzner. Payment is more flexible in one direction: RackNerd takes cryptocurrency alongside cards, PayPal and invoices.

What you do get is KVM virtualisation with full root access, RackNerd's ctrl control panel for reboots, OS reinstalls, an HTML5 VNC console and one-click apps (Docker with Portainer, Coolify, n8n, Ollama and similar), plus instant provisioning and 24/7 support. Free IPv6 is available, up to 100 addresses in the Los Angeles and France locations, but you have to open a support ticket after ordering to request them.

Hetzner, by contrast, has backups, block storage, load balancers, DDoS protection, snapshots, floating IPs, private networks and hourly billing, with a REST API, official Go and Python SDKs, Terraform and Ansible support. If your infrastructure lives in code, that list is the whole argument.

👉 [Compare all of RackNerd's annual VPS specials](https://bit.ly/RacKnerd)

## Locations, latency and compliance

RackNerd colocates in about 20 data centres across 8 countries: the US, Canada, the Netherlands, France, Ireland, the UK, Germany and Singapore. That geographic spread is its second real advantage, and it's the reason someone in Toronto or Strasbourg picks it over a cheaper German host that only operates in Germany and Finland.

Location quality isn't uniform. Los Angeles and New York have the longest track record; some of the secondary sites are more of a coin flip, so pick the region closest to your users and don't expect every city to perform identically. For European users wanting lower latency than Amsterdam, Strasbourg is the usual pick.

Hetzner runs six data centres in four countries: Falkenstein and Nuremberg in Germany, Helsinki in Finland, Hillsboro and Ashburn in the US, and Singapore. Fewer places, but the ones it runs are its own, staffed by its own engineers. Hetzner also publishes ISO/IEC 27001 and BSI C5 certification and is GDPR-compliant, which is the deciding factor for anyone handling EU personal data under a contract. RackNerd sells on price and coverage, not on compliance paperwork.

On uptime guarantees, Hetzner publishes a 99.9% SLA with service credits. RackNerd's position is murkier: third-party directories list 99.9%, and a review of its terms describes a network and power SLA with credits capped at 50% of the monthly fee, but it isn't a per-plan uptime guarantee with payouts the way Hetzner's is. Don't build a business case on it.

## Which one to buy

Four rules cover almost every case:

**A small always-on service that fits in 1–2 GB → RackNerd annual special.** A personal site, a VPN node, a monitoring box, a mail relay, a dev sandbox, a Tor relay. $21.99 or $35.99 a year, renewing at the same rate, is the cheapest legitimate option in this market.

**Anything that starts and stops, or needs infrastructure features → Hetzner.** CI runners, staging environments, Kubernetes nodes, anything you'd provision with Terraform. Hourly billing capped at the monthly maximum, plus snapshots, private networks and an API, are worth more than the annual savings.

**Users in Canada, France, Ireland, the UK or a specific US city Hetzner doesn't cover → RackNerd.** Check the latency from the location you're actually buying before committing a year to it.

**4 GB or 8 GB running long-term → do the arithmetic first.** The 4 GB annual special at $59.99 beats Hetzner's CX23 on price; the same plan on monthly billing at $295 a year loses to it by a factor of four. At 8 GB, RackNerd's $119.99 annual and Hetzner's CX33 at roughly $111 are close enough that NVMe and hourly billing should break the tie.

Before you check out, three things: confirm the plan price on the cart page rather than the marketing page, since campaign pricing changes; pick the data centre nearest your users rather than the default; and remember that free IPv6 in Los Angeles and France requires a support ticket, and that RackNerd doesn't issue refunds.

👉 [Start with RackNerd's 1 GB annual special at $21.99/year](https://bit.ly/RacKnerd)
