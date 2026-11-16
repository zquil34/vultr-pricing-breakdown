# Vultr Pricing: Is the $2.50 Plan Real? Which Tier Do You Actually Need? And What Do Backups, Bandwidth and São Paulo Add to the Bill? (Full Plan Table)

Vultr's pricing page starts at $2.50 a month, and that number comes with two conditions attached: no IPv4 address, and a couple of US locations only. The 512 MB plan you can actually point a domain at is $3.50, the first tier that runs a normal site without gasping is $5 for 1 GB, and the box most small teams settle on is $20 for 4 GB and 2 vCPU. Below is every current list price, plus the line items that decide what you really pay each month: backups, snapshots, bandwidth overage, the São Paulo surcharge, and the fact that Vultr has no refund window at all.

> **Quick picks**
> - First server, small site, cron jobs, a VPN: **$5/mo** (1 GB RAM, 25 GB SSD, 1 TB transfer)
> - App plus database on one box: **$20/mo** (4 GB, 2 vCPU, 80 GB SSD, 3 TB)
> - Need IPv4 on the smallest possible plan: **$3.50/mo**, New Jersey only
> - Single-core speed matters more than RAM: **$6/mo** High Performance or High Frequency, both NVMe
> - Dedicated CPU: **VX1 from $43.80/mo**
>
> 👉 [Check the live price for every Vultr plan](https://www.vultr.com/pricing/?ref=9738262-9J)

## Vultr Cloud Compute prices: all 11 Regular Performance plans

Regular Performance is the entry line, running on shared AMD and Intel vCPUs with standard SSD. Prices are per month, billed hourly with a monthly cap, and the plan cards state the same price on renewal.

| Plan | vCPU / RAM | SSD | Transfer | Price/mo | Order |
| --- | --- | --- | --- | --- | --- |
| 512 MB (IPv6 only) | 1 / 0.5 GB | 10 GB | 500 GB | $2.50 | [Order](https://www.vultr.com/pricing/?ref=9738262-9J) |
| 512 MB | 1 / 0.5 GB | 10 GB | 500 GB | $3.50 | [Order](https://www.vultr.com/pricing/?ref=9738262-9J) |
| 1 GB | 1 / 1 GB | 25 GB | 1 TB | $5.00 | [Order](https://www.vultr.com/pricing/?ref=9738262-9J) |
| 2 GB | 1 / 2 GB | 55 GB | 2 TB | $10.00 | [Order](https://www.vultr.com/pricing/?ref=9738262-9J) |
| 2 GB (2 vCPU) | 2 / 2 GB | 65 GB | 3 TB | $15.00 | [Order](https://www.vultr.com/pricing/?ref=9738262-9J) |
| 4 GB | 2 / 4 GB | 80 GB | 3 TB | $20.00 | [Order](https://www.vultr.com/pricing/?ref=9738262-9J) |
| 8 GB | 4 / 8 GB | 160 GB | 4 TB | $40.00 | [Order](https://www.vultr.com/pricing/?ref=9738262-9J) |
| 16 GB | 6 / 16 GB | 320 GB | 5 TB | $80.00 | [Order](https://www.vultr.com/pricing/?ref=9738262-9J) |
| 32 GB | 8 / 32 GB | 640 GB | 6 TB | $160.00 | [Order](https://www.vultr.com/pricing/?ref=9738262-9J) |
| 64 GB | 16 / 64 GB | 1.3 TB | 10 TB | $320.00 | [Order](https://www.vultr.com/pricing/?ref=9738262-9J) |
| 96 GB | 24 / 96 GB | 1.6 TB | 15 TB | $640.00 | [Order](https://www.vultr.com/pricing/?ref=9738262-9J) |

## High Performance and High Frequency: NVMe for $1 more

The AMD and Intel variants of High Performance are priced identically, so pick whichever is available in the region you want. Both swap the SSD for NVMe and use newer CPU generations.

| Plan | vCPU / RAM | Storage | Transfer | Price/mo | Order |
| --- | --- | --- | --- | --- | --- |
| High Performance 1 GB | 1 / 1 GB | 25 GB NVMe | 2 TB | $6.00 | [Order](https://www.vultr.com/pricing/?ref=9738262-9J) |
| High Performance 2 GB | 1 / 2 GB | 50 GB NVMe | 3 TB | $12.00 | [Order](https://www.vultr.com/pricing/?ref=9738262-9J) |
| High Performance 2 GB (2 vCPU) | 2 / 2 GB | 60 GB NVMe | 4 TB | $18.00 | [Order](https://www.vultr.com/pricing/?ref=9738262-9J) |
| High Performance 4 GB | 2 / 4 GB | 100 GB NVMe | 5 TB | $24.00 | [Order](https://www.vultr.com/pricing/?ref=9738262-9J) |
| High Performance 8 GB | 4 / 8 GB | 180 GB NVMe | 6 TB | $48.00 | [Order](https://www.vultr.com/pricing/?ref=9738262-9J) |
| High Performance 12 GB | 4 / 12 GB | 260 GB NVMe | 7 TB | $72.00 | [Order](https://www.vultr.com/pricing/?ref=9738262-9J) |
| High Performance 16 GB | 8 / 16 GB | 350 GB NVMe | 8 TB | $96.00 | [Order](https://www.vultr.com/pricing/?ref=9738262-9J) |
| High Performance 24 GB | 12 / 24 GB | 500 GB NVMe | 12 TB | $144.00 | [Order](https://www.vultr.com/pricing/?ref=9738262-9J) |
| High Frequency 1 GB | 1 / 1 GB | 32 GB NVMe | 1 TB | $6.00 | [Order](https://www.vultr.com/pricing/?ref=9738262-9J) |
| High Frequency 2 GB | 1 / 2 GB | 64 GB NVMe | 2 TB | $12.00 | [Order](https://www.vultr.com/pricing/?ref=9738262-9J) |

High Frequency uses 3 GHz+ Intel Xeon chips. If your workload is a single-threaded PHP app, a game server or a build runner, the clock speed gain is worth more than an extra gigabyte of RAM, and $6 is the cheapest route to it.

## Optimized Cloud Compute, VX1 and everything else

| Line | Starting price | What it's for | Order |
| --- | --- | --- | --- |
| CPU Optimized | $28/mo | Compute-heavy workloads that don't need much RAM | [Order](https://www.vultr.com/pricing/?ref=9738262-9J) |
| General Purpose | $30/mo | Balanced dedicated-vCPU instances | [Order](https://www.vultr.com/pricing/?ref=9738262-9J) |
| Memory Optimized | $40/mo | Caches, in-memory databases, analytics | [Order](https://www.vultr.com/pricing/?ref=9738262-9J) |
| Storage Optimized | $75/mo | High disk throughput | [Order](https://www.vultr.com/pricing/?ref=9738262-9J) |
| VX1 (dedicated resources) | $43.80/mo | Predictable performance, nested virtualization | [Order](https://www.vultr.com/pricing/?ref=9738262-9J) |
| Cloud GPU A16 16 GB | $344/mo | Small inference, rendering | [Order](https://www.vultr.com/pricing/?ref=9738262-9J) |
| Cloud GPU A16 32 GB | $688/mo | Same, more VRAM | [Order](https://www.vultr.com/pricing/?ref=9738262-9J) |
| Cloud GPU A40 48 GB | $1,250/mo or $1.71/hr | Professional graphics, compute | [Order](https://www.vultr.com/pricing/?ref=9738262-9J) |
| Cloud GPU A100 80 GB | $1,750/mo | Training and large inference | [Order](https://www.vultr.com/pricing/?ref=9738262-9J) |
| Cloud GPU L40S | $1.67/hr for 1 GPU, $13.37/hr for 8 | LLM inference and training | [Order](https://www.vultr.com/pricing/?ref=9738262-9J) |
| Cloud GPU HGX H100 (8 GPUs) | $23.92/hr | Large-scale training | [Order](https://www.vultr.com/pricing/?ref=9738262-9J) |
| Bare metal | from $120/mo | Full hardware, no hypervisor | [Order](https://www.vultr.com/pricing/?ref=9738262-9J) |
| Managed databases | from $15/mo | MySQL, PostgreSQL, Kafka, Valkey | [Order](https://www.vultr.com/pricing/?ref=9738262-9J) |
| Block storage | $0.10/GB/mo, 10 GB min | Extra volumes, triple-replicated | [Order](https://www.vultr.com/pricing/?ref=9738262-9J) |
| Object storage | $0.018/GB/mo standard, $0.050 performance | S3-compatible, 250 GB min | [Order](https://www.vultr.com/pricing/?ref=9738262-9J) |
| Snapshots | $0.05/GB/mo | Compressed image backups | [Order](https://www.vultr.com/pricing/?ref=9738262-9J) |
| DDoS protection | $10/mo | Up to 10 Gbps | [Order](https://www.vultr.com/pricing/?ref=9738262-9J) |

Kubernetes works differently from the rest of this list. Vultr Kubernetes Engine includes the managed control plane free of charge, and you pay only for worker nodes, load balancers and block storage. Worker nodes run on Cloud Compute instances of 2 GB RAM or more, so a cluster has a floor of a few small instances plus whatever the load balancer costs. Older third-party write-ups still quote a $10/mo Kubernetes figure; the current documentation and product page both describe a free control plane.

## What the $2.50 headline leaves out

The 512 MB IPv6-only plan is a real product and it costs $2.50 a month, but it ships without an IPv4 address. If anything needs to reach that server over IPv4, including most legacy clients, some monitoring tools and plenty of corporate networks, you need the $3.50 version instead.

Location is the second catch. The IPv6-only tier is sold in New Jersey and Atlanta. The $3.50 tier with IPv4 is New Jersey only. Neither is available across Vultr's full footprint, so a reader in Frankfurt or Singapore comparing on price alone will find the cheapest tier simply isn't offered where they need it.

Both 512 MB plans are also tight for anything database-backed. A WordPress install with a couple of plugins will spend more time swapping than serving. Practical entry points are 1 GB for a static or lightly dynamic site, 2 GB once a database is involved.

## Hidden costs that don't appear on the plan card

Automatic backups add **20% to the base monthly or hourly fee**, not a flat surcharge. Vultr schedules them automatically and keeps the two most recent copies. On a $20 instance that's $4/mo, so $24 total; on a $160 instance it's $32/mo. Reviewers on G2 occasionally flag backup pricing as steep, and the percentage model is why the cost scales with the instance rather than with how much data you actually store.

Snapshots bill at $0.05/GB/mo based on compressed size and can be restored in any region, which makes them the cheaper tool for one-off images before an upgrade. Bare metal has no snapshot support.

Block storage is $0.10/GB/mo with a 10 GB minimum, replicated three times. Object storage starts at $0.018/GB/mo on the standard tier with a 250 GB minimum and 1 TB of included bandwidth.

Bandwidth overage is $0.01/GB past each instance's allowance, which ranges from 500 GB on the 512 MB plans to 15 TB on the 96 GB plan (the 4 GB instance includes 3 TB). One public IPv4 comes with each instance; additional reserved IPs cost $3/mo.

Windows licences are billed separately from the instance price. DDoS protection is a $10/mo add-on unless you're on a plan that includes it.

Then there's geography: **São Paulo is priced at roughly 1.5× the list price** on many plans. Every other region in the lineup prices the same. If you're deploying for Brazilian users, budget accordingly before comparing Vultr against anything else.

## Hourly billing, the 672-hour cap, and whether renewal costs more

Cloud Compute, Optimized Cloud Compute and bare metal bill by the hour, capped at 672 hours per month. That cap is 28 days, so an instance running continuously never costs more than the monthly price shown on the card. Part-time instances cost the hourly rate multiplied by hours used. The minimum billing unit is one hour, and a stopped instance keeps billing until you destroy it. Suspending a VM to save money doesn't work here.

VX1 is the exception. It bills on actual hours used with no 672-hour cap, which means a 31-day month of 730 hours costs roughly 8–9% more than the $43.80 headline. GPU instances also bill on actual hours (730 in a full month) rather than the capped model.

Renewal pricing is not a trap on this platform. There's no intro rate that jumps in month two, and the plan cards state the same price on renewal. What does change your bill is add-ons, region and usage.

One more thing worth knowing before you enter a card: Vultr's new-account credit is **$300**, and it requires a valid credit card or PayPal account to activate. The unused portion expires after 30 days. There is no free tier and no free trial beyond that credit.

👉 [Activate the $300 credit and see current plan pricing](https://bit.ly/VuLtr)

## What a real monthly bill looks like

Take the most common small-production configuration: 4 GB RAM, 2 vCPU, 80 GB SSD, 3 TB transfer.

| Configuration | Monthly |
| --- | --- |
| Vultr Regular 4 GB, no backups | $20.00 |
| Vultr Regular 4 GB with automatic backups (+20%) | $24.00 |
| DigitalOcean Basic Droplet, 4 GB / 2 vCPU, no backups | $24.00 |
| DigitalOcean same droplet with backups (+20%) | $28.80 |

Vultr is $4/mo cheaper at the same spec before backups and $4.80/mo cheaper after, which is $57.60 a year. That gap is real but it isn't the whole story: the two providers include different storage and transfer allowances, so a workload that burns bandwidth can close or invert the difference. Compare the allowance, not just the sticker.

For context on where that sits in the market, the median unmanaged plan tracked across providers is about $21.99/mo, and Vultr's $3.50 tier ranks among the 22 cheapest of 565 plans in that index. Five of the eight Vultr plans in the same index price below the median.

If you'd rather not run the server yourself but want Vultr's network, Cloudways offers Vultr as one of its underlying clouds alongside DigitalOcean, Linode, AWS and Google Cloud, with an NGINX stack, Redis, a firewall, automated backups and 24/7 support, starting around $14/mo on its default listing. That's a managed layer on top, not a Vultr product, and it costs more than doing it yourself.

👉 [Compare Vultr's 4 GB plan against the current price list](https://www.vultr.com/pricing/?ref=9738262-9J)

## Which plan fits your workload

**Personal project, test box, VPN, bot.** The $3.50 plan with IPv4 if New Jersey works for you, otherwise $5 for 1 GB in any region. The extra $1.50 buys 15 GB more disk, double the RAM and double the transfer, which is better value than most upgrades on this list.

**A small production site or API.** $10 for 2 GB handles a low-traffic site with a database. Move to $20 for 4 GB once you're running an app server and a database together, or once you need headroom for deploys and backups happening on the same box.

**Anything where request latency is the bottleneck.** $6 High Performance or High Frequency. NVMe and newer CPUs matter more than the RAM difference at this tier. Public benchmark runs on Vultr plans put the strongest single-core Geekbench 6 score at 1,073 on the Regular 2 GB, which is respectable for shared silicon but not what you want behind a latency-sensitive API.

**Dedicated CPU without bare metal prices.** VX1 from $43.80/mo, and it's the only line where nested virtualization is documented. If you plan to run Docker with KVM inside, or a nested hypervisor, this is the tier to look at.

**Kubernetes.** Free control plane, pay for workers at Cloud Compute rates. Size the workers with 2 GB minimum and remember the load balancer bills separately from the nodes.

**GPU work.** A16 at $344/mo is the entry point for small inference or rendering. L40S at $1.67/hr suits LLM inference where you want to pay by the hour. H100 clusters at $23.92/hr are for training runs that justify the invoice.

## When Vultr is the wrong buy

Vultr sells infrastructure, not hosting. You get a server with a root login, a control panel, an API and a firewall. You install the stack, configure TLS, set up backups and apply security updates yourself. Support runs on tickets, and the documentation library is thinner than what the larger clouds publish. If a kernel panic, a broken PHP upgrade or a hacked WordPress install is something you'd want a human to fix for you, this is the wrong product.

Managed WordPress, WooCommerce and agency-style hosting are better served elsewhere. Cloudways running on Vultr is the closest middle path if you like the regions and want someone else handling the stack. A managed VPS with phone support and a money-back guarantee costs more per month but removes the operational work entirely.

The other case to think twice: large bare metal or GPU fleets. Cost complaints in user reviews cluster around backups and around GPU and bare metal pricing at scale, not around the small instances.

## FAQ

**Does Vultr have a free trial or a free plan?**
No free tier and no trial period. New accounts can get $300 in credit after linking a valid card or PayPal, and whatever isn't used within 30 days expires.

**Can I get a refund if I don't like it?**
There's no money-back window. Because billing is hourly, cancelling stops future charges and you pay for the hours already used. Destroy the instance, don't just power it off, or it keeps billing.

**Is the $2.50 plan actually usable?**
It's a real 1 vCPU, 512 MB, 10 GB SSD instance with 500 GB of transfer. It has no IPv4 address and is limited to a couple of US locations, so it suits IPv6-only experiments and not much else.

**Will the price go up when I renew?**
Not on the plan itself. Vultr doesn't use intro pricing, and the plan cards list the same price on renewal. Your bill changes with add-ons, overage and region.

**Which location is cheapest?**
Every region prices the same except São Paulo, which runs about 1.5× the list price.

**How much do backups cost?**
20% on top of the instance fee, monthly or hourly, with the two most recent backups retained. Snapshots are a separate product at $0.05/GB/mo.

## Before you order

Match the plan to the job and nothing else:

- One small server, nothing critical: $5
- A real site with a database: $20
- Single-core performance is the constraint: $6 High Performance
- You need guaranteed CPU: VX1 at $43.80
- You don't want to administer Linux: skip Vultr entirely

Three things to confirm at checkout. Whether you need IPv4, because the $2.50 tier doesn't have one. Whether automatic backups should be on, because it changes the price by 20% and it's easier to enable at deploy time than to retrofit. And whether your region is São Paulo, because the multiplier applies before any of the numbers above.

👉 [Start with the $300 credit and pick your plan](https://bit.ly/VuLtr)
