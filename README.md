# asocks pricing: What $3/GB Really Costs, When a Per-IP Plan Is Cheaper, and How to Compare Both

Search for "asocks pricing" and almost every page hands you the same single number: $3 per GB. That number is real, and it's also only part of the picture. ASocks bills in three different ways depending on which proxy type you choose, and once you're past the entry tier the arithmetic stops looking like a flat rate at all.

This is a breakdown of what ASocks actually charges, what extra charges sit outside the headline number, and how a different billing model — paying per IP with unlimited bandwidth instead of per gigabyte — can cut the bill considerably on certain workloads.

## ASocks pricing is really three separate rate cards

The flat $3/GB rate applies to pay-as-you-go traffic on residential and mobile proxies. There's no monthly subscription attached to it, and by most accounts the traffic balance doesn't expire. You top up, you burn it when you need it.

But ASocks also sells dedicated proxy access on a monthly per-proxy basis, and those rates are much higher than the per-GB entry point suggests. Here's the full set of rates that are publicly documented across ASocks' own comparison page and third-party comparisons:

| Plan type | Rate | How it's billed | Notes |
| --- | --- | --- | --- |
| Residential, GB-based | $3.00/GB | Pay as you go, no monthly fee | Traffic balance reported as non-expiring |
| Mobile, GB-based | $3.00/GB | Pay as you go | Same rate as residential |
| Residential, dedicated | $5 per proxy/month | Monthly, per proxy | Unlimited traffic |
| Mobile, dedicated | $15 per proxy/month | Monthly, per proxy | Unlimited traffic |
| Datacenter / corporate IP | $5 per proxy/month | Monthly, per proxy | Unlimited traffic |
| City & ASN targeting | Charged on top | Add-on | ASocks' comparison page flags this as extra cost, with a doubled rate shown on some rows |

Two things stand out here. First, the GB model is genuinely flat: ASocks' own comparison table shows $150 buying 50 GB, $500 buying 167 GB and $1,000 buying 333 GB — which works out to roughly $3/GB at every level. There is no volume discount hiding behind a "contact sales" button on the traffic side. If your plan is simply to consume a few hundred gigs a month, the price per gig doesn't improve as you spend more.

Second, mobile traffic costs the same as residential under the pay-as-you-go model. That's unusual — most providers price mobile IPs well above residential because mobile carrier bandwidth is more expensive to source. Reviewers have questioned the parity, and it's worth testing with a small top-up before you move a large mobile workload onto it.

<aside>
The per-proxy monthly rates ($5 residential, $15 mobile, $5 datacenter) come from third-party comparisons rather than a single canonical ASocks page, and ASocks has changed its page structure more than once. Treat them as directional and confirm the current figure in your dashboard before planning a budget around them.
</aside>

## What sits outside the headline rate

City-level targeting and ASN targeting are the two features most likely to move your real cost. ASocks' own comparison page lists city and ASN targeting as costing extra, with the rate doubling on some line items. That matters if your work depends on hitting a specific ISP or a specific metro rather than just a country. Standard country-level rotation stays within the $3/GB structure; the moment you narrow down to a city or an ASN, the effective rate per gig can change.

Free trials are handled through promotional codes distributed to partner platforms rather than a self-serve trial button. Several browser-automation and antidetect vendors publish codes that grant a few gigabytes free for new accounts, and those codes rotate as partner programs change. So the honest answer to "is there an ASocks free trial" is: usually yes, but the code lives on a partner's page, not on the pricing page.

Pool size is the other constraint worth knowing about before you buy. ASocks is consistently reported at around 7 million residential and mobile IPs across 150-plus countries. That's a real pool, but it's smaller than the large incumbents, and it's a fraction of what the biggest networks advertise.

## Running the numbers on a normal workload

Pricing tables are abstract until you attach them to a use case. Three quick scenarios:

**100 GB of rotating residential traffic per month.** At $3/GB that's $300 a month, every month, with no discount for consistency. Over a year: $3,600.

**100 stable residential IPs, unlimited traffic each.** On the dedicated plan listed above at $5 per proxy per month, that's $500 a month. The same job under a per-IP model that charges for the IP rather than the bandwidth is where things get interesting.

**1,000 GB of bandwidth-heavy scraping.** $3,000 at the flat rate. Most providers start discounting hard somewhere between 500 GB and 1 TB. ASocks, based on its own comparison figures, does not.

If your workload looks like the second scenario — a stack of browser profiles, accounts that need to hold a stable IP, or long sessions where traffic is unpredictable — you're paying for gigabytes you may never consume. Which is exactly the gap a per-IP model is built to fill.

## 9Proxy's pricing: pay per IP, or pay per GB

9Proxy runs two residential models side by side, and the per-IP one inverts the logic above. You buy a number of IPs; bandwidth through those IPs is unlimited while they're active. IPs stay in your account until you use them, so a package bought for one campaign can still be sitting there months later.

The other model bills bandwidth instead: you buy a GB package, generate as many endpoints as you like from it, and rotate freely across the pool. Packages come with 180-day validity, with enterprise tiers dropping the expiry entirely. Coverage is 20 million-plus residential IPs across 90-plus countries, with targeting down to country, state, city and ISP, and authentication by username/password or IP whitelisting.

One piece of housekeeping: 9Proxy adjusted its IP-based and bundle pricing on 1 June 2026 — its first price change since launch — while leaving GB packages untouched. The tables below reflect the post-adjustment numbers.

### IP-based packages (unlimited bandwidth per IP)

| Package | Price per IP | Total | Buy |
| --- | --- | --- | --- |
| 100 IPs | $0.24 | $24 | [ Check the 100-IP package](https://bit.ly/9-Proxy) |
| 500 IPs | $0.144 | $72 | [ See the 500-IP package](https://bit.ly/9-Proxy) |
| 1,000 IPs + 500 bonus | $0.084 | $126 | [ Get the 1,500-IP deal](https://bit.ly/9-Proxy) |
| 2,500 IPs | $0.084 | $210 | [ View the 2,500-IP package](https://bit.ly/9-Proxy) |
| 5,000 IPs | $0.072 | $360 | [ Check the 5,000-IP package](https://bit.ly/9-Proxy) |
| 15,000 IPs | $0.048 | $720 | [ See the 15,000-IP package](https://bit.ly/9-Proxy) |
| 25,000 IPs | $0.035 | $863 | [ View the 25,000-IP package](https://bit.ly/9-Proxy) |
| 50,000 IPs | $0.029 | $1,438 | [ Check the 50,000-IP package](https://bit.ly/9-Proxy) |
| 100,000 IPs (Business) | $0.023 | $2,300 | [ See Business IP packages](https://bit.ly/9-Proxy) |
| 200,000 IPs (Business) | $0.021 | $4,140 | [ Check Business 200k IPs](https://bit.ly/9-Proxy) |
| 500,000 IPs (Business) | $0.018 | $8,625 | [ View Business 500k IPs](https://bit.ly/9-Proxy) |

Read that against the ASocks dedicated-proxy rate and the gap is not subtle. 100 stable IPs with unlimited bandwidth costs $24 here versus roughly $500 on a $5-per-proxy monthly plan. Even the largest ASocks dedicated line, at $15 per mobile proxy per month, is 60 times the per-IP cost at the entry tier.

What you're actually buying differs, of course. 9Proxy IPs sit in your balance until used rather than being guaranteed for a fixed contract period, and an individual IP lives anywhere from a few hours to about 24 hours before it rotates naturally. That's fine for session-based work, account management and profile separation — less fine if you expected a permanent static address.

### GB-based packages (180-day validity)

| Package | Price per GB | Total | Validity | Buy |
| --- | --- | --- | --- | --- |
| 5 GB | $3.00 | $15 | 180 days | [ Start with 5 GB](https://bit.ly/9-Proxy) |
| 50 GB + 5 GB bonus | $2.10 | $105 | 180 days | [ Grab the 55 GB package](https://bit.ly/9-Proxy) |
| 100 GB | $1.50 | $150 | 180 days | [ Check the 100 GB package](https://bit.ly/9-Proxy) |
| 200 GB | $1.00 | $200 | 180 days | [ See the 200 GB package](https://bit.ly/9-Proxy) |
| 1,000 GB | $0.80 | $800 | 180 days | [ View the 1,000 GB package](https://bit.ly/9-Proxy) |
| 2,000 GB | $0.75 | $1,500 | 180 days | [ Check the 2,000 GB package](https://bit.ly/9-Proxy) |
| 3,000 GB (Enterprise) | $0.72 | $2,160 | No expiry | [ See Enterprise 3,000 GB](https://bit.ly/9-Proxy) |
| 6,000 GB (Enterprise) | $0.70 | $4,200 | No expiry | [ View Enterprise 6,000 GB](https://bit.ly/9-Proxy) |
| 10,000 GB (Enterprise) | $0.68 | $6,800 | No expiry | [ Check Enterprise 10,000 GB](https://bit.ly/9-Proxy) |

The volume curve here is the opposite of ASocks'. The 5 GB pack matches ASocks at $3.00/GB, then it slides steadily: $1.50 at 100 GB, $1.00 at 200 GB, $0.80 at 1,000 GB, $0.68 at 10,000 GB. If you're moving a high-volume scraping or monitoring workload, the same 1,000 GB that costs $3,000 on a flat $3/GB rate costs $800 here.

### Bundle packages (IPs plus bandwidth)

| Bundle | Contents | Price | Buy |
| --- | --- | --- | --- |
| Starter | 100 IPs + 5 GB | $30 | [ Get the Starter bundle](https://bit.ly/9-Proxy) |
| Popular | 1,500 IPs + 50 GB | $180 | [ Check the Popular bundle](https://bit.ly/9-Proxy) |
| Pro | 5,000 IPs + 500 GB | $720 | [ See the Pro bundle](https://bit.ly/9-Proxy) |

Bundles suit mixed workloads where some tasks need to sit on a stable IP while others just need throughput. Bundled traffic carries the same 180-day validity.

## So which one costs less for your job

Strip away the marketing and the decision comes down to what your workload is actually shaped like.

**Per-IP wins when sessions matter more than volume.** Account management, profile separation, ad verification from fixed locations, anything where one identity needs to persist across thousands of requests. You're paying for addresses, and bandwidth stops appearing on the invoice. At 100 IPs the difference is roughly $24 versus $500 a month against the reported ASocks dedicated rates.

**Per-GB wins when you're rotating hard and each request is small.** SERP checks, price monitoring, geo-testing, lightweight scraping. Traffic-based billing also means you never pay for idle IPs.

**Coverage cuts the other way.** ASocks covers roughly 150-plus countries off a pool of around 7 million IPs; 9Proxy reports 20 million-plus IPs across 90-plus countries. If a specific country or city is the whole point of the job, check the coverage list before you check the price list — a cheaper gigabyte you can't spend is not cheaper.

**Targeting detail differs too.** ASocks charges extra for city and ASN targeting; 9Proxy includes country, state, city and ISP targeting in its packages. ASN-level targeting — the ability to pick a specific carrier or ISP — is the thing to ask about directly if your work depends on it.

**Trial risk is low either way.** ASocks hands out small trial balances through partner promo codes rather than a public free tier. 9Proxy offers a limited trial for new users depending on availability, and both models start at price points low enough to test with real work: $15 for 5 GB, or $24 for 100 IPs with no expiry pressure. 9Proxy also lists a 5% discount for referred users as part of its published affiliate terms, which the sign-up link applies.

## Quick answers to the usual questions

**Is ASocks really $3/GB for everything?** For pay-as-you-go residential and mobile traffic, yes. Dedicated monthly proxies are a separate, much higher rate card at $5 and $15 per proxy per month.

**Does ASocks get cheaper if I buy more traffic?** Based on the GB figures on its own comparison page — 50 GB for $150, 167 GB for $500, 333 GB for $1,000 — the rate stays at roughly $3/GB across the range.

**Does ASocks do free trials?** Partner platforms distribute codes worth a few gigabytes to new users. There's no open trial button.

**What's the cheapest way into 9Proxy?** $15 for the 5 GB pack if you want to test rotation, or $24 for 100 IPs if you want to test session stability. Both sit in your account until used, so a test that goes badly isn't a write-off.

**[👉 Compare all 9Proxy packages and pick the model that matches your workload](https://bit.ly/9-Proxy)** — the IP-based and GB-based calculators sit side by side, which makes the per-gig versus per-IP tradeoff visible in about thirty seconds.
