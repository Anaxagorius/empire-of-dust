# Empire of Dust

Single-file idle/clicker game where every system feeds a harsh progression loop: build income, survive choke, reset, and come back stronger.

## Run

1. Open `Empire-of-Dust.html` in a browser.
2. Save data is stored in browser localStorage.

## Release packaging

`Empire-of-Dust.zip` should always contain the current `Empire-of-Dust.html` build with matching content.

## Core currency and rates

- **Dust**: main spend currency.
- **Marks / Embers / Thorns / Crowns**: rebirth-prestige-ascension-crown progression currencies.
- **Rent / Factory / Bonds / Mining / Pit / Labor values** are rates.
  - Example: `Rent +0.30` means **+0.30 dust per second** before modifiers.
- **Total Yield (header)** = combined gross value of all profitable ventures:
  - dust-rate channels
  - racket income
  - BTC mining converted to dust value at current BTC price

## Main earning channels

- **Labor (The Ditch)**: click and labor base economy.
- **Tenements**: rent-based income with occupancy and weather interaction.
- **The Pit**: stock-like market with spreads/crashes.
- **Bitcoin**: BTC trading + mining economy.
- **Factory**: production-line income channel (now fully populated with upgrades).
- **Bonds**: slower, steadier coupon income channel (now fully populated with upgrades).

## Purchase scaling

- Rung purchases are now effectively unlimited.
- Each additional level on a rung costs **10% more** than the previous level.
- This applies across core ladders and long-term skill/progression ladders.

## Real estate and mega-structures

Tenement upgrades include late-game staged mega-structure development:

- Skyline Skeleton
- Skyline Arcology
- Skyline Crown

Each phase materially boosts rent capacity/output and culminates in a large empire-wide bonus.

## Bitcoin refactor: generators + farming machines

Bitcoin upgrades now explicitly include power generation and farm-machine concepts:

- generator-style upgrades improve mining and add **small rent bonus** (power for residents)
- machine/farm upgrades directly increase BTC/s and mining scale

## Crew and The Boys

### Crew
Crew automation purchases remain the operational managers of Labor/Tenements/Pit/Bitcoin loops.

### The Boys
The Boys now clearly operate as assignment-based force multipliers:

- **Door** assignment: reduces county theft pressure and protects net yield
- **Job** assignment: generates racket income but raises heat/theft pressure
- Training levels and balancing now make higher purchases meaningful over time (not just first rung).

## Casino fairness

Casino systems remain house-favored, but were tuned to be less punishing:

- better roulette payouts (still house edge)
- softer pricing on race/sports style books
- gambling training can improve practical returns (without flipping house advantage long-term)

## Skills and progression systems

### Ember skill trees
Classic branch trees remain for:

- Labour
- Tenements
- The Pit
- Bitcoin

### Active training skills (click training)
New click-training tracks with level milestones and passive bonuses:

- Mining
- Forestry
- Martial Arts
- Electrician
- Crypto
- Carpentry
- Fashion
- Gambling
- Bondsman
- Logistics

Each has its own style/theme and click target scaling.

### Facilitators (training automation)
Each training track has facilitator hires:

- upfront hire cost
- unlimited hires
- each hire costs ~10% more than previous
- ongoing salary drain (incremental)
- auto-trains associated skill over time

### Cycle tab and reset flow
Cycle now focuses on reset timing/state:

- Rebirth
- Prestige
- Ascension
- Crown
- relic/oath visibility

Progression purchase ladders for rebirth/prestige/ascension currencies are now managed from **Skills**.

## Save compatibility note
This is still a single-file game with state migration logic in-script. Old saves should load, with new systems initialized as needed.
