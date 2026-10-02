# AI Energy and Carbon Explorer

Interactive single-page explorer of how AI uses energy, emits carbon and costs money, from power plant to data center to your desk.

**Live page:** https://gaborkalmar83.github.io/ai-energy-carbon-explorer/

## What's inside

1. **Lineage**: the 7 steps from power plant to your screen, and back.
2. **Grid simulator**: hourly carbon intensity for 7 Azure regions, by season and wind, with time-shifting.
3. **Compare models**: 51 cloud models (CLEER data) vs 7 local models on your own device. Energy, CO₂e and cost.
4. **Your workday**: device + AI end to end, 1 to 3,000+ people, day/week/month/year, API / Claude plan / GitHub Copilot costs with prompt caching.

Everything is in one file: `index.html`. No build step.

## Sources

- Grid intensity: Ember Yearly Electricity Data 2025 (via GreenCalculus)
- AI inference energy and embodied carbon: [CLEER Dashboard](https://cleerdash.sustainableaigroup.com/) by Sustainable AI Group, data licensed [CC BY-NC 4.0](https://github.com/sustainableaigroup/CLEER)
- Prices: Claude API and plans, GitHub Copilot plans and usage-based billing, list prices via CLEER / Artificial Analysis

Hourly curves, device power, PUE and local speeds are modelled estimates. See the footer of the page for all assumptions. Non-commercial use, with attribution to the sources above.
