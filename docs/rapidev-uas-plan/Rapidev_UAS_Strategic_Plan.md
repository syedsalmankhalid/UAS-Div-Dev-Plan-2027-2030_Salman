# Rapidev UAS Division — Strategic Plan 2027–2030

**COMPANY CONFIDENTIAL** · Nov 3, 2026 · @Salman K

## Document Control

Rapidev should stand up a UAS (Unmanned Aircraft Systems) Division in three overlapping phases from 1 January 2027, on a core internal budget of USD 5.0M (≈ PKR 1.41B), to design and build surveillance, agri and supplies drones in Islamabad for Pakistani law-enforcement agencies (LEAs) and export customers.

| Item | Detail |
| --- | --- |
| Classification | COMPANY CONFIDENTIAL — Board and CEO only |
| Prepared by | Chief Technology Advisor (CTA), Rapidev Pvt Ltd, Islamabad |
| Audience | Board of Directors, Chief Executive Officer |
| Board meeting | 15–17 November 2026 |
| Version | v1.0 draft for Board review |
| Plan horizon | T0 = 1 Jan 2027 to M36 = Dec 2029, with an outlook to 2031 |
| Currency basis | USD with PKR equivalent at PKR 282 / USD (planning rate; sensitivity in Ch 8) |
| Companion files | Board slide deck (15 min) · Phase-wise financial workbook · Repo copy on branch `claude/rapidev-drone-expansion-plan-m0ihme` |

### Abbreviations

| Term | Meaning |
| --- | --- |
| UAS / UAV | Unmanned Aircraft System / Vehicle |
| sUAS | Small UAS, below 25 kg maximum take-off weight (MTOW) |
| VTOL | Vertical Take-Off and Landing (here: fixed-wing hybrid) |
| MALE | Medium-Altitude Long-Endurance UAV (typically 600 kg+ MTOW, 24 h+ endurance) |
| ISR | Intelligence, Surveillance and Reconnaissance |
| GCS | Ground Control Station |
| EO/IR | Electro-optical / infrared camera payload |
| BVLOS | Beyond Visual Line of Sight |
| ToT | Transfer of Technology |
| JV | Joint Venture |
| LRIP / FRP | Low-Rate Initial Production / Full-Rate Production |
| PCAA | Pakistan Civil Aviation Authority |
| MoDP / DEPO | Ministry of Defence Production / Defence Export Promotion Organization |
| STZA | Special Technology Zones Authority |
| NASTP | National Aerospace Science & Technology Park |
| PAeC | Pakistan Aerospace Council |
| GAMI / SAMI | General Authority for Military Industries / Saudi Arabian Military Industries (KSA) |
| HIL / SIL | Hardware-in-the-loop / Software-in-the-loop test rigs |
| M0, M6 … | Months after T0 (1 Jan 2027) |

### Basis of preparation

- Desk research completed 3 Nov 2026 from public sources (listed in Annex A). Several partner websites and rapidev.com could not be opened from the research environment; partner facts marked *(to validate)* rest on secondary sources or CTA input.
- All costs are planning estimates at ±25% accuracy (Class 4). They will be firmed into a Class 3 budget at Gate G1 (M3).
- Product names used here (e.g. *Sentinel*) are working titles only.

## Executive Summary

**Recommendation:** approve a USD 5.0M (PKR 1.41B) internally funded UAS Division. It acquires capability in 6 months, runs a design department to M24 and reaches production of 100 aircraft a year by M36. MALE-class work is added only through customer pre-funded co-production with KSA and Bahrain.

### The opportunity

- **Domestic LEA demand is urgent and growing.** Police and Counter-Terrorism Departments (CTDs), Frontier Corps (FC), Rangers, Motorway Police, CPEC security and disaster agencies need persistent, low-cost ISR. Use of militant drones on the western border since 2025 has also created demand for counter-UAS detection and interceptor capability.
- **The state backs private industry.** At Indus RAS Expo 2026 the Prime Minister said Pakistani drones are already over 60% indigenised and announced the *Spark* and *Elevate* programmes for robotics and autonomous systems ([Arab News](https://www.arabnews.com/node/2651885/pakistan)). Defence analysts note Pakistan is turning to private firms to build drones.
- **The Gulf export window is open.** KSA's Vision 2030 targets more than 50% localisation of military spend by 2030; GAMI reported 19.35% at end-2023 ([GAMI](https://www.gami.gov.sa/en/news/general-authority-military-industries-gami-grants-license-develop-manufacture-and-localize), [Breaking Defense](https://breakingdefense.com/2024/11/saudi-arabia-reveals-strides-in-local-defense-production-as-it-races-towards-ambitious-2030-goal)). A Pakistani supplier willing to co-produce and localise is attractive to KSA and Bahrain customers.
- **Agri and supplies are dual-use volume lines.** They share airframes, avionics and datalinks with the ISR product. Syngenta Pakistan has already piloted drone spraying on about 5,000 acres ([Brandsynario](https://www.brandsynario.com/business/syngenta-pakistan-successfully-pilots-drone-spraying-services-for-local-farmers/)).

### Why Rapidev

Rapidev already owns what most drone start-ups lack: RF and datalink engineering, mission-critical communications (first Pakistani member of TCCA, the global critical-communications association), embedded hardware, secure software and an LEA customer base. In a UAS, the datalink, GCS and command-and-control software carry about 30–40% of system value and most of the security sensitivity. Rapidev enters at the top of the value chain and buys or partners for airframes, propulsion and composites.

### Portfolio: three tiers

| Tier | Class | Products (working titles) | Route | Funding |
| --- | --- | --- | --- | --- |
| T1 | Small UAS < 25 kg | Sentinel-Q ISR quadcopter, AgriSpray-30, Cargo-M multirotor | In-house design and build | Core USD 5M |
| T2 | Tactical 25–150 kg | Sentinel-V fixed-wing VTOL ISR / cargo, 6–8 h | Inphoenix JV plus foreign ToT | Core USD 5M |
| T3 | MALE 600 kg+ | Co-produced MALE with Rapidev datalink, GCS and payload integration | Foreign OEM licence / co-production | Customer pre-funding (KSA, Bahrain) only |

### Three overlapping phases

| Phase | Window | Purpose | Exit criterion |
| --- | --- | --- | --- |
| 1 — Capability acquisition and ToT | M0–M6 (Jan–Jun 2027) | Sign JV and ToT, hire the core team, run a pilot integration in the existing premises | Gate G1 at M3: JV term sheet and one ToT signed |
| 2 — UAS Design Department | M3–M24 (Apr 2027–Dec 2028) | Build a 45-engineer department, qualify the T1 and T2 designs | Gate G3 at M18: design freeze |
| 3 — Manufacturing facility | Planning from M0, build M9–M18, LRIP M18–M24, ramp to M36 | Site at Silicon Village, Capital Smart City; 100 units a year | Gate G4 at M24: FRP decision |

### Investment by phase (USD M; PKR M at 282)

| Phase | HR | Equipment | Infrastructure | Other (ToT, JV, certification, prototypes) | Total USD M | Total PKR M |
| --- | --- | --- | --- | --- | --- | --- |
| Phase 1 | 0.22 | 0.13 | 0.05 | 0.40 | 0.80 | 226 |
| Phase 2 | 1.05 | 0.45 | 0.20 | 0.20 | 1.90 | 536 |
| Phase 3 | 0.40 | 0.75 | 0.55 | 0.10 | 1.80 | 508 |
| Contingency (10%) | — | — | — | 0.50 | 0.50 | 141 |
| **Total** | **1.67** | **1.33** | **0.80** | **1.20** | **5.00** | **1,410** |

Customer pre-funding from KSA and Bahrain comes on top of the USD 5M. It is ring-fenced for T3 and for export-specific adaptation, and is never needed to complete T1 and T2.

### Partners

- **Design:** Inphoenix Aviation (JV, minority stake below 50%), NaqCode (software and AI services), and Dr Jahanzeb Masud, PhD, Professor at Air University (Technical Advisor).
- **Manufacturing:** Honley, Sherani Engineering (PAeC member; supplied assembly jigs for the PAF MALE programme), ARRAD Technologies, Fibre Craft Industries (composites, Lahore).
- **Sub-systems and platforms:** Alsons Group / AKAL (Pakistan's first locally made UAV engine, shown at Eurosatory 2026; equity partner later), Integrated Dynamics (Karachi; datalinks, flight control, UAV heritage since 1997), Woot Tech (Karachi; VTOL and multirotor), Talons Dynamics (Islamabad), ZGI Robotics (Karachi).
- **Talent:** NUST (SMME Aerospace, SEECS, CAE), Institute of Space Technology, Air University (Islamabad and Kamra).

### Business outlook (high level)

At full rate (100 aircraft a year from 2030) the division can earn about USD 6–7M a year from T1 and T2 hardware plus services, at a 30–35% gross margin. On domestic volumes alone, cumulative cash break-even falls in 2032, with an indicative 10-year IRR of about 27%. One export Sentinel-V programme brings it to 2031.

### Top five risks

| Risk | Mitigation |
| --- | --- |
| Export and defence licensing delay (MoDP, DEPO, NOCs) | Start applications at M0; appoint a compliance lead; engage MoDP early through a pilot LEA order |
| Dependence on one foreign ToT source or on imported components | Two ToT sources per critical sub-system; a local second source by M24 |
| JV governance or IP dispute with Inphoenix | Rapidev majority (51–60%); background and foreground IP defined in the term sheet; deadlock clause |
| Talent poaching by state entities and Gulf employers | Retention bonuses, ESOP-style JV units, university pipeline of 15–20 interns a year |
| Scope creep into MALE within USD 5M | Board rule: T3 proceeds only on signed customer pre-funding |

### Decisions requested from the Board (15–17 Nov 2026)

1. Approve the UAS Division and the USD 5.0M phased budget, released at gates G1–G4.
2. Mandate the CEO and CTA to negotiate the Inphoenix JV (Rapidev majority) and up to two foreign ToT agreements.
3. Approve site due diligence and a letter of intent with Silicon Village, Capital Smart City.
4. Approve recruitment of the Division Head and five core leads from January 2027.
5. Adopt the rule that T3 (MALE) work proceeds only with signed customer pre-funding.

## Chapter 1 — Strategic Context and Market

Pakistan's drone market has moved from state-only programmes to a mixed state-and-private model. The first private firms to combine secure communications with qualified airframes will win LEA and Gulf contracts in 2027–2030.

### 1.1 Pakistan's UAS landscape

- **State backbone.** The armed forces' fleet rests on the NESCOM Burraq, GIDS Shahpar series and Leonardo Falco, plus imported Turkish and Chinese MALE aircraft ([Takshashila](https://takshashila.org.in/content/publications/20250626-pakistan-drone-ecosystem.html)). These programmes rarely serve police, FC or civil customers at small-UAS price points.
- **Private firms are rising.** Integrated Dynamics (Karachi, founded 1997) exported Border Eagle surveillance UAVs ([Wikipedia](https://en.wikipedia.org/wiki/Integrated_Dynamics)). Woot Tech (Karachi, founded 2021) moved from agri and survey VTOLs into defence products ([Robotics.press](https://robotics.press/companies/woot-tech-aerospace/)). Inphoenix grew out of the Institute of Space Technology into a 40+ engineer UAS avionics and GNC house.
- **Policy direction.** The Prime Minister cited over 60% drone indigenisation at Indus RAS Expo 2026 and launched the Spark and Elevate programmes ([Arab News](https://www.arabnews.com/node/2651885/pakistan)). Alsons' AKAL showed Pakistan's first locally made UAV engine at Eurosatory 2026 ([ProPakistani](https://propakistani.pk/2026/06/26/pakistan-unveils-first-locally-made-uav-engine-for-drones/)).
- **Threat driver.** Cross-border drone attacks from Afghanistan in 2025–2026 ([The Defense Post](https://thedefensepost.com/2026/03/14/pakistan-afghan-taliban-drone-attacks/amp/)) have pushed LEAs and FC to seek their own ISR, plus counter-UAS detection. Rapidev's RF capability fits the detection side.

### 1.2 Customer segments

| Segment | Need | Priority products | Buying route |
| --- | --- | --- | --- |
| Provincial police and CTDs (Punjab, KP, Sindh, Balochistan) | Urban and highway ISR, event security, night surveillance | Sentinel-Q, tethered option | Provincial procurement (PPRA rules), safe-city projects |
| FC, Rangers, Levies | Border and line-of-communication surveillance, 4–8 h endurance | Sentinel-V VTOL | Ministry of Interior, through MoDP-registered vendor |
| CPEC and SEZ security, oil and gas, power utilities | Pipeline and line patrol, perimeter security | Sentinel-V, Sentinel-Q | Corporate tenders |
| NDMA, PDMAs, Rescue 1122 | Flood mapping, last-mile medical and supply drop | Cargo-M, Sentinel-Q | Federal and provincial disaster budgets |
| Agriculture: provincial departments, agri-service companies, large farms | Precision spraying, crop scouting | AgriSpray-30 | Provincial schemes, agri-input companies (e.g. Syngenta-type service models) |
| Export: KSA, Bahrain, wider GCC | Localised ISR and border security, MALE co-production | Sentinel-V, T3 MALE integration | Government-to-government (G2G) through DEPO, GAMI localisation rules, customer pre-funding |
| Export: Africa, Central Asia | Low-cost ISR and agri | Sentinel-Q, AgriSpray-30 | DEPO, distributors |

### 1.3 Market sizing (planning view)

No audited figure exists for Pakistan's LEA drone market. For planning we use a bottom-up estimate:

- **Domestic LEA:** about 150 police and CTD districts plus FC and Rangers wings. Each needs 2–6 small ISR drones and, per sector, 1–2 VTOL systems. That gives a 2027–2031 addressable demand of roughly 800–1,200 small UAS and 60–100 VTOL systems, about USD 60–90M in total.
- **Domestic agri:** Pakistan cultivates about 22M hectares. Even 1% drone-serviced acreage needs 1,500–2,500 spray drones. DJI and XAG imports dominate today, which gives a local alternative an opening under import-substitution policy.
- **Gulf export:** KSA localisation means a foreign supplier must offer local content. Rapidev's target is a small share: 1–2 VTOL programmes and one MALE integration contract by 2030.
- **Rapidev's target share:** 100 units a year at full rate is about 8–12% of the domestic small-UAS LEA addressable market, plus export.

### 1.4 Competitors and alternatives

| Competitor | Strength | Weakness against Rapidev |
| --- | --- | --- |
| GIDS, NESCOM, NRTC, PAC Kamra (state) | Scale, military trust, MALE heritage | Priced and scheduled for armed-forces programmes; limited LEA focus |
| DJI, Autel, XAG (Chinese commercial) | Low price, mature products | Security concerns for LEAs, import NOC friction, no local support or customisation |
| Turkish OEMs (Baykar, STM and others) | Combat-proven, strong in the Gulf | Expensive; sell finished systems, not local co-development |
| Pakistani private firms (Woot Tech, Integrated Dynamics, Inphoenix and others) | Agile, low cost | Small scale, limited secure communications and production quality systems; many are better partners than rivals |

### 1.5 Regulation and compliance

| Instrument / authority | What it requires | Plan response |
| --- | --- | --- |
| Civil Unmanned Aircraft Rules 2024 (PCAA) | Registration of every drone with a unique code; track-and-trace for drones over 250 g; remote pilot licences ([Unmanned Airspace](https://www.unmannedairspace.info/uncategorized/pakistan-issues-new-rules-on-uas-registration/)) | Build track-and-trace into all products; train and license an in-house pilot cadre |
| Proposed drone regulatory authority (draft ordinance for licensing, import, manufacturing and permits) ([Profit](https://profit.pakistantoday.com.pk/2021/03/12/drone-regulatory-authority-draft-gets-pms-nod)) | Final status not confirmed in public sources *(to validate with legal counsel)* | Compliance lead tracks the gazette; the plan assumes a manufacturing licence regime by 2027 |
| Ministry of Defence NOCs | Needed for drone imports and flight operations; cited as a major bottleneck ([PIDE](https://pide.org.pk/research/bring-on-drone-technology-in-pakistans-agriculture-regulatory-constraints/)) | Apply at M0 for import of ToT kits and test drones; seek a standing test-flight NOC |
| MoDP registration | Required to supply defence and security forces | File at M0; register the JV entity once formed |
| DEPO export licensing | G2G and export sales | Begin export case files at M6 for KSA and Bahrain |
| PTA / FAB spectrum | Datalink frequencies and licensing | Rapidev's existing RF regulatory experience applies |
| MTCR Category I (500 kg / 300 km) | Constrains MALE transfers by member-state suppliers | T3 sourced only from suppliers able to transfer; legal review per deal |
| Customer-side rules (GAMI, Bahrain MoD) | Local-content and offset obligations | T3 and export T2 structured as co-production with a local partner in KSA |

### 1.6 Rapidev capability gap analysis

| Capability | Rapidev today | Gap | How closed |
| --- | --- | --- | --- |
| RF datalinks, mission-critical communications | Strong | Airborne form factor, weight and anti-jam | In-house, Phase 1–2 |
| Embedded hardware, PCB design | Strong | Flight-grade ruggedisation | In-house plus test lab |
| Software, GCS, security | Strong | UAV mission planning, MAVLink and STANAG 4586 | In-house plus NaqCode |
| Aerodynamics, airframe design | None | Full | Inphoenix JV, Dr Masud, foreign ToT |
| Flight control, GNC | None | Full | Inphoenix (core competence), ToT |
| Propulsion | None | Full | Buy (motors, ESCs); AKAL engines for T2 |
| Composites manufacturing | None | Full | Fibre Craft, ARRAD, Honley; in-house cell in Phase 3 |
| Flight test and airworthiness | None | Full | Hire test pilots; range MoUs |
| Production quality (AS9100) | ISO-type processes *(to validate)* | Aerospace quality management | AS9100D certification by M30 |

### 1.7 SWOT

| Strengths | Weaknesses |
| --- | --- |
| Secure communications and datalink IP; LEA relationships; software depth; Islamabad location near customers and universities | No airframe or flight heritage; no aerospace quality system; limited capital (USD 5M) for a hardware business |
| **Opportunities** | **Threats** |
| LEA ISR and counter-UAS demand; KSA localisation; Spark and Elevate programmes; STZA tax-free zone; import substitution in agri drones | Licensing delays; component embargoes on Chinese and Western parts; state-sector competition; FX depreciation; talent flight to the Gulf |

## Chapter 2 — Product and Technology Strategy

Five products on one common avionics, datalink and GCS core give Rapidev four T1/T2 revenue lines and a T3 integration role without five separate engineering programmes.

### 2.1 Portfolio and outline specifications

Targets for design entry. They will be confirmed with customers in Phase 1.

| Parameter | Sentinel-Q (T1 ISR) | AgriSpray-30 (T1 agri) | Cargo-M (T1 supplies) | Sentinel-V (T2 VTOL) | T3 MALE (co-production) |
| --- | --- | --- | --- | --- | --- |
| Configuration | Quad / hexa multirotor, folding | Hexa / octo multirotor | Coaxial octo multirotor | Fixed-wing quad-plane VTOL | Fixed-wing, runway |
| MTOW | 6–9 kg | 55–70 kg (30 L tank) | 35–45 kg | 35–60 kg | 1,000–1,700 kg (per OEM) |
| Payload | EO/IR gimbal 0.8–1.2 kg | 30 L liquid / 40 kg granules | 10–20 kg | 3–8 kg EO/IR, SIGINT or cargo pod | 200–400 kg |
| Endurance | 45–60 min | 12–18 min per sortie | 25–35 min | 6–8 h (hybrid / ICE) | 24 h+ |
| Range (link) | 10–15 km | 2–5 km | 15–20 km | 100–150 km line of sight; satcom option | Satcom BVLOS |
| Propulsion | Electric | Electric | Electric | Electric VTOL plus ICE cruise (AKAL engine candidate) | Turboprop / heavy-fuel engine |
| Key features | Night ISR, AI target tracking, encrypted link, track-and-trace | RTK GNSS, terrain following, variable-rate spraying | Winch drop, parachute, medical box | Anti-jam link, GNSS-denied navigation, STANAG 4586 GCS | Rapidev datalink, GCS and payload integration |
| Indicative price (USD) | 25–35k | 15–20k | 40–50k | 130–170k per aircraft; 350–450k per system | Programme-specific |
| Customers | Police, CTD, Rangers, utilities | Agri departments, service companies | NDMA, PDMAs, Rescue 1122, export | FC, Rangers, CPEC security, KSA, Bahrain | KSA, Bahrain (G2G) |

### 2.2 Common system architecture

Every product uses five common building blocks. That is the main cost and schedule advantage of the plan.

1. **Rapidev Avionics Core (RAC):** flight computer on an open-architecture autopilot (PX4 / ArduPilot-derived for T1; hardened custom stack for T2), with Rapidev's secure boot.
2. **Rapidev Secure Datalink (RSL):** encrypted C2 and video link, frequency-hopping and anti-jam, in 2 to 3 power classes. This is Rapidev's core differentiator.
3. **Rapidev GCS:** one software suite across all products. Mission planning, video exploitation, multi-aircraft control, STANAG 4586 interface, LEA command-centre integration (safe-city).
4. **Edge AI module:** on-board detection and tracking of people and vehicles; crop-health analytics for agri. Built with NaqCode.
5. **Navigation resilience:** multi-constellation GNSS with anti-spoofing, visual-inertial odometry for GNSS-denied flight.

Around that core sit the product-specific parts: airframe and composites, propulsion, payload (gimbal, spray, winch), power (batteries, hybrid generator) and launch and recovery.

### 2.3 Make, buy or partner by sub-system

| Sub-system | Decision | Phase 1–2 source | Phase 3 source (target) |
| --- | --- | --- | --- |
| Datalink and RF | Make | Rapidev | Rapidev |
| GCS and mission software | Make | Rapidev plus NaqCode | Rapidev |
| Flight control and GNC | Partner → make | Inphoenix JV, foreign ToT | JV (in-house) |
| Flight computer hardware | Make | Rapidev design, local PCB assembly | Rapidev line |
| Airframe aero design | Partner | Inphoenix JV, Dr Masud, ToT | JV |
| Composite structures | Buy → make | Fibre Craft, ARRAD, Honley | In-house layup cell plus Fibre Craft as second source |
| Metal parts, jigs, tooling | Buy | Sherani Engineering, Honley | Same |
| ICE engines (T2) | Buy | AKAL, plus imported benchmark engine | AKAL |
| Electric motors, ESCs | Buy | Import (Chinese / Turkish) | Import plus a local winding trial |
| Batteries | Buy | Import cells, local pack assembly | In-house pack line |
| EO/IR gimbals | Buy | Import; Integrated Dynamics option | Local integration |
| Spray system | Buy → make | Import pumps and nozzles | Local tank and boom |
| Edge AI | Partner | NaqCode | Rapidev plus NaqCode |
| MALE airframe (T3) | License | Foreign OEM | Co-production |

### 2.4 Indigenisation roadmap

| Milestone | Local content by value | What becomes local |
| --- | --- | --- |
| M6 pilot integration | about 30% | Datalink, GCS, integration |
| M18 LRIP design | about 50% | Plus flight computer, composites, harness, jigs |
| M36 FRP | 60–65% | Plus battery packs, spray systems, AKAL engine on T2 |
| 2030 target | 70% | Plus GNC software fully owned, local motor trial |

### 2.5 Quality, certification and standards

- **Quality management:** ISO 9001:2015 for the division by M12; AS9100D by M30, before FRP.
- **Software:** DO-178C-inspired lifecycle (requirements traceability, code review, coverage) for flight-critical code; full certification not required for the LEA market.
- **Hardware:** environmental testing to MIL-STD-810H methods (temperature, vibration, dust, humidity); EMC to MIL-STD-461G methods for export customers.
- **Interoperability:** STANAG 4586 GCS interface and MISB KLV video metadata for export and military customers.
- **Airworthiness:** a company airworthiness manual, flight-test cards and a configuration-control board; PCAA type registration for civil variants.
- **Cyber security:** encrypted links, secure boot, signed firmware, no cloud dependency for LEA data (a key selling point over imported drones).

### 2.6 Technology risks

| Risk | Effect | Mitigation |
| --- | --- | --- |
| VTOL transition and control maturity | T2 schedule slip | Use a ToT-proven flight-control baseline; HIL rig from M6; staged flight envelope |
| Hybrid propulsion reliability | Endurance shortfall | Benchmark imported engine in parallel with AKAL; electric-only fallback version at 2–3 h |
| Datalink weight | Payload loss on T1 | Compact airborne module designed in Phase 1 |
| Component embargo | Line stoppage | Dual sourcing; 6-month safety stock of critical items |

## Chapter 3 — Phase 1: Capability Acquisition and Transfer (M0–M6, Jan–Jun 2027)

In six months and for USD 0.80M (PKR 226M), Phase 1 turns Rapidev from a communications company into a UAS company. It signs the Inphoenix JV and one or two foreign ToT agreements, hires 18 people and flies a Rapidev-linked drone by M6.

### 3.1 Objectives and exit criteria

| # | Objective | Exit criterion (by M6) |
| --- | --- | --- |
| 1 | Secure design capability | Inphoenix JV shareholders' agreement signed; JV entity incorporated |
| 2 | Secure proven technology | At least one foreign ToT agreement signed (T2 VTOL or flight control); second under negotiation |
| 3 | Build the core team | Division Head plus 5 leads plus 6 engineers in post; 8 interns started |
| 4 | Demonstrate integration | Partner airframe flown with Rapidev datalink and GCS; LEA demonstration held |
| 5 | Open regulatory doors | MoDP registration filed; MoD NOC for test flights; PCAA registrations |
| 6 | Prepare Phase 3 | Silicon Village LOI signed; facility concept brief issued |

### 3.2 Hybrid acquisition model: foreign and local

Rapidev should combine three routes rather than bet on one.

| Route | What it buys | Partner(s) | Cost (Phase 1) | Pros | Cons |
| --- | --- | --- | --- | --- | --- |
| JV with equity (preferred) | Airframe, GNC and avionics design team | Inphoenix Aviation | USD 0.20M equity and JV set-up | Team and IP inside a Rapidev-controlled entity | Governance effort; valuation negotiation |
| Foreign ToT licence | Proven VTOL or flight-control baseline, production drawings, training | Shortlist (3.3) | USD 0.12M first tranche | Cuts 12–18 months from T2 | Royalties; export restrictions in the licence |
| Design-services contracts | Software, AI, specialist analysis | NaqCode, Dr Masud (advisor), Air University labs | Within HR budget | Flexible, fast | No ownership of the team |
| Supply agreements | Sub-systems | AKAL, Integrated Dynamics, Fibre Craft and others | Phase 2 onwards | No capital needed | Less control |
| Acqui-hire or minority stake (option) | A small specialist team (e.g. Talons Dynamics, ZGI Robotics) | Screened in Phase 1 | Not budgeted; Board decision at G2 | Speed | Integration risk |

### 3.3 Foreign ToT: screening approach

The Board has allowed all source countries. ToT candidates are screened in M0–M3 on five criteria: technical maturity, willingness to transfer source and drawings, export freedom to Pakistan and onward to the GCC, price and royalty, and supply security.

| Source pool | Typical offer | Best fit | Watch-outs |
| --- | --- | --- | --- |
| Türkiye (tier-2 UAV and avionics firms) | VTOL and tactical UAV designs, flight control, co-production experience in KSA | T2 VTOL, GCS standards | Turkish export licence; competes with Turkish primes in the Gulf |
| China (commercial and defence-industrial groups) | Low-cost VTOL kits, motors, batteries, MALE co-production | T2 baseline, T3 MALE, components | Gulf customer sensitivity; quality variance |
| Eastern Europe (Ukraine, Belarus, others) | Battle-tested small UAS, EW-resilient links, fast iteration | T1 ISR, anti-jam navigation | Political and sanctions screening per deal |
| UAE and KSA industry | Co-funding, local content, customer access | T3 and export T2 | They may want majority control of export programmes |
| Western component makers | Gimbals, engines, sensors | Payloads | ITAR and EAR controls; avoid in core design |

**Rule:** the core design (airframe, GNC, datalink, GCS) must end up ITAR-free and owned by Rapidev or the JV. Licensed IP is limited to time-bound baselines.

### 3.4 Inphoenix JV structure

Inphoenix is willing to hold less than 50%. The proposed structure:

| Term | Proposal |
| --- | --- |
| Entity | New private limited company, "Rapidev-Inphoenix Aerosystems" (working name), registered with SECP; MoDP registration after incorporation |
| Equity | Option A: Rapidev 60% / Inphoenix 40%. Option B: 51% / 49% with Rapidev casting vote. Recommendation: A, with Inphoenix able to earn up to 5% more through milestones |
| Contributions | Rapidev: cash (USD 0.20M in Phase 1, more as approved at gates), datalink and GCS licence, customer access, facilities. Inphoenix: design team (key engineers seconded or transferred), avionics and GNC IP, tools |
| Scope | Design and production of T1 and T2 airframes and flight systems. Rapidev keeps datalink, GCS and LEA prime contracts |
| IP | Background IP stays with each party, licensed royalty-free to the JV. Foreground IP owned by the JV. Rapidev has first right to buy it on exit |
| Governance | Board of 5 (Rapidev 3, Inphoenix 2); CEO nominated by Rapidev; CTO by Inphoenix; reserved matters list |
| Protections | Non-compete in UAS for 3 years; key-person lock-in; deadlock resolution; tag-along and drag-along; right of first refusal |
| Valuation | Independent valuation of Inphoenix's contribution in M1–M2 |

### 3.5 Design partners and advisors

- **Dr Jahanzeb Masud, PhD (Technical Advisor):** a very experienced aerospace engineer and Professor at Air University. Retained on an individual advisory contract. He chairs design reviews, guides aero and flight-test strategy, and links Rapidev with Air University (Islamabad and Kamra) for interns and joint labs.
- **NaqCode:** a software and AI services partner under a framework agreement. Scope: GCS front-end, edge-AI detection, simulation. *(Company profile to validate; its website could not be opened during research.)*
- **Inphoenix Aviation:** a JV partner. It began as an IST start-up, reports a 40+ aerospace engineering team and 5 years of UAS avionics, GNC and system engineering, and is a PAeC member.

### 3.6 Core team and first intern cohort (by M6)

| Role | Count | Start | Source |
| --- | --- | --- | --- |
| Head, UAS Division | 1 | M1 | Senior hire from state aerospace or industry |
| Lead, Aero and Structures | 1 | M2 | JV (Inphoenix) or market |
| Lead, Avionics and GNC | 1 | M2 | JV (Inphoenix) |
| Lead, RF and Datalink | 1 | M1 | Rapidev internal transfer |
| Lead, Software and GCS | 1 | M2 | Rapidev internal transfer |
| Lead, Test, Quality and Airworthiness | 1 | M3 | Ex-PAF or state flight-test background |
| Engineers (mixed) | 6 | M3–M5 | NUST, IST, Air University graduates; Rapidev transfers |
| Interns | 8 | M3 | NUST (SMME, SEECS, CAE), IST, Air University |
| Technical Advisor | 1 (part-time) | M1 | Dr Jahanzeb Masud |

### 3.7 Interim lab at Rapidev's existing premises

A space of about 3,000 sq ft is fitted out in M1–M2. It has a design office, an electronics and RF bench, an integration bay, secure storage for batteries and drones, and a small HIL and simulation corner. Outdoor tests use a leased field or partner range under NOC.

### 3.8 Pilot integration project (M2–M6)

1. Choose 2 platforms: an Inphoenix-supported multirotor and a VTOL kit from the ToT partner.
2. Integrate the Rapidev datalink and GCS, plus an EO/IR gimbal.
3. Ground and HIL tests (M4); first flights (M5).
4. LEA demonstration for Islamabad Police / Punjab CTD and an FC representative (M6).
5. Capture lessons into the Phase 2 requirements baseline.

### 3.9 Phase 1 financing

| Category | Line items | USD k | PKR M |
| --- | --- | --- | --- |
| HR | Division Head, 5 leads, 6 engineers, 8 interns, Technical Advisor retainer, recruitment, benefits | 220 | 62.0 |
| Equipment | CAD/CFD seed licences (40), HIL bench and dev kits (25), benchmark drones and parts (30), thrust stand and test gear (15), RF lab additions (10), workstations (10) | 130 | 36.7 |
| Infrastructure | Interim lab fit-out of about 3,000 sq ft (30), secure storage and IT (10), test vehicle lease (10) | 50 | 14.1 |
| Other | JV equity and set-up (200), ToT first tranche (120), legal, regulatory and MoDP (50), pilot demo (30) | 400 | 112.8 |
| **Total Phase 1** |  | **800** | **225.6** |

### 3.10 Milestones and risks

| Month | Milestone |
| --- | --- |
| M1 (Jan 2027) | Division Head hired; Inphoenix term sheet; ToT RFI to 6–8 candidates; MoDP filing |
| M2 | JV valuation; interim lab ready; Silicon Village LOI |
| M3 | **Gate G1:** JV term sheet and first ToT signed; interns start; Phase 2 starts |
| M4 | HIL rig running; facility concept design |
| M5 | First flight of the integrated pilot |
| M6 | JV incorporated; LEA demonstration; Phase 1 close-out report to the Board |

| Risk | Likelihood | Impact | Mitigation |
| --- | --- | --- | --- |
| JV valuation impasse | Medium | High | Independent valuer; milestone-based earn-out; fallback design-services contract |
| ToT partner restricts GCC export | Medium | High | Export clause is non-negotiable; keep two candidates live to M3 |
| NOC delay for test drone imports | High | Medium | File at M0; use locally available platforms for the pilot |
| Lead hires slip | Medium | Medium | Interim leads from Inphoenix; retained recruiter |

## Chapter 4 — Phase 2: UAS Design Department (M3–M24, Apr 2027–Dec 2028)

Phase 2 builds a 45-engineer design department, plus 12 interns, at Silicon Village. It takes four T1 and T2 products from prototype to frozen, qualified designs by M18 and supports LRIP to M24. Cost: USD 1.90M (PKR 536M).

### 4.1 Department charter

**Mission:** design, qualify and support secure, affordable UAS for LEA and export customers, with all flight-critical IP owned by Rapidev or its JV.

**Scope:** requirements, systems engineering, aero and structures, avionics and GNC, datalink, software and GCS, payloads and AI, test and airworthiness, production engineering hand-over.

### 4.2 Organisation (M24 steady state)

| Section | Lead | Engineers at M24 | Key outputs |
| --- | --- | --- | --- |
| Systems Engineering and Programme Office | Chief Engineer | 4 | Requirements, interfaces, configuration, schedule |
| Aerodynamics and Structures | Lead Aero | 8 | Airframe design, CFD/FEA, composites design, loads |
| Avionics and GNC | Lead Avionics (JV) | 8 | Flight computer, autopilot, navigation resilience |
| RF and Datalink | Lead RF | 6 | Airborne datalink family, antennas, anti-jam |
| Software, GCS and AI | Lead Software | 9 | GCS suite, edge AI, simulation, cyber security |
| Payloads and Mission Systems | Lead Payloads | 4 | EO/IR integration, spray and winch systems |
| Test, Quality and Airworthiness | Lead Test | 6 incl. 2 pilots | HIL/SIL, environmental, flight test, ISO/AS9100 |
| **Total** | 7 leads (incl. Chief Engineer) | **45** | + 12 interns, + Division Head and admin |

The Division Head reports to Rapidev's CEO. The JV CTO (Inphoenix) is dual-hatted as Lead Avionics and GNC, so design authority stays unified.

### 4.3 Design process

1. **Requirements and concept (M3–M6):** customer requirement workshops with LEAs and export customers; trade studies; System Requirements Review (SRR).
2. **Preliminary design (M6–M10):** architecture, CFD and sizing, Preliminary Design Review (PDR), chaired by Dr Masud.
3. **Detailed design (M10–M14):** CAD, PCB, software sprints; Critical Design Review (CDR).
4. **Prototype build and test (M12–M18):** HIL/SIL, ground, environmental and flight-test campaigns; Test Readiness Reviews.
5. **Design freeze and qualification (M18):** Production Readiness Review (PRR) gives **Gate G3**; technical data package released to Phase 3.
6. **LRIP support and design maintenance (M18–M24):** engineering change control, cost-down, customer feedback.

Tools: a PLM and configuration-management system, a requirements database, DFM/DFA reviews with Phase 3 manufacturing engineers from M9, and a V-model for software and avionics.

### 4.4 Product programme schedule

| Product | SRR | PDR | CDR | First flight | Design freeze |
| --- | --- | --- | --- | --- | --- |
| Sentinel-Q (T1 ISR) | M5 | M8 | M11 | M12 | M16 |
| AgriSpray-30 (T1) | M6 | M9 | M12 | M13 | M17 |
| Cargo-M (T1) | M8 | M11 | M14 | M15 | M19 |
| Sentinel-V (T2 VTOL) | M6 | M10 | M14 | M15 | M20 (LRIP lot 1 from M22) |
| T3 MALE integration | Starts only on signed pre-funding; earliest M12 | — | — | — | — |

### 4.5 Labs and tools

| Lab / tool | Purpose | USD k |
| --- | --- | --- |
| CAD/CAE licences (SolidWorks/CATIA, ANSYS Fluent and Mechanical, MATLAB/Simulink) | Design and analysis | 150 |
| HIL and SIL rigs (2) | Flight-control and avionics verification | 60 |
| RF and EMC pre-compliance lab | Datalink performance, emissions, susceptibility | 80 |
| Environmental (small thermal chamber; vibration through a partner or university) | MIL-STD-810H screening | 60 |
| Prototype composite cell (oven, vacuum tables, moulds) | Rapid airframe parts | 50 |
| Flight-test instrumentation, telemetry, GCS hardware | Flight campaigns | 50 |
| **Total equipment** |  | **450** |

Heavy tests (wind tunnel, large-scale vibration, EMC certification) are bought as services from NUST, IST, Air University Kamra, or NASTP facilities under MoUs.

### 4.6 Move to Silicon Village (M9–M12)

The department moves from the interim lab to a leased design centre of about 8,000 sq ft in Silicon Village, Capital Smart City. Silicon Village is an STZA-licensed Special Technology Zone of 498 acres, described by its management as Pakistan's largest tax-free technology park ([STZA](https://www.stza.gov.pk/?p=17097), [APP](https://www.app.com.pk/?p=1238836)). Its "Silicon Forge" IoT-hardware and "Silicon Labs" R&D clusters fit the division. Placing design next to the Phase 3 factory site removes hand-over friction.

### 4.7 Flight testing

- **Ranges:** MoUs with a partner range (subject to MoD NOC); a leased private field near Capital Smart City or Fateh Jang for T1; a remote range in Punjab or Sindh for T2 long-endurance flights.
- **Safety:** company flight-test manual, test cards, a safety review board and third-party liability insurance.
- **Pilots:** 2 licensed in-house pilots by M9, 4 by M24 (plus customer-training instructors).

### 4.8 IP strategy

- File Pakistani patents (IPO-Pakistan), plus PCT filings for export-relevant inventions: datalink anti-jam methods, VTOL transition control, spray-control algorithms.
- Trade secrets for source code; access control and code escrow rules agreed with JV partners.
- University research agreements: the university publishes, Rapidev gets an exclusive commercial licence.

### 4.9 Talent pipeline with universities

| Institution | Departments | Supplies | Mechanism |
| --- | --- | --- | --- |
| NUST, SMME (H-12) | Aerospace Engineering | Aero, structures, CFD | Sponsored final-year projects (FYPs), 4–6 interns a year |
| NUST, SEECS | Electrical, Computer Science, AI | Embedded, RF, software, AI | 3–5 interns a year; AI challenge |
| NUST, College of Aeronautical Engineering (Risalpur) | Avionics, Aerospace | Avionics, GNC | Interns and test-range cooperation |
| Institute of Space Technology | Avionics, Aerospace | Avionics, GNC, satellite navigation | 2–4 interns a year; joint lab (Inphoenix's alma mater) |
| Air University, Islamabad | Mechatronics, Electrical, Aerospace | Software, mechatronics | Interns; Dr Masud's research group |
| Air University Aerospace and Aviation Campus, Kamra | Aerospace, Aviation | Technicians, test and maintenance | Interns; technician pipeline for Phase 3 |

The intern-to-hire funnel targets 15–20 interns a year from M3, about a 50% conversion rate, and 6–8 sponsored FYPs a year on real division problems.

### 4.10 Phase 2 financing

| Category | Line items | USD k | PKR M |
| --- | --- | --- | --- |
| HR | Ramp from 12 to 45 engineers plus leads; 12 interns; about 630 person-months; advisor retainer | 1,050 | 296.1 |
| Equipment | Labs and tools (4.5) | 450 | 126.9 |
| Infrastructure | Silicon Village design-centre lease for about 15 months (75), fit-out (100), IT and security (25) | 200 | 56.4 |
| Other | Prototypes: T1 4 units × 3 products, T2 3 aircraft (120); range fees and insurance (30); ISO 9001 and PCAA registrations (25); IP filings (10); university FYPs and joint lab (15) | 200 | 56.4 |
| **Total Phase 2** |  | **1,900** | **535.8** |

### 4.11 Milestones and risks

| Gate / month | Milestone |
| --- | --- |
| M3 | Phase 2 starts (overlaps Phase 1) |
| M9 | **Gate G2:** PDRs passed; Silicon Village lease signed; design centre move starts |
| M12 | ISO 9001; first flight of Sentinel-Q |
| M15 | First flight of Sentinel-V |
| M18 | **Gate G3:** design freeze (T1); PRR passed; LRIP starts |
| M20 | Sentinel-V design freeze |
| M24 | **Gate G4:** qualification complete; FRP decision; 45 engineers in post |

| Risk | Mitigation |
| --- | --- |
| Too many parallel programmes for the team | Cargo-M staggered 2 months behind; the Board may defer it at G2 |
| Sentinel-V flight-control immaturity | Flight test with the ToT baseline first; independent review by Dr Masud |
| Attrition of key engineers | Retention plan (Ch 7); documented designs in PLM |
| Customer requirements churn | Frozen requirements baseline at SRR; change board |

## Chapter 5 — Phase 3: Manufacturing Facility (planning from M0; LRIP M18; 100 units a year by M36)

Phase 3 runs alongside Phases 1 and 2 from day one. That way a leased 20,000 sq ft factory at Silicon Village is fitted out by M18, delivers LRIP lots from M18 to M24 and reaches 100 aircraft a year on one shift by M36. Cost: USD 1.80M (PKR 508M), with production working capital funded by customer advances.

### 5.1 Phase 3 timeline

| Window | Stage | Key outputs |
| --- | --- | --- |
| M0–M3 | Planning | Facility brief, capacity model, site shortlist, Silicon Village LOI |
| M3–M9 | Site and approvals | Site due diligence, lease negotiation, STZA enterprise licence, MoDP facility security plan, layout design |
| M9–M12 | Contracting | Lease signed (Gate G2); fit-out contractor and long-lead machines ordered |
| M12–M18 | Fit-out and commissioning | Building works, machine installation, ERP/MES go-live, operator training |
| M18–M24 | LRIP | 2–3 lots, about 20–30 aircraft in total; first-article inspections; customer acceptance |
| M24–M36 | Ramp to FRP | AS9100D (M30); 100 units a year rate by M36 |

### 5.2 Site selection

**Primary: Silicon Village, Capital Smart City, Islamabad.** It is an STZA-licensed Special Technology Zone (498 acres, tax-free status), next to the design centre, and about 30 minutes from Islamabad and Rawalpindi customers and universities.

**Secondary options:** ICT industrial zone (I-9 / I-10), Islamabad Technology Park (STZA, Chak Shahzad), the Kamra / Taxila aerospace cluster. Full scoring is in Annex F.

| Criterion (weight) | Silicon Village | ICT industrial zone | STZA park (Chak Shahzad) | Kamra / Taxila |
| --- | --- | --- | --- | --- |
| Tax and duty incentives (20%) | 5 | 2 | 5 | 3 |
| Co-location with design centre (20%) | 5 | 3 | 4 | 2 |
| Talent access (15%) | 4 | 5 | 5 | 3 |
| Security and test-flight access (15%) | 4 | 2 | 3 | 5 |
| Lease cost and availability (15%) | 3 | 3 | 3 | 4 |
| Supply-chain proximity (15%) | 3 | 4 | 3 | 5 |
| **Weighted score (out of 5)** | **4.1** | **3.1** | **3.9** | **3.6** |

**Decision rule:** lease, do not buy. Buying land would use 30–50% of the whole USD 5M. Revisit a build-to-suit option after FRP with pre-funding or bank finance.

### 5.3 Capacity and layout (about 20,000 sq ft)

Target mix at full rate: 40 Sentinel-Q, 25 AgriSpray-30, 15 Cargo-M, 20 Sentinel-V a year. That is 100 aircraft, plus spares (about 15% of value).

| Zone | Area (sq ft) | Function |
| --- | --- | --- |
| Goods-in, bonded and secure stores | 2,000 | Inspection, controlled items, battery store (fire-rated) |
| Composites shop | 4,000 | Layup, vacuum bagging, oven cure, trimming (CNC router), paint booth |
| Machining and fabrication | 1,500 | CNC mill, metal parts, jigs and fixtures |
| Electronics and harness (ESD) | 2,500 | Harnesses, flight-computer and datalink assembly (PCBs from a local contract manufacturer at first), conformal coating |
| Battery pack line | 800 | Cell grading, pack assembly, test |
| Final integration lines | 4,000 | 2 lines: multirotor line (T1) and fixed-wing line (T2) |
| Test and acceptance | 2,500 | Environmental screening, RF test, end-of-line test, calibration |
| Quality, engineering, offices, training room | 2,700 | QA lab, production engineering, customer training |
| **Total** | **20,000** | Flight acceptance at the partner range |

### 5.4 Manufacturing partner model

| Partner | Role in Phase 3 | Status |
| --- | --- | --- |
| Sherani Engineering (Karachi) | Assembly jigs, fixtures, inspection gauges, moulds. Supplied jigs for the PAF MALE UAV programme in 2018; PAeC member ([PAeC](https://pakaero.com.pk/sherani-engineering-a-paec-success-story/)) | Framework agreement M9 |
| Honley (honleygroup.com) | Precision machining, metal parts, sub-assemblies *(capabilities to validate; website not reachable during research)* | Supplier audit M6–M9 |
| ARRAD Technologies | Composite and mechanical sub-assemblies, possible build-to-print of airframes *(to validate)* | Supplier audit M6–M9 |
| Fibre Craft Industries (Lahore) | Composite structures and moulds; second source to the in-house cell *(to validate)* | Prototype parts from M10 |
| Alsons / AKAL | ICE engines for Sentinel-V; later co-investor | Engine evaluation M6–M15; supply agreement M18 |
| Integrated Dynamics (Karachi) | Gimbals, flight-control and datalink know-how; possible build partner for export lots | Teaming discussion M3–M9 |
| Woot Tech (Karachi, NASTP) | VTOL and multirotor sub-assemblies, surge capacity | Teaming discussion M6 |
| Local electronics manufacturer | PCB assembly (SMT) until volumes justify an in-house line | Contract M12 |

**Principle:** Rapidev and the JV do final integration, test, datalink and flight-computer assembly, and quality sign-off. Structures and metalwork are mostly bought, with a minimal in-house composite cell for agility and protection of IP.

### 5.5 Supply chain

- Vendor development programme from M6: audits, first-article inspection and quality agreements for the top 25 parts.
- Dual sourcing for motors, ESCs, cells and GNSS receivers (Chinese plus Turkish or other).
- Six months of safety stock for embargo-sensitive items; an import-licence calendar run by the compliance lead.
- ERP with lot and serial traceability from goods-in to delivery (track-and-trace requirement).

### 5.6 Quality system

ISO 9001 (M12), then AS9100D (M30). Also: first-article inspection to AS9102 for all LRIP parts, a nonconformance and corrective action process, configuration control linked to PLM, and acceptance-test procedures signed off by the customer.

### 5.7 Production ramp

| Period | Sentinel-Q | AgriSpray-30 | Cargo-M | Sentinel-V | Total aircraft |
| --- | --- | --- | --- | --- | --- |
| LRIP H2 2028 (M18–M24) | 12 | 8 | 2 | 3 | 25 |
| 2029 (M25–M36) | 30 | 20 | 10 | 12 | 72 (exit rate 100/yr) |
| 2030 | 40 | 25 | 15 | 20 | 100 |

### 5.8 After-sales: MRO, training, spares

- Customer training academy (pilot, maintainer) at Silicon Village. Revenue per course.
- MRO and spares contracts at 10–15% of fleet value a year; field-support teams in Islamabad, Lahore, Karachi and Quetta.
- Export customers: an in-country support partner, with KSA local content through a GAMI-licensed entity.

### 5.9 Phase 3 financing

| Category | Line items | USD k | PKR M |
| --- | --- | --- | --- |
| HR | Production manager, manufacturing and quality engineers, technicians ramping to about 30 by M36 (mostly from M15) | 400 | 112.8 |
| Equipment | Composite cell and oven, moulds (220); CNC router and mill (150); electronics rework, harness tooling (80); battery line (40); test and acceptance: chamber, shaker, end-of-line benches, RF test (160); jigs and fixtures (60); ERP/MES (40) | 750 | 211.5 |
| Infrastructure | Factory fit-out: ESD area, paint booth, battery store, secure store (300); power backup and solar (80); security, fire safety, IT (70); lease M15–M36 (100) | 550 | 155.1 |
| Other | AS9100D (30), first-article and qualification (30), ERP services and training (20), site studies and permits (20) | 100 | 28.2 |
| **Total Phase 3** |  | **1,800** | **507.6** |

**Production working capital** (materials for about 4 months of output, about USD 0.6–0.8M at full rate) sits outside the USD 5M. It is funded by 30–50% customer advances on LEA and export orders, plus bank running finance (e.g. SBP-refinanced schemes) secured on confirmed orders.

### 5.10 Milestones and risks

| Month | Milestone |
| --- | --- |
| M2 | Silicon Village LOI |
| M9 | **Gate G2:** lease signed; long-lead machines ordered |
| M15 | Building handed over; machines installed |
| M18 | **Gate G3:** LRIP lot 1 starts |
| M24 | **Gate G4:** FRP decision; about 25 aircraft delivered |
| M30 | AS9100D certified |
| M36 | Rate of 100 aircraft a year reached |

| Risk | Mitigation |
| --- | --- |
| Silicon Village construction or utilities delay | Secondary site (STZA Chak Shahzad) kept warm until M9; temporary LRIP in the design centre |
| Low orders at LRIP | Do not ramp before G4; T1 agri and cargo lines give non-defence volume |
| Import delays on machines | Order long-lead items at M9; local alternatives for CNC |
| Fire risk from batteries | Fire-rated battery store, procedures, insurance |

## Chapter 6 — Pakistan Industry Partner Ecosystem

Twelve named Pakistani partners cover every sub-system Rapidev will not make itself. The plan engages them in three waves (design M0–M3, manufacturing M6–M9, platform teaming M3–M12), always with an NDA before an MoU before any contract.

### 6.1 Partner map by sub-system

| Sub-system | Lead partner | Alternate / second source |
| --- | --- | --- |
| Airframe and aero design | Inphoenix Aviation (JV) | Dr Jahanzeb Masud (advisor); foreign ToT |
| Flight control and GNC | Inphoenix Aviation (JV) | Integrated Dynamics; foreign ToT |
| Software, AI, simulation | NaqCode | Rapidev in-house; ZGI Robotics (robotics and autonomy) |
| Datalink and GCS | Rapidev | Integrated Dynamics (heritage datalinks) |
| Composite structures | Fibre Craft Industries | ARRAD Technologies; in-house cell |
| Machined parts and sub-assemblies | Honley | Sherani Engineering |
| Jigs, fixtures, moulds, tooling | Sherani Engineering | Honley |
| ICE propulsion (T2) | Alsons / AKAL | Imported benchmark engine |
| VTOL and multirotor platforms, surge capacity | Woot Tech | Talons Dynamics |
| Small UAS, robotics, counter-UAS concepts | Talons Dynamics | ZGI Robotics |
| EO/IR gimbal integration | Integrated Dynamics | Import |

### 6.2 Partner profiles

| Partner | Location | What is known | Proposed role | Engagement | Confidence |
| --- | --- | --- | --- | --- | --- |
| [Inphoenix Aviation](https://www.inphoenixaviation.com/) | Islamabad | Started at IST; reports a 40+ aerospace team; 5 years in UAS avionics, GNC and system engineering; PAeC member | JV partner (below 50%): design authority for airframe and GNC | Term sheet M1; JV M6 | Medium (self-reported) |
| [NaqCode](https://naqcode.com/) | Pakistan | Software engineering firm *(profile to validate)* | GCS front-end, edge AI, simulation | Framework contract M2 | Low until validated |
| Dr Jahanzeb Masud, PhD | Islamabad | Very experienced aerospace engineer; Professor at Air University | Technical Advisor: design reviews, flight-test strategy, academic links | Advisory contract M1 | High (CTA input) |
| [Honley](https://honleygroup.com/) | Pakistan | Engineering and manufacturing group *(capabilities to validate)* | Machined parts, sub-assemblies | Audit M6; framework M9 | Low until validated |
| [Sherani Engineering](https://sheraniengineering.com/) | Karachi | Est. 1990; jigs, fixtures, dies, moulds, SPM; early PAeC member; designed, made and commissioned jigs for the PAF MALE UAV in 2018 ([PAeC](https://pakaero.com.pk/sherani-engineering-a-paec-success-story/)) | Tooling, jigs and assembly fixtures for both lines | Framework M9 | High |
| [ARRAD Technologies](https://www.arradtech.com/) | Pakistan | Technology manufacturer *(capabilities to validate)* | Composite and mechanical sub-assemblies, build-to-print | Audit M6 | Low until validated |
| [Alsons Group / AKAL](http://www.alsonsgroup.com/) | Karachi | Automotive and electronics group; AKAL showed Pakistan's first locally developed UAV engine (four engines) at Eurosatory 2026; specs not public ([ProPakistani](https://propakistani.pk/2026/06/26/pakistan-unveils-first-locally-made-uav-engine-for-drones/)) | Sub-system supplier (T2 engines), later equity partner or co-investor | Engine evaluation M6; supply agreement M18; equity option after G4 | Medium |
| Woot Tech | Karachi (NASTP, Shahrah-e-Faisal) | Founded 2021; commercial VTOL for agri and survey, then defence products; claims Pakistan Navy induction of the Juggernaut multirotor ([Robotics.press](https://robotics.press/companies/woot-tech-aerospace/)) | VTOL and multirotor sub-assemblies, surge production, agri know-how | NDA M3; teaming M6 | Medium (claims not third-party verified) |
| Integrated Dynamics | Korangi Creek, Karachi | Founded 1997; UAV platforms, flight control, C4I, datalinks, payloads; exported Border Eagle ([Wikipedia](https://en.wikipedia.org/wiki/Integrated_Dynamics)) | Gimbal and payload integration, datalink cross-licence, export build partner | NDA M3; teaming M9 | Medium (sources dated) |
| [Talons Dynamics](http://talonsdynamics.com/) | Islamabad | Islamabad drone developer *(profile to validate; site not reachable)* | Small UAS and counter-UAS concepts; acqui-hire option | Screening M3 | Low until validated |
| [Fibre Craft Industries](https://fcicomposites.com/) | Lahore | Composites manufacturer *(capabilities to validate; site not reachable)* | Composite airframe parts and moulds | Prototype parts M10 | Low until validated |
| [ZGI Robotics](https://www.linkedin.com/company/zgi-robotics/) | Karachi | Robotics company *(profile to validate)* | Autonomy and robotics software, ground robotics adjacency | Screening M3 | Low until validated |

Partners marked *to validate* get a site visit and a capability questionnaire in M1–M3. That covers process, capacity, quality system, MoDP status and key staff. Their scores are then confirmed before any MoU.

### 6.3 Other suppliers to approach

- **PCB assembly:** Islamabad, Rawalpindi and Lahore contract electronics manufacturers (shortlist in Phase 1).
- **Batteries:** local pack assemblers for e-mobility, for pack assembly with imported cells.
- **State facilities as service providers:** NASTP (test and certification services), PAC Kamra and AWC (environmental and EMC testing, subject to access), NUST, IST and Air University labs (wind tunnel, vibration).
- **Testing and calibration:** PNAC-accredited labs.

### 6.4 Partner scoring matrix

Scores 1–5, weights in brackets. Initial scores are CTA judgement and must be confirmed through audits.

| Partner | Capability (30%) | Capacity (15%) | Quality / clearance (20%) | Cost (15%) | Strategic fit (20%) | Weighted |
| --- | --- | --- | --- | --- | --- | --- |
| Inphoenix Aviation | 4 | 3 | 3 | 4 | 5 | 3.85 |
| Sherani Engineering | 4 | 3 | 4 | 4 | 4 | 3.85 |
| Integrated Dynamics | 4 | 3 | 4 | 3 | 3 | 3.50 |
| Alsons / AKAL | 3 | 4 | 4 | 3 | 4 | 3.55 |
| Woot Tech | 3 | 3 | 3 | 4 | 3 | 3.15 |
| Dr Jahanzeb Masud (advisor) | 5 | 2 | 5 | 4 | 5 | 4.40 |
| NaqCode | 3 | 3 | 3 | 4 | 3 | 3.15 |
| Fibre Craft Industries | 3 | 3 | 3 | 4 | 3 | 3.15 |
| Honley | 3 | 3 | 3 | 3 | 3 | 3.00 |
| ARRAD Technologies | 3 | 3 | 3 | 3 | 3 | 3.00 |
| Talons Dynamics | 3 | 2 | 3 | 4 | 3 | 3.00 |
| ZGI Robotics | 3 | 2 | 3 | 4 | 3 | 3.00 |

### 6.5 Engagement sequence

1. **NDA** (all partners, M0–M3), with mutual export-control and confidentiality clauses.
2. **Capability audit** (M1–M6).
3. **MoU** (selected partners): scope, exclusivity by product line, pricing principles.
4. **Framework or supply agreement:** quality clauses (AS9100 flow-down), IP, delivery, liquidated damages.
5. **Annual partner review:** scorecard on quality, delivery, cost and responsiveness.

## Chapter 7 — Human Resources Plan

The division grows from 0 to 20 people at M6, 75 at M24 and about 100 at M36, including interns. About 60% of engineers come from the NUST, IST and Air University pipeline, and the senior 10% from experienced aerospace hires and the Inphoenix JV.

### 7.1 Headcount by phase and function (end of period)

| Function | M6 | M12 | M18 | M24 | M36 |
| --- | --- | --- | --- | --- | --- |
| Division leadership and admin (Head, finance, HR, compliance, procurement) | 2 | 4 | 5 | 6 | 8 |
| Design leads (incl. Chief Engineer) | 5 | 7 | 7 | 7 | 7 |
| Design engineers | 6 | 20 | 34 | 38 | 40 |
| Test pilots and test engineers | 1 | 3 | 5 | 6 | 7 |
| Manufacturing and quality engineers | 0 | 1 | 4 | 6 | 8 |
| Technicians and operators | 0 | 0 | 6 | 12 | 22 |
| Business development and customer support | 0 | 1 | 2 | 3 | 5 |
| **Staff subtotal** | **14** | **36** | **63** | **78** | **97** |
| Interns (rolling cohorts) | 8 | 12 | 12 | 12 | 15 |
| Technical Advisor (part-time) | 1 | 1 | 1 | 1 | 1 |

Some Phase 1 staff are Rapidev transfers (RF and software leads), so their cost was already partly in the base business. They are counted in the division to show its full cost.

### 7.2 Salary bands (Islamabad market, 2026, PKR per month gross, approximate)

| Grade | Role examples | Band PKR k / month | Loaded cost factor |
| --- | --- | --- | --- |
| E1 | Division Head | 1,200–1,800 | 1.25 |
| E2 | Chief Engineer, section leads | 700–1,200 | 1.25 |
| E3 | Senior engineer (6–10 years) | 450–700 | 1.25 |
| E4 | Engineer (2–5 years) | 250–420 | 1.25 |
| E5 | Graduate engineer | 150–230 | 1.20 |
| T1–T2 | Senior technician / technician (DAE, Kamra graduates) | 90–180 | 1.20 |
| I | Intern stipend | 40–60 | 1.00 |

The bands are planning assumptions from market experience, not a survey. HR will benchmark them in M1. Gulf employers pay 2–3 times these rates for senior aerospace engineers, so retention matters more than salary in the plan.

### 7.3 Recruitment sources

- **Senior and lead:** ex-PAF, PAC, NESCOM and GIDS professionals (retired or seeking private sector); the Pakistani diaspora in the Gulf and Türkiye; the Inphoenix JV team.
- **Engineers:** NUST SMME (Aerospace), SEECS (EE, CS, AI), CAE (Avionics, Aerospace); IST (Avionics, Aerospace); Air University Islamabad (Mechatronics, EE) and Kamra (Aerospace, Aviation).
- **Technicians:** Air University Kamra campus, PAF technical training alumni, GIKI and polytechnic DAE graduates.
- **Interns:** two cohorts a year (Feb and Jul); 8–12 weeks plus a final-year project option; about 50% conversion.

### 7.4 Training and certification

- PCAA remote pilot licences for all test and demo staff.
- AS9100 internal auditors (2), IPC-A-610 and IPC/WHMA-A-620 for electronics and harness technicians, composite repair training.
- ToT training packages delivered at the ToT partner and in Islamabad (budgeted inside the ToT fee).
- Annual learning budget per engineer: about PKR 100k.

### 7.5 Retention

- **JV phantom equity / long-term incentive units** for the top 20% of engineers, vesting over 4 years and tied to FRP and export milestones.
- **Retention bonus** of 1–2 months' salary at M12, M24 and M36 for critical roles.
- **Career ladder** with a technical track (Principal Engineer) equal to the management track.
- **Purpose and visibility:** named patents, conference papers, flight-test participation.
- **Bonding:** 2-year service agreements for staff given foreign ToT training (legally enforceable training-cost recovery).

### 7.6 HR cost summary (USD k)

| Phase | HR cost USD k | PKR M |
| --- | --- | --- |
| Phase 1 (M0–M6) | 220 | 62.0 |
| Phase 2 (M3–M24, design) | 1,050 | 296.1 |
| Phase 3 (M0–M36, manufacturing) | 400 | 112.8 |
| **Total in USD 5M** | **1,670** | **470.9** |

From 2029, division salaries are increasingly paid from gross margin on deliveries rather than from the capital budget. The full schedule is in the workbook's HR Plan tab.

## Chapter 8 — Financial Plan (High Level)

The USD 5.0M is spent over 2027–2029 and released in five gate tranches. On domestic volumes alone the division's cumulative cash turns positive in 2032, with an indicative 10-year project IRR of about 27% (NPV of USD 2.2M at 15%). One export VTOL programme pulls break-even into 2031.

### 8.1 Spend by year and phase (USD M)

| Phase | 2027 | 2028 | 2029 | Total |
| --- | --- | --- | --- | --- |
| Phase 1 (M0–M6) | 0.80 | — | — | 0.80 |
| Phase 2 (M3–M24) | 0.75 | 1.15 | — | 1.90 |
| Phase 3 (M0–M36) | 0.35 | 0.95 | 0.50 | 1.80 |
| Contingency | 0.10 | 0.20 | 0.20 | 0.50 |
| **Total USD M** | **2.00** | **2.30** | **0.70** | **5.00** |
| **Total PKR M (at 282)** | **564** | **649** | **197** | **1,410** |

By category: HR USD 1.67M (33%), Equipment 1.33M (27%), Infrastructure 0.80M (16%), Other (ToT, JV equity, certification, prototypes) 0.70M (14%), Contingency 0.50M (10%).

### 8.2 Funding and gate releases

**Core funding is 100% Rapidev internal**, released only when each gate is passed:

| Release | Trigger | USD M | Cumulative |
| --- | --- | --- | --- |
| R0 | Board approval (Nov 2026) | 0.80 | 0.80 |
| R1 | Gate G1 (M3): JV term sheet and ToT signed | 1.40 | 2.20 |
| R2 | Gate G2 (M9): PDRs passed, Silicon Village lease | 1.60 | 3.80 |
| R3 | Gate G3 (M18): design freeze, LRIP start | 0.90 | 4.70 |
| R4 | Gate G4 (M24): FRP decision (balance of contingency) | 0.30 | 5.00 |

**Customer pre-funding sits on top of the USD 5M and is ring-fenced:**

- **KSA and Bahrain:** advance payments of 30–50% on export Sentinel-V systems; full non-recurring engineering (NRE) funding for T3 MALE integration and in-country localisation. Contracted G2G through DEPO, with a local partner for GAMI local-content credit in KSA.
- **Domestic LEAs:** 20–30% mobilisation advances where procurement rules allow.
- **Working capital:** bank running finance against confirmed orders.

### 8.3 Revenue model at full rate (2030)

| Product | Units a year | Average price USD k | Revenue USD M |
| --- | --- | --- | --- |
| Sentinel-Q | 40 | 30 | 1.20 |
| AgriSpray-30 | 25 | 18 | 0.45 |
| Cargo-M | 15 | 45 | 0.68 |
| Sentinel-V (per aircraft) | 20 | 150 | 3.00 |
| Services: training, MRO, spares (about 17%) | — | — | 0.90 |
| **Total** | **100** |  | **6.23** |

The gross margin assumption is 35% (blended; higher on GCS and software, lower on agri). Revenue ramp: USD 0.2M (2027, demos and NRE), 1.1M (2028, LRIP), 3.9M (2029), 6.2M (2030), 7.5M (2031).

### 8.4 Cash profile

&#91;embedded content: Plan model, workbook tab Revenue · 2027–2032, USD M, 35% gross margin, USD 0.9–0.95M sustaining overhead from 2030\]

Investment years 2027–2028 take the position down to about USD −3.8M. LRIP and FRP margins then recover it through 2029–2031. Any export programme or T3 integration contract adds to these numbers, because its NRE is customer-funded.

### 8.5 Sensitivities (effect on cumulative break-even year)

| Change | Effect |
| --- | --- |
| One export Sentinel-V programme (4 systems from 2029) | Break-even moves to 2031 |
| Volumes 30% below plan | Break-even moves to 2034 |
| 6-month slip in design freeze | About USD 0.4M extra burn, covered by contingency; break-even +1 year |
| Prices 10% lower | Break-even 2033 |
| PKR weakens to 320 per USD | About 4% saving on PKR-denominated costs (HR, local works); imported equipment unchanged |
| AKAL engine not ready | Imported engine used; T2 cost up about 5%; no schedule effect |

## Chapter 9 — Governance, Risk and Compliance

The division is run as a gated programme. The Board releases money only at gates G1–G4, a monthly steering committee manages the risk register, and a dedicated compliance lead owns every licence, NOC and export file from M0.

### 9.1 Governance structure

| Body | Members | Cadence | Decides |
| --- | --- | --- | --- |
| Rapidev Board | Directors | Quarterly, plus each gate | Gate approvals, budget releases, JV and equity matters, T3 go / no-go |
| UAS Steering Committee | CEO (chair), CTA, CFO, Division Head, JV CTO | Monthly | Schedule, spend against plan, top-10 risks, partner issues |
| JV Board (Rapidev-Inphoenix) | 3 Rapidev, 2 Inphoenix | Quarterly | JV budget, reserved matters, IP |
| Design Review Board | Chief Engineer (chair), Technical Advisor (Dr Masud), leads | At each SRR, PDR, CDR, PRR | Technical readiness |
| Safety and Airworthiness Board | Lead Test (chair), Chief Engineer, Quality | Before every flight campaign | Permit to fly |

**Board reporting pack (quarterly):** milestone status against the master Gantt, spend against budget by phase and category, headcount, risk heat-map, order pipeline, compliance status.

### 9.2 Gate criteria

| Gate | Month | Pass criteria | Release |
| --- | --- | --- | --- |
| G1 | M3 | JV term sheet signed; one foreign ToT signed; Division Head plus 3 leads in post; MoDP filing accepted | R1: USD 1.40M |
| G2 | M9 | PDRs for Sentinel-Q and AgriSpray passed; Silicon Village lease agreed; JV incorporated; LEA letter of interest received | R2: USD 1.60M |
| G3 | M18 | Design freeze (T1); PRR passed; factory commissioned; ISO 9001 achieved; first LRIP order of 10 or more units | R3: USD 0.90M |
| G4 | M24 | Qualification complete; at least 25 aircraft delivered; order backlog of 60 or more units or one export contract | R4: USD 0.30M; FRP launch |

If a gate fails, the Board can re-plan (with up to 3 months' grace), reduce scope (for example, defer Cargo-M) or stop and keep the IP, team and datalink products already built.

### 9.3 Risk register (top 12)

| # | Risk | Likelihood | Impact | Owner | Mitigation |
| --- | --- | --- | --- | --- | --- |
| 1 | Delays in MoDP registration, DEPO export licences or MoD NOCs | High | High | Compliance Lead | File at M0; early MoDP engagement through LEA demos; legal counsel on retainer |
| 2 | ToT licence restricts export to KSA and Bahrain | Medium | High | CTA | Export clause non-negotiable; two candidates to M3 |
| 3 | Inphoenix JV dispute or key-person loss | Medium | High | CEO | Majority control; IP assignment; key-person lock-in; deadlock clause |
| 4 | Component embargo (motors, cells, GNSS, chips) | Medium | High | Supply Chain Lead | Dual sourcing; 6-month safety stock; local battery packs |
| 5 | VTOL flight-control or hybrid-engine immaturity | Medium | Medium | Chief Engineer | ToT baseline; HIL; staged envelope; imported engine fallback |
| 6 | Talent attrition to the Gulf and the state sector | High | Medium | Division Head | Retention plan (Ch 7); documented designs |
| 7 | Weak LRIP orders | Medium | High | BD Lead | Pre-orders from LEA demos; agri and cargo civil volume; gate G4 discipline |
| 8 | Silicon Village readiness (utilities, approvals) | Medium | Medium | Facilities Lead | Secondary site warm until M9 |
| 9 | FX and import-duty changes | Medium | Medium | CFO | USD-linked export pricing; STZA duty exemptions; hedging of large imports |
| 10 | Flight-test accident | Low | High | Lead Test | Safety board, insurance, restricted ranges |
| 11 | Cyber or data leak of LEA video or designs | Low | High | CISO (Rapidev) | Encrypted links; on-premise data; ISO 27001-aligned controls |
| 12 | Scope creep into MALE inside USD 5M | Medium | High | Board | T3 only on signed pre-funding |

### 9.4 Compliance and security

- **Compliance Lead** (hired by M1): owns the regulatory calendar covering PCAA registrations, MoDP, MoD NOCs, PTA and FAB spectrum, DEPO export, STZA licence, SECP (JV), customs and duty exemptions.
- **Export control:** an internal compliance programme; end-user certificates for every export; screening of partners and sanctions lists; MTCR awareness for T3.
- **Facility security:** access control, CCTV, visitor logs, controlled stores and personnel vetting as MoDP requires for defence work.
- **Information security:** segregated engineering network, PLM access rights, signed firmware, code escrow terms with partners.
- **Ethics and end use:** products are marketed as ISR, logistics and agri systems. Any request to weaponise a product needs a separate Board decision and its own legal review.

## Chapter 10 — Integrated Roadmap and First 90 Days

All three phases start together or overlap. Phase 3 planning begins at T0, Phase 2 begins at M3 while Phase 1 is still running, and LRIP begins at M18 while design continues to M24. Rapidev can therefore deliver its first production aircraft 18 months after Board approval.

### 10.1 Master roadmap

&#91;embedded content: Master roadmap · Jan 2027 to Dec 2029 · phases and Board gates G1–G4\]

The critical path runs through the ToT signature (G1), then Sentinel-V flight control, then the design freeze (G3). Facility fit-out has about 2 months of float against the M18 LRIP start.

### 10.2 Overlap logic

| Overlap | Months | Why it is safe |
| --- | --- | --- |
| Phase 1 and Phase 2 | M3–M6 | Phase 2 starts with requirements and concept work that needs the core team, not the finished JV |
| Phase 1 and Phase 3 planning | M0–M6 | Site search, permits and the facility brief need no design data |
| Phase 2 and Phase 3 fit-out | M9–M18 | Facility layout depends on product families, not detailed designs; manufacturing engineers join design reviews from M9 |
| Phase 2 and LRIP | M18–M24 | T1 designs are frozen first (M16–M19); Sentinel-V follows in LRIP lot 2 |

### 10.3 First 90 days (Jan–Mar 2027)

| Week | Action | Owner |
| --- | --- | --- |
| Before T0 (Nov–Dec 2026) | Board approval; R0 release; Division Head search launched; advisory contract with Dr Masud; NDA with Inphoenix | CEO, CTA |
| W1–W2 | Steering committee set up; compliance lead appointed; MoDP registration filed; NOC applications for test imports | CTA, Compliance |
| W1–W4 | Inphoenix term-sheet negotiation; independent valuer appointed | CEO, CFO |
| W2–W6 | ToT RFI to 6–8 candidates across Türkiye, China, Eastern Europe and the GCC; shortlist of 2 | CTA |
| W2–W8 | Interim lab fit-out at the existing premises; CAD and HIL seed purchases | Admin, Division Head |
| W3–W6 | NDAs and capability questionnaires to all 12 partners; site visits to Karachi (Sherani, Integrated Dynamics, Woot Tech, AKAL, ZGI) and Lahore (Fibre Craft) | Division Head |
| W4–W8 | Silicon Village site visit and LOI; secondary-site scan | Facilities, CFO |
| W4–W10 | MoUs with NUST (SMME, SEECS, CAE), IST and Air University (Islamabad and Kamra); first intern cohort selected | HR, Technical Advisor |
| W6–W12 | LEA requirement workshops (Islamabad Police, Punjab CTD, FC); KSA and Bahrain export discussions through DEPO and embassies | BD, CEO |
| W12–W13 | **Gate G1** pack to the Board | CTA |

## Annexes

### Annex A — Sources (opened or cited, as of 3 Nov 2026)

- [Arab News: PM hails drone progress, 60% locally made; Spark and Elevate programmes (Indus RAS Expo 2026)](https://www.arabnews.com/node/2651885/pakistan)
- [ProPakistani: Pakistan unveils first locally made UAV engine (Alsons / AKAL, Eurosatory 2026)](https://propakistani.pk/2026/06/26/pakistan-unveils-first-locally-made-uav-engine-for-drones/)
- [Unmanned Airspace: Pakistan issues new rules on UAS registration (Civil Unmanned Aircraft Rules 2024)](https://www.unmannedairspace.info/uncategorized/pakistan-issues-new-rules-on-uas-registration/)
- [Profit: Drone regulatory authority draft gets PM's nod](https://profit.pakistantoday.com.pk/2021/03/12/drone-regulatory-authority-draft-gets-pms-nod)
- [PIDE: Regulatory constraints on drone technology in Pakistan's agriculture](https://pide.org.pk/research/bring-on-drone-technology-in-pakistans-agriculture-regulatory-constraints/)
- [STZA: Capital Smart STZ (Silicon Village)](https://www.stza.gov.pk/?p=17097)
- [APP: BOI minister meets Silicon Village CEO](https://www.app.com.pk/?p=1238836)
- [Takshashila: Pakistan's UAV ecosystem (2025)](https://takshashila.org.in/content/publications/20250626-pakistan-drone-ecosystem.html)
- [The Defense Post: Pakistan–Afghan Taliban drone attacks (Mar 2026)](https://thedefensepost.com/2026/03/14/pakistan-afghan-taliban-drone-attacks/amp/)
- [Wikipedia: Integrated Dynamics](https://en.wikipedia.org/wiki/Integrated_Dynamics)
- [Robotics.press: Woot Tech Aerospace](https://robotics.press/companies/woot-tech-aerospace/)
- [PAeC: Sherani Engineering, a PAeC success story](https://pakaero.com.pk/sherani-engineering-a-paec-success-story/)
- [GAMI: licence to develop, manufacture and localise UAVs](https://www.gami.gov.sa/en/news/general-authority-military-industries-gami-grants-license-develop-manufacture-and-localize)
- [Breaking Defense: Saudi local defence production toward the 2030 goal](https://breakingdefense.com/2024/11/saudi-arabia-reveals-strides-in-local-defense-production-as-it-races-towards-ambitious-2030-goal)
- [Brandsynario: Syngenta Pakistan pilots drone spraying services](https://www.brandsynario.com/business/syngenta-pakistan-successfully-pilots-drone-spraying-services-for-local-farmers/)
- Partner websites supplied by the CTA: [Inphoenix Aviation](https://www.inphoenixaviation.com/), [NaqCode](https://naqcode.com/), [Honley](https://honleygroup.com/), [Sherani Engineering](https://sheraniengineering.com/), [ARRAD Technologies](https://www.arradtech.com/), [Alsons Group](http://www.alsonsgroup.com/), [Talons Dynamics](http://talonsdynamics.com/), [Fibre Craft Industries](https://fcicomposites.com/), [ZGI Robotics](https://www.linkedin.com/company/zgi-robotics/). These could not be opened from the research environment and must be checked during the M1–M3 audits.
- Universities: [NUST SMME Aerospace](https://smme.nust.edu.pk/departments/department-of-aerospace-engineering/), [NUST SEECS](https://seecs.nust.edu.pk), [NUST CAE](https://cae.nust.edu.pk/), [IST](https://www.ist.edu.pk/), [Air University](https://www.au.edu.pk/), [Air University Kamra](https://aack.au.edu.pk/).

### Annex B — Detailed product specifications

Outline specs are in Ch 2.1. The detailed specification sheets (one page per product: mission profiles, environment, interfaces, compliance matrix) are produced at SRR (M5–M8) and appended here at Gate G2.

### Annex C — Partner contact and capability sheets

A capability sheet per partner (contacts, facilities, certifications, MoDP status, key staff, audit score) is filled in during the M1–M3 audits. The template follows the scoring matrix in Ch 6.4. Contact details are held by the CTA office and kept out of this Board document.

### Annex D — Assumptions register

| # | Assumption | Value | Source / owner |
| --- | --- | --- | --- |
| 1 | Start date (T0) | 1 Jan 2027 | Board |
| 2 | Core budget | USD 5.0M, internal funding | Board |
| 3 | FX planning rate | PKR 282 / USD | CFO to confirm |
| 4 | Contingency | 10% (USD 0.5M) | CTA |
| 5 | Inphoenix equity | Below 50% (proposed 40%) | Inphoenix position, CEO |
| 6 | Primary site | Silicon Village, Capital Smart City (lease) | Board |
| 7 | Full-rate volume | 100 aircraft a year by M36 | Board |
| 8 | Gross margin | 35% blended | CTA estimate |
| 9 | Sustaining overhead from 2030 | USD 0.90–0.95M a year | CTA estimate |
| 10 | Salary bands | Ch 7.2, loaded factor 1.20–1.25 | HR to benchmark M1 |
| 11 | T3 MALE | Only on signed customer pre-funding | Board rule |
| 12 | Customer pre-funding | KSA, Bahrain; 30–50% advances; outside the USD 5M | CEO, BD |
| 13 | Regulation | Civil UA Rules 2024 in force; manufacturing licence regime by 2027 | Compliance, legal counsel |
| 14 | ToT sources | All countries allowed; screened per Ch 3.3 | Board |
| 15 | Cost estimate accuracy | ±25% (Class 4), firmed at G1 | CTA, CFO |

### Annex E — Inphoenix JV term-sheet outline

1. Parties, purpose and scope (T1/T2 airframes and flight systems).
2. Entity, name and registered office (Islamabad; Silicon Village from M9).
3. Shareholding: Rapidev 60%, Inphoenix 40% (option 51/49 with casting vote); milestone earn-out up to 5%.
4. Capital contributions and calls (cash, in-kind, IP licences); valuation method.
5. Board composition, quorum, reserved matters, deadlock.
6. Management: CEO (Rapidev nominee), CTO (Inphoenix nominee); key-person clauses.
7. IP: background and foreground IP; licences to and from the JV; confidentiality; code escrow.
8. Commercial: Rapidev as prime contractor for LEA and export; transfer pricing; exclusivity.
9. Non-compete and non-solicit (3 years).
10. Transfer restrictions: ROFR, tag-along, drag-along; exit and buy-out formula.
11. Compliance: export control, MoDP, anti-bribery.
12. Governing law (Pakistan); arbitration seat (Islamabad or Singapore).
13. Conditions precedent: valuation, regulatory approvals, Board approvals.

### Annex F — Site comparison

The weighted scoring of Silicon Village against the ICT industrial zone, STZA Islamabad Technology Park (Chak Shahzad) and Kamra / Taxila is in Ch 5.2. Silicon Village leads with 4.1 out of 5, then STZA Chak Shahzad (3.9), Kamra / Taxila (3.6) and the ICT industrial zone (3.1). Scores are re-run after site visits in M2–M6.

### Annex G — To-Do / Checklist

Tick items as they close. G.1 is the time view (monthly to M6, quarterly to M24, half-yearly to M36). G.2 holds the same work by department. Each item shows its due month and owner.

#### G.1 Phase-wise, time-based

**Pre-T0 (Nov–Dec 2026)**

- [ ] Board approves the division, the USD 5.0M budget and the gate rules (15–17 Nov) — Board
- [ ] R0 release of USD 0.80M — CFO
- [ ] Division Head search launched; retained recruiter — CEO, HR
- [ ] Advisory contract with Dr Jahanzeb Masud — CTA
- [ ] NDA with Inphoenix; JV kick-off meeting — CEO

**Phase 1 — M1 (Jan 2027)**

- [ ] UAS Steering Committee set up; monthly cadence — CEO
- [ ] Compliance Lead appointed; regulatory calendar issued — CTA
- [ ] MoDP registration filed; MoD NOC applications for test imports — Compliance
- [ ] Inphoenix term sheet tabled; independent valuer appointed — CEO, CFO
- [ ] ToT RFI to 6–8 candidates — CTA

**Phase 1 — M2 (Feb 2027)**

- [ ] Interim lab (about 3,000 sq ft) fitted out at the existing premises — Admin
- [ ] CAD/CFD seed licences, HIL bench and benchmark drones bought — Division Head
- [ ] NDAs and capability questionnaires sent to all 12 partners — Division Head
- [ ] Silicon Village site visit and LOI — Facilities, CFO
- [ ] University MoUs drafted (NUST, IST, Air University) — HR, Technical Advisor

**Phase 1 — M3 (Mar 2027): Gate G1**

- [ ] JV term sheet signed — CEO
- [ ] First foreign ToT agreement signed — CTA
- [ ] Division Head plus 3 leads in post — HR
- [ ] First intern cohort (8) starts — HR
- [ ] Phase 2 kick-off: requirement workshops scheduled — Chief Engineer
- [ ] G1 pack to the Board; R1 release of USD 1.40M — CTA, CFO

**Phase 1 — M4–M6 (Apr–Jun 2027)**

- [ ] HIL rig running; pilot integration of Rapidev datalink and GCS (M4) — Lead RF, Lead Software
- [ ] Facility concept design and capacity model (M4) — Facilities
- [ ] First flight of the integrated pilot (M5) — Lead Test
- [ ] Partner capability audits complete; scores updated (M6) — Division Head
- [ ] JV incorporated with SECP (M6) — CEO, Legal
- [ ] LEA demonstration: Islamabad Police, Punjab CTD, FC (M6) — BD
- [ ] Phase 1 close-out report to the Board (M6) — CTA

**Phase 2 and 3 — Q3 2027 (M7–M9): Gate G2**

- [ ] SRR and PDR for Sentinel-Q and AgriSpray-30; SRR for Sentinel-V — Chief Engineer
- [ ] Silicon Village lease signed; long-lead machines ordered — Facilities, CFO
- [ ] Sherani, Honley and ARRAD framework agreements — Supply Chain
- [ ] AKAL engine evaluation started — Lead Aero
- [ ] Export case files opened with DEPO (KSA, Bahrain) — BD, Compliance
- [ ] G2 pack to the Board; R2 release of USD 1.60M — CTA, CFO

**Q4 2027 (M10–M12)**

- [ ] Design centre move to Silicon Village complete — Admin
- [ ] CDR for Sentinel-Q; PDR for Sentinel-V and Cargo-M — Chief Engineer
- [ ] ISO 9001 certification — Lead Quality
- [ ] First flight of Sentinel-Q (M12) — Lead Test
- [ ] Factory fit-out contractor mobilised — Facilities

**Q1 2028 (M13–M15)**

- [ ] First flights of AgriSpray-30, Cargo-M and Sentinel-V — Lead Test
- [ ] Factory building handed over; machines installed — Facilities
- [ ] ERP/MES go-live — Production Manager
- [ ] Production hiring wave (technicians, Kamra pipeline) — HR

**Q2 2028 (M16–M18): Gate G3**

- [ ] Design freeze: Sentinel-Q (M16), AgriSpray-30 (M17) — Chief Engineer
- [ ] PRR passed; technical data package released — Chief Engineer
- [ ] First LRIP order of 10 or more units — BD
- [ ] G3 pack; R3 release of USD 0.90M; LRIP lot 1 starts — CTA, CFO

**Q3–Q4 2028 (M19–M24): Gate G4**

- [ ] Cargo-M (M19) and Sentinel-V (M20) design freeze — Chief Engineer
- [ ] LRIP lots 1–3 delivered (about 25 aircraft) — Production Manager
- [ ] AKAL engine supply agreement (M18–M20) — Supply Chain
- [ ] Qualification test reports complete — Lead Test
- [ ] G4 pack: FRP decision; R4 release of USD 0.30M — CTA, CFO

**H1 2029 (M25–M30)**

- [ ] Production rate at 6–8 aircraft a month — Production Manager
- [ ] AS9100D certification (M30) — Lead Quality
- [ ] First export Sentinel-V contract signed — CEO, BD
- [ ] AKAL equity or co-investment discussion opened — CEO

**H2 2029 (M31–M36)**

- [ ] 100 aircraft a year rate reached — Production Manager
- [ ] Training academy and MRO contracts running — Customer Support
- [ ] T3 MALE co-production decision (only with signed pre-funding) — Board
- [ ] Strategy refresh for 2030–2032 — CTA

#### G.2 Department-wise

**Technology**

- [ ] Product requirements baseline from LEA workshops (M5) — Chief Engineer
- [ ] Airborne datalink module, compact version (M6) — Lead RF
- [ ] Common Avionics Core architecture frozen (M8) — Lead Avionics
- [ ] GCS release 1.0 with STANAG 4586 interface (M14) — Lead Software
- [ ] Edge-AI detection model with NaqCode (M15) — Lead Software
- [ ] GNSS-denied navigation demonstration (M18) — Lead Avionics
- [ ] Environmental and EMC qualification campaigns (M20–M24) — Lead Test
- [ ] Patent filings: datalink, VTOL transition, spray control (M12, M24) — Chief Engineer
- [ ] Local content at 60% or more (M36) — Chief Engineer

**HR**

- [ ] Salary benchmark and grade structure (M1) — HR
- [ ] Division Head (M1), 5 leads (M3), 6 engineers (M5) — HR
- [ ] University MoUs signed with NUST SMME, SEECS, CAE, IST, AU Islamabad and AU Kamra (M3) — HR, Technical Advisor
- [ ] Intern cohorts each February and July from M3 — HR
- [ ] Retention scheme: JV incentive units, retention bonuses (M6) — HR, CFO
- [ ] Headcount at 36 (M12), 63 (M18), 78 (M24), about 97 (M36) — HR
- [ ] PCAA pilot licences, IPC and AS9100 auditor training (M9–M24) — HR, Lead Quality

**Finance**

- [ ] Division cost centre and project codes (M0) — CFO
- [ ] Independent JV valuation (M2) — CFO
- [ ] Class 3 budget at G1 (M3) — CFO, CTA
- [ ] Gate releases R0–R4 (Nov 2026, M3, M9, M18, M24) — CFO
- [ ] Quarterly Board financial pack — CFO
- [ ] STZA tax and duty exemptions registered (M9) — CFO
- [ ] Bank running-finance line for working capital (M15) — CFO
- [ ] Export advance-payment and guarantee structures for KSA and Bahrain (M12) — CFO, BD

**Infrastructure and Admin**

- [ ] Interim lab fit-out at the existing premises (M2) — Admin
- [ ] Silicon Village LOI (M2), lease (M9) — Facilities
- [ ] Secondary site kept warm until M9 — Facilities
- [ ] Design centre move (M9–M12) — Admin
- [ ] Factory fit-out, utilities, battery store, security (M12–M18) — Facilities
- [ ] Flight-test range MoUs and NOCs (M6, renewed yearly) — Compliance
- [ ] MoDP registration (filed M1), DEPO export licences (from M9) — Compliance
- [ ] Insurance: flight test, product liability, property (M5) — Admin
- [ ] ISO 9001 (M12), AS9100D (M30) — Lead Quality
