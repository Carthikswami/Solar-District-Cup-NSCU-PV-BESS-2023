# Solar District Cup 2023 – NC State University PV + BESS Portfolio

This repository documents a Solar District Cup design for a 6.6 MW photovoltaic portfolio with a 1.5 MWh battery energy storage system (BESS) for the NC State University district. The project covers technical siting, non-export operation concepts, and a full financial evaluation of rooftop, floating, and ground-mounted solar assets.

The work brings together interconnection constraints, campus load characteristics, and capital structure considerations to propose a viable deployment strategy for large-scale distributed solar on an academic campus. :contentReference[oaicite:1]{index=1}

---

## Project Scope

The design evaluates:

- Deployment of approximately 6.6 MW of PV across 11 sites, including rooftops, floating, and ground-mounted systems.
- Integration of a 1.5 MWh battery system to support peak shaving and operational flexibility.
- Non-export or export-limited control concepts using smart inverter capabilities.
- Site-level development constraints such as floodplain, wetlands, grading, land use, and access.
- Financial performance under power purchase agreement (PPA) and cash purchase structures, including incentives and lifecycle savings.

---

## Technical Approach

### Siting and Capacity

- Screened candidate rooftops and ground areas based on structural, environmental, and interconnection constraints.
- Evaluated individual array capacities and combined them into a campus portfolio.
- Considered floating PV potential as part of the generation mix.

### Controls and Operations

- Applied non-export and smart inverter concepts to allow high PV penetration while limiting backfeed on feeders.
- Considered battery dispatch strategies to:
  - Mitigate peak demand charges,
  - Improve self-consumption of on-site generation,
  - Support reliability for priority loads.

### Financial Analysis

- Built 20-year cash flows for:
  - PPA structures (targeting approximately 7.9 cents per kWh, all-in)  
  - Direct ownership / cash purchase structures
- Accounted for investment tax credits and other incentives, and compared lifecycle savings bands (for example, ranges on the order of multi-million dollar savings over the analysis horizon). :contentReference[oaicite:2]{index=2}

---

## Repository Structure

```text
solar-district-cup-ncsu-pv-bess-2023/
├── site-design/          # Site maps, layout concepts, and one-line diagrams
├── capacity-modeling/    # Sizing logic, load-matching analysis
├── controls-concepts/    # Non-export / smart inverter concepts and notes
├── financial-models/     # PPA vs cash scenarios, assumptions, outputs
├── reports/              # Final report, executive summary, slide deck
└── figures/              # Charts and visuals for communication
