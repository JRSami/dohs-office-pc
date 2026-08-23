# Dhaka Office PC Sourcing

Buying research for equipping one office staff desk in Dhaka: what machine to get, what it costs once the monitor, power backup and software licence are included, and where to buy it.

Aimed at a small business kitting out a staff member who spends the day in Excel, Word, email and a database front-end. All prices in Bangladeshi taka, collected from local retailers in August 2026.

## Contents

| File | Description |
|---|---|
| `index.html` | The guide. Machine comparisons, memory and storage market context, software licensing options, total cost of ownership, and a linked directory of every product mentioned. |
| `scorecard.html` | Interactive scorecard. Weight eight attributes to taste and thirteen machines re-rank live. |

Both are self-contained static HTML — no build step, no dependencies, no framework. Open either file directly in a browser, or serve the folder from any static host. They link to each other with relative paths.

## What the guide covers

- **Hardware** — assembled towers, brand pre-builts, mini PCs, all-in-ones and laptops, with configurations and current retail prices
- **The memory market** — why factory-fitted RAM matters more than usual right now, and a survey of which pre-builts actually ship with 16 GB
- **Software** — Microsoft 365 plans, one-time Office licences, Google Workspace and free alternatives, priced through Bangladeshi resellers
- **Total cost** — three-year cost per seat across several hardware and software combinations
- **Practical checks** — what to confirm before paying, and where each item can be bought

## How the scorecard scores

Eight attributes: price, processor, memory fitted, storage, warranty and service, availability, upgrade headroom, and size and power draw. Each carries a weight from 0 (ignored) to 5 (decisive), and the displayed score is the weighted mean of the machine's attribute scores.

The price axis uses the **complete desk cost**, not the machine alone. Towers and mini PCs include a monitor, UPS and peripherals; all-in-ones exclude the monitor; laptops exclude the UPS. That is the only basis on which the formats compare fairly.

Only the price score is computed. The other seven are editorial judgements from published specifications and observed market conditions — defensible, but not objective. Setting an attribute's weight to zero removes it from the calculation entirely, which is the quickest way to see which priority is driving a given ranking.

## Data and currency

Prices were collected between 21 and 23 August 2026 from Star Tech, Ryans, TechLand BD, BDStall, Eastern IT, Qbits, Pickaboo, Tofa, Daraz and LKEY. They are indicative, not quotations.

Two caveats worth carrying forward:

- Memory and SSD prices were mid-spike during collection and move faster than anything else on the page.
- Several retailers render price and stock only after page scripts run, so a listing can appear complete while the item is unavailable. Availability claims here should be confirmed by phone before being relied on.

## Correcting a price

Prices go stale quickly. Edit the relevant figure in `index.html` (and the `MACHINES` array in `scorecard.html` if the change affects a scored machine), then open a pull request. **Note the date you checked it in the commit message** — that is what tells the next reader how much to trust the number.

## Scope

Independent research. No retailer or manufacturer mentioned had any input, and none of the links are affiliate links. Prices for the same item genuinely differ between shops in Dhaka; check more than one before buying.

## Licence

Free to reuse and adapt. If republishing, keep the collection date visible so readers can judge how current the figures are.
