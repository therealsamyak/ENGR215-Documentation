# Aegis Swarm — Market Analysis

**Team:** Samyak Kakatur (CEO, Customer Acquisition, Insurer Partnerships, Bridge Software), Daniel Luzzatto (AI & Engineering Lead, Detection/Sonar/Signal Processing), Sam Seban (COO & Product Lead, Pilots, Deployment, Logistics, Swarm Coordination), Michael Xiong (CTO, Technical Architecture, Simulation)

**Date:** Spring 2026


## 1. Target Customer

### Primary Customer

Safety and Operations Managers, along with fleet operations executives, at Tier-1 global shipping conglomerates: Maersk, MSC, CMA CGM, Euronav, and similar operators. These people own the day-to-day decision about what safety equipment goes on their vessels. They report to VP-level operations leadership and are accountable for incident rates, regulatory compliance, and per-voyage cost efficiency.

The sweet spot within this group is operators of high-value vessels transiting known chokepoints: ULCC and VLCC oil tankers, LNG carriers, and ultra-large container ships (20,000+ TEU). A single grounding or collision on one of these vessels produces direct costs in the hundreds of millions. The Ever Given incident in the Suez Canal blocked traffic for six days; estimated global trade losses ran to roughly $9.6 billion per day, and the vessel owner faced repair, salvage, and liability costs that insurance did not fully cover.

### The Problem from the Customer's View

Hull-mounted sonar looks forward and downward, not laterally. A ship traveling through a congested strait or poorly charted port approach has a visibility gap extending 1 to 2 kilometers to port and starboard. Hazards in that gap include submerged debris, shifting sandbanks, unexploded ordnance from past conflicts, and container stacks that fell from other vessels. Existing tools like ECDIS chart overlays, AIS tracking, and VTS (Vessel Traffic Services) help with known, charted, or transponder-equipped objects. They do not help with uncharted underwater hazards that moved since the last survey.

The consequences are not hypothetical. Groundings and collisions cause dry dock repairs (weeks or months of downtime), missed charter contracts, cargo damage, environmental liability, and crew safety incidents. Insurance premiums for vessels with prior incidents rise significantly and stay elevated for years.

### Decision-Making Unit

The primary buyer is the fleet operations executive who approves equipment procurement and lease agreements. The internal champion is typically the Safety Manager or DPA (Designated Person Ashore) who can argue for the system on risk-reduction grounds. A secondary buyer is the Marine Insurance Risk Officer, or the P&I club / hull underwriter directly, who benefits from lower claims frequency and may offer premium reductions to vessels equipped with validated safety technology.

### Why This Segment First

High-value vessels at chokepoints have the most to lose and the clearest ROI. A one-month Aegis Swarm lease ($8,000 to $15,000) costs less than a single day of hiring a survey vessel ($20,000 to $50,000). The math is immediate and obvious for fleet operators running ULCCs or LNG carriers through the Strait of Hormuz, the Malacca Strait, the Suez Canal, or the approaches to major ports like Rotterdam and Singapore. Starting with this segment also builds credibility quickly: if Maersk or Euronav adopts the system, mid-tier operators follow.


## 2. Customer Acquisition Strategy

This section outlines our phased go-to-market approach. We lead with insurer partnerships rather than direct enterprise sales, because a marine insurer endorsing the system (and pricing it into premium reductions) does more to establish trust than any pitch deck.

### Phase 1: Insurer Partnerships as Market Entry

Before selling to a single ship, we partner with one or two P&I clubs or hull underwriters. The arrangement works as follows: the insurer helps fund or subsidize controlled water trials to validate the technology. In return, the insurer gets early access to performance data and can begin modeling how Aegis Swarm affects claims frequency for vessels transiting high-risk routes.

This phase gives us three things we cannot buy: technical validation in real conditions, an insurer's name attached to the product, and a relationship with the insurer's fleet operator clients. When we approach a fleet operations executive and can say "your P&I club asked us to call you," the conversation starts from trust, not cold outreach.

### Phase 2: Pilot Fleet Program

With insurer validation in hand, we place Aegis Swarm systems on two to three vessels operated by one or two shipping companies. Pilots are structured as three-month deployments during which the vessel transits a known high-risk route. We collect data on detections, false alarm rates, crew interaction with the bridge command unit, and any near-miss events attributable to swarm coverage.

Pilot pricing is set at or below $8,000 per month per vessel to lower the commitment barrier. The goal is not revenue at this stage; it is a documented case study with real performance numbers and a testimonial from a named fleet operator.

### Phase 3: Fleet-Wide Enterprise Rollout

Pilot results feed into an enterprise proposal for fleet-wide deployment. The proposal includes per-vessel lease pricing (tiered by route risk and swarm size), replacement and maintenance terms, and an ongoing data-sharing arrangement that lets the fleet operator benefit from detection improvements across the entire Aegis Swarm user base.

### Acquisition Funnel

| Stage | Activity | Goal |
|---|---|---|
| Lead generation | Insurer introductions, trade conference presence, targeted LinkedIn outreach to fleet ops executives | Identify operations leaders at top-20 global carriers |
| Qualification | Initial call to assess vessel types, transit routes, current safety systems, incident history | Confirm fit: high-value vessels, chokepoint routes, history of or exposure to grounding/collision risk |
| Conversion | Pilot proposal with insurer co-sign, three-month deployment, fixed low cost | Secure two to three pilot vessels within first year |
| Expansion | Case study from pilot, premium reduction data from insurer partner, enterprise fleet proposal | Expand from pilot vessels to fleet-wide contracts |
| Retention | Ongoing detection improvements via data flywheel, annual contract renewals with volume discounts, insurer incentive alignment | Multi-year contracts, low churn |

### Why Customers Discover and Trust the Solution

Discovery happens through insurer recommendation (Phase 1), industry conference visibility, and word of mouth among fleet operations circles once pilots are running. Trust builds in layers: the insurer's involvement signals credibility, the pilot program demonstrates the product works, and the lease model means the customer is not locked into a large capital purchase. If the system does not perform, the customer cancels the lease. That low-risk structure is itself a selling point.


## 3. Competitive Positioning

### Direct Competitors

These are companies building underwater vehicles used in some commercial and defense settings. None target the disposable-swarm, real-time-perimeter use case for commercial shipping.

**General Dynamics Knifefish:** A Navy-designed UUV for detecting buried mines. Unit cost is $10 million to $15 million. Built for military minehunting, not routine commercial vessel protection. Requires specialized launch and recovery infrastructure.

**Kongsberg HUGIN AUV:** Deep-sea survey and research platform. Recent contracts valued at $44 million and above. Designed for long-duration scientific surveys, not real-time ship escort. Requires trained operators and support vessels.

**Bluefin Robotics Bluefin-21:** Modular AUV used in salvage, UXO detection, and commercial surveys. Unit cost starts around $500,000. Not disposable; loss of one unit is a significant financial event.

### Indirect Competitors and Substitutes

- **ECDIS / SOLAS chart data:** The standard electronic chart system on commercial vessels. Shows charted depths and known hazards. Does not detect uncharted or recently shifted obstacles.
- **VTS and AIS:** Port traffic control and ship-tracking systems. Manage known, transponder-equipped traffic. Do not see submerged debris or UXO.
- **Survey vessels:** Dedicated ships that perform bathymetric surveys before a vessel transits an area. Cost $20,000 to $50,000 per day. Not feasible for routine use on every transit.
- **Military escorts and cleared windows:** In some regions, naval forces clear channels of mines or hazards. Availability is limited, not guaranteed, and not under the ship operator's control.
- **Status quo:** Accept the risk, carry elevated insurance premiums, and hope.

### Comparison Table

| | Aegis Swarm | Knifefish | HUGIN AUV | Bluefin-21 | Survey Vessel | ECDIS/VTS |
|---|---|---|---|---|---|---|
| Unit cost | Low (disposable) | $10M-$15M | $1M+ | $500K+ | $20K-$50K/day | Standard equipment |
| Real-time alerts | Yes | No | No | No | No | No |
| Bridge-integrated | Yes | No | No | No | No | Yes (charted data only) |
| Specialized crew | No | Yes | Yes | Yes | Yes | No |
| Disposable/replaceable | Yes (individual drones) | No | No | No | N/A | N/A |
| Model | Lease ($8K-$15K/mo) | Government sale | Enterprise sale | Enterprise sale | Day rate | Included in vessel systems |
| Target user | Commercial shipping | Navy | Research/defense | Defense/commercial | Port authorities/navies | All vessels (standard) |

### Why Customers Choose Aegis Swarm

We occupy a position that existing options do not: low-cost, real-time, bridge-integrated, and designed for routine commercial use. The closest substitute is doing nothing and accepting risk. Our lease pricing makes the decision comparable to a minor operational expense rather than a capital project.

### Defensibility

The moat is not the drone hardware alone. It is the combination of (a) insurer relationships and premium-reduction certifications that create a financial incentive to use Aegis Swarm, (b) a data flywheel where more deployments improve detection models, and (c) fleet-level contracts with annual commitments. Competitors building a single expensive AUV cannot replicate the swarm economics. New entrants would need to replicate the insurer channel and the operational track record, which takes years.


## 4. Entrepreneurial Selling Strategy

### Core Value Proposition

Aegis Swarm gives your crew real-time underwater visibility to port and starboard for less than the cost of one day of a survey vessel. If a drone is lost, the swarm recalibrates and keeps working. No specialized pilots, no capital purchase, no changes to your vessel's structure.

### Key Selling Points

1. **Cost:** One month of Aegis Swarm costs less than one day of a survey vessel. For a VLCC operator, this is a rounding line item on a voyage that generates millions in revenue.
2. **Real-time detection:** The swarm provides continuous acoustic imaging and relays alerts to the bridge while the vessel is underway. This is not a pre-transit survey; this is coverage during transit.
3. **Disposable architecture:** Losing a $500 drone is an operational non-event. Losing a $500,000 AUV is a budget incident. The swarm model means the system degrades gracefully, not catastrophically.
4. **No specialized crew:** The bridge command unit presents alerts. Crew can inspect anomalies manually if they choose. No ROV pilot certification required.
5. **Lease model:** No capital expenditure. Monthly billing, annual contracts. Cancel if it does not work. The financial risk to the customer is low.

### Objections and Responses

**"We already have sonar and chart systems."** Hull-mounted sonar looks forward and down, not laterally. ECDIS shows charted data, which can be months or years out of date in areas with shifting seabeds. Aegis Swarm covers the lateral gap with real-time data.

**"This is too expensive for our operations budget."** The lease costs $8,000 to $15,000 per month. A single grounding incident on a ULCC can cause hundreds of millions in damages and weeks of downtime. The monthly cost is negligible compared to the downside. If your P&I club offers a premium reduction for carrying the system, it can partially or fully offset the lease.

**"The technology is unproven."** That is why we structure pilot deployments: three months, one to two vessels, at reduced pricing, with full data transparency. You see the results before committing to fleet-wide rollout. Our insurer partner validates the performance data independently.

**"What happens when drones fail?"** The swarm recalibrates. Individual drone loss is expected and accounted for. Replacement drones ship to the next port of call. The system is designed around partial failure, not around perfect reliability of each unit.

**"Our crew doesn't have time for more systems."** The bridge unit pushes alerts to existing bridge displays. There is no new piloting task. Crew respond to alerts the same way they respond to existing sonar or radar contacts: by reviewing the data and deciding whether to adjust course.


## 5. Marketing with Limited Resources

As a pre-revenue startup, we cannot afford broad advertising campaigns. Our marketing is founder-led, targeted, and designed to produce one high-quality conversation at a time.

### Founder Outreach

Direct outreach by the CEO (Samyak Kakatur) to fleet operations executives and marine insurance risk officers. Channels include LinkedIn messages, email introductions through mutual contacts, and warm referrals from UCLA's professional network. Each outreach is specific to the recipient's fleet composition and route risk profile, not a generic pitch. A message to a Maersk operations lead references the specific chokepoint routes their ULCC fleet transits and the incident history on those routes.

### Insurer Co-Marketing

Once an insurer partnership is in place, the insurer becomes a distribution channel. P&I clubs regularly communicate with their member fleets about risk mitigation tools. Being featured in a P&I club's recommended safety technology list is more credible than any advertisement we could produce ourselves.

### Pilot Case Studies

After the first two to three pilot deployments, we produce a short, data-backed case study: vessel type, route, number of detections, false alarm rate, crew feedback, and insurer assessment. This document becomes the primary sales asset. We do not publish vague testimonials. We publish specific numbers.

### Maritime Trade Press and Industry Conferences

Targeted press coverage in maritime industry outlets (TradeWinds, Lloyd's List, The Maritime Executive) and presence at key conferences (Posidonia, Nor-Shipping, SMM). These are where fleet operations executives and marine insurers gather. A conference demo of the bridge command unit with simulated swarm data is worth more than a booth with brochures.

### Technical and LinkedIn Content

Short-form posts on LinkedIn covering specific topics: lateral sonar gaps, disposable swarm economics, real-world grounding incident analysis. Written by team members with technical depth, not by a marketing agency. The audience is the operations and engineering community in maritime, not a general tech crowd.

### UCLA and Professional Networks

Use UCLA's engineering and business alumni network for introductions to maritime industry professionals. Engage with the Los Angeles maritime community, including the Port of LA/Long Beach ecosystem, for local pilot opportunities and advisor relationships.

### Maritime Industry Advisors

Recruit one to two advisors with operational experience in commercial shipping fleet management or marine insurance underwriting. Their endorsement and network access accelerates credibility with target buyers who otherwise have no reason to take a call from a student-founded startup.


## References

- International Maritime Organization. "Hydrographic data, nautical charts and nautical publications." https://www.imo.org/en/OurWork/Safety/Pages/Charts.aspx
- International Maritime Organization. "Vessel Traffic Services." https://www.imo.org/en/OurWork/Safety/Pages/VesselTrafficServices.aspx
- U.S. Coast Guard Navigation Center. "Vessel Traffic Services." https://www.navcen.uscg.gov/vessel-traffic-services
- NOAA Office of Coast Survey. "National Bathymetric Source." https://nauticalcharts.noaa.gov/learn/nbs.html
- General Dynamics Mission Systems. "Bluefin Robotics Unmanned Underwater Vehicles." https://gdmissionsystems.com/underwater-vehicles/bluefin-robotics
- Naval Technology. "Kongsberg Maritime wins multiple contracts for HUGIN AUV." https://www.naval-technology.com/news/kongsberg-maritime-contracts-hugin-auv/
- University of Connecticut Marine Sciences. "Vessel Rates." https://marinesciences.uconn.edu/mstc/vesselops/rates/
- Global Marine Surveys. "Survey Rates." https://globalmarinesurveys.com/rates.html
