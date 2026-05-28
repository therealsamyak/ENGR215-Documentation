# Aegis Swarm — Investor Pitch

> A disposable-first underwater drone swarm that gives commercial ships real-time lateral visibility they have never had.

## The Problem

Commercial maritime transport carries 80% of global trade. Every single day, massive vessels worth hundreds of millions of dollars navigate through congested chokepoints: the Suez Canal, the Straits of Malacca, the Panama Canal, the Bosporus. Submerged debris, shifting obstacles, and unexploded ordnance sit in their path.

And these ships are completely blind to hazards on their sides.

Hull-mounted sonar looks forward and down. That is it. Anything submerged a kilometer or two to port or starboard goes undetected until it is too late. There is no lateral visibility. Zero.

When the *Ever Given* ran aground in the Suez Canal in 2021, it blocked global trade for six days. Losses hit $9.6 billion per day. The ship owner's direct costs ran into the hundreds of millions. Even with full insurance, the vessel sat in dry dock for months. Insurance pays for repairs. It does not pay for the contracts you lost, the routes you missed, or the customers who found someone else.

This is not a rare event. It is a structural blind spot that every commercial vessel on the water lives with every single transit.

### What operators do today

1. **Nothing.** Accept the risk and pay elevated insurance premiums. This is what most do.
2. **Hire survey vessels** at $20,000 to $50,000 per day. Too expensive for routine use.
3. **Buy a traditional AUV** for $250,000+. Then hesitate to deploy it in the exact hazardous waters they bought it to scout, because losing a $250,000 drone is a major financial loss.
4. **Wait for military escorts or cleared windows.** Days of delays, burned fuel, wasted crew time.

None of these are real solutions. They are Band-Aids on a problem no one has solved at the right price point.

## The Solution

**Aegis Swarm** is a network of 10 to 20 low-cost, relay-linked underwater drones that form a real-time 2 km protective perimeter around a vessel.

Instead of one expensive autonomous robot doing everything itself, we distribute the problem. The drones are sensors. They follow predefined search paths, relay acoustic imaging back to a single bridge-mounted command unit, and the heavy AI processing happens on the ship. When the system detects an anomaly, the crew gets an immediate alert and can take manual remote control of individual drones to investigate.

The drones are cheap enough to be disposable. If one is lost to debris or a hazard, the swarm recalibrates. The other 19 keep working. You replace the one drone and move on. An entire Aegis Swarm costs less than 10% of a single military-grade AUV.

No specialized ROV pilots. No cranes. The drones are stored in a compact launch-and-recover rack on deck. Multiple swarms can be loaded on the same ship. Swarm size adjusts based on route risk.

This is not a better AUV. It is a fundamentally different architecture: distributed, disposable, real-time.

## Market

The target customer is fleet operators and marine insurance risk officers at global shipping conglomerates. Maersk runs 700+ vessels. MSC runs 800+. Euronav. CMA CGM. Cruise lines like Carnival and Royal Caribbean. Insurance companies managing luxury yachts and passenger ships.

One enterprise contract can cover hundreds of vessels. Revenue scales linearly with fleet count. The same hardware and software stack extends to adjacent markets:

- **Cruise ships** — thousands of passengers, even stronger safety incentive
- **Luxury yachts** — near-zero tolerance for any hull damage
- **Offshore oil and gas** — continuous perimeter monitoring need

Every major shipping chokepoint on Earth is a recurring hazard zone. Port approaches in developing nations are often poorly charted. Any vessel transiting any of these routes is a potential customer.

This is a global problem with no existing product in the price bracket we are targeting.

## Business Model

Pure leasing. No upfront hardware purchase. Customers pay a monthly fee that covers everything: drone hardware (10 to 20 units), the bridge command unit, detection software, maintenance, and replacement drones.

**Pricing: $8,000 to $15,000 per month per vessel**, depending on swarm size and route risk.

One day of a survey vessel costs $20,000 to $50,000. A full month of Aegis Swarm costs less than a single day of the traditional alternative. For a fleet of 50+ vessels, the monthly total is a rounding error compared to the cost of a single grounding.

Leases run on annual contracts with monthly billing. The detection software improves with every deployment. More data means better models, fewer false positives, and higher accuracy over time. Customers keep paying because hazard detection is not one-time. Ships deal with shifting debris, uncharted obstacles, and congested ports on every transit.

Why leasing instead of selling? Traditional AUVs require a $250,000+ capital purchase, and that is a hard sell for a new product in a conservative industry. Leasing turns a capital decision into an operational one. It shifts hardware risk from the customer to us, which is where it belongs, because the drones are designed to be disposable anyway.

### Unit economics logic

- A full year of Aegis Swarm on one vessel costs roughly the same as one week of a survey vessel
- Even when insurance covers collision damage, the vessel sits in dry dock for months — lost revenue and missed contracts that insurance does not replace
- Prevention is cheaper than a payout, and ship operators know this

## Competitive Landscape

| Player | What they do | Price |
|---|---|---|
| General Dynamics / Knifefish | Navy UUV for buried mines | $10M–15M per unit |
| Kongsberg / HUGIN AUV | Deep-sea survey and research | $44M+ contracts |
| Bluefin Robotics / Bluefin-21 | Salvage and UXO removal | $500K+ |

These are exquisite machines built for deep-sea research and high-end military use. Titanium housings. Expensive onboard AI. Commercial shipping does not need any of that. Current AUVs collect data and are retrieved to download it. They do not provide real-time alerts. If a $250K drone breaks, the mission ends.

Aegis Swarm is the only product that sits in the gap between "do nothing" and "spend a quarter million on something you are afraid to use."

## Why Now

Three forces are converging:

1. **Drone hardware is cheap enough.** The component cost curve has finally made sub-$5K underwater units viable. This was not true five years ago.
2. **Insurance incentives are aligning.** Marine insurers are actively looking for technology that reduces claims exposure. Premium reductions for Aegis-equipped vessels create a financial pull that regulation does not.
3. **High-profile incidents keep happening.** The *Ever Given* was not the first and will not be the last. Each event sharpens the industry's willingness to try something new.

## Defensibility

The drones themselves are not deeply patentable. Cheap underwater hardware is accessible. Our defensibility comes from the full system and the data flywheel:

- **Proprietary sensor integration** tuned for shallow, noisy coastal waters
- **Swarm coordination software** that works in GPS-denied environments
- **Detection AI that improves with every deployment** — more field data means better models at near-zero marginal cost
- **Regulatory certifications and insurer relationships** that take time to build
- **Manufacturing cost advantages** that compound with volume
- **Operational data from real deployments** that competitors cannot replicate without going through the same cycle

A large defense contractor could enter the space, but they tend to build expensive, over-engineered systems. Our edge is speed, cost discipline, and focus on a narrow commercial use case that big players historically ignore.

## The Team

**Samyak Kakatur — CEO.** Owns fundraising, customer acquisition, insurer partnerships, and the bridge command unit's customer-facing software. Production cloud deployment background (NextJS, AWS ECS/RDS/Amplify, authentication) at Sidecar Health. IoT Systems concentration at UCLA. The only founder with explicit business and marketing motivation.

**Michael Xiong — CTO.** Owns the full technical architecture: drone hardware, swarm protocol, bridge command unit, simulation infrastructure. Built MuJoCo simulation environments at Farm-ng for autonomous rover testing. Current research at UCLA on cross-platform ML benchmarking (HoliBench) spanning GPU servers to edge devices. Incoming GM Cruise intern working on sensor health for autonomous vehicles. Embedded firmware experience at SproutLabs.

**Daniel Luzzatto — AI & Engineering Lead.** Owns detection software, sonar signal processing, model architecture, and scientific validation. Automated acoustic calibration at FUSMobile (C++/Python). Control systems and sensor fusion research at Technion's Flow Control Lab. Peer-reviewed publication. MEMS sensor validation at STMicroelectronics. Deep learning on temporal/signal data with physically grounded augmentation.

**Sam Seban — COO & Product Lead.** Owns pilot planning, deployment logistics, product requirements, and swarm coordination engineering. SLAM and autonomous navigation from Formula Student Technion. Led a 5-engineer software team at Technion Rocketry Club. Shipped a consumer product at Marions-Nous with a measured 14% sales lift. Multilingual (French, English, Hebrew, Spanish) — directly useful for European and Mediterranean shipping customers.

Four UCLA M.Eng students in Robotics, IoT, and Autonomous Systems. The team covers the full stack: simulation, embedded firmware, acoustic sensing, signal processing ML, SLAM, cloud deployment, customer-facing software, and business ownership. No one is here by default.

## Roadmap

**Phase 1 — Prototype and Simulation (Months 1–6)**
Build the simulation environment. Validate swarm coordination algorithms. Test detection models on synthetic underwater data. Build the first drone prototype.

**Phase 2 — Controlled Water Trials (Months 6–12)**
Test single-drone and small-swarm deployments in controlled water environments. Validate sensor performance, relay communication, and detection accuracy. Begin maritime advisor engagement for compliance and certification planning.

**Phase 3 — Pilot Fleet Deployment (Months 12–18)**
Deploy on 2–3 pilot vessels through partnerships with a shipping operator or cruise line. Collect real deployment data. Refine detection models. Build the insurer partnership track (premium reductions for Aegis-equipped vessels).

**Phase 4 — Scale (Months 18–30)**
Expand from pilot fleet to enterprise contracts. Hire field operations, BD lead, and ML data engineer. Manufacturing scale-up to reduce unit costs. Target break-even on operating costs.

## The Ask

We are raising a pre-seed round to fund Phase 1 and Phase 2: prototype development, simulation infrastructure, controlled water trials, and maritime compliance groundwork.

The capital gets us to a working demo in water with real sensor data flowing through the bridge command unit. That is the milestone that unlocks pilot partnerships and insurer conversations.

We are looking for investors who understand that the best hardware companies do not start with the most expensive hardware. They start with the cheapest hardware that solves the problem.

## Closing Thought

Ships have navigated the world's most dangerous waters blind to their sides for over a century. The technology to fix this exists today. No one has packaged it at the right price point for the people who need it.

Aegis Swarm is that package. A 2 km underwater perimeter. Real-time alerts. Disposable drones. A monthly lease that costs less than one day of the alternative.

The question is not whether commercial ships need lateral underwater visibility. They do. The question is who builds the system that makes it affordable enough to actually deploy.

We intend to be that company.
