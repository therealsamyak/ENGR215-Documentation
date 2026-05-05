## **Part 1: Competitive Landscape**

**Direct competition:**

| Company/Product | What they do | Business Model/Pricing |
| :---- | :---- | :---- |
| General Dynamics/Knifefish | Navy UUV for buried mines. | Cost: $10M-15M per unit |
| Kongsberg / HUGIN AUV | Deep-sea survey & research. | $44M+ contracts. High overhead. |
| Bluefin Robotics / Bluefin-21 | Salvage & UXO removal. | Modular/Commercial. $500k+. |

**Indirect Competitors/Substitutes:**

* Regulatory: Ships rely on SOLAS charts and VTS (Shore-side radar). Both provide zero real-time submerged visibility.  
* Behavioral: Avoidance. Ships wait for military escorts or "cleared" windows, incurring massive fuel and labor costs during delays.

## **Part 2: Customer Reality Check**

**Current Behavior:** Operators treat underwater hazards as an "external risk." They rely on passive navigation and accept higher war-risk insurance premiums rather than investing in on-board hardware.

**Barriers to Change:**

* Regulatory Inertia: International law mandates updated charts but not active scouting; operators rarely adopt non-mandated workflows.  
* Cost & Complexity: Current AUVs ($1M+) are too expensive to "risk" in commercial collisions and require specialized technicians/cranes that cargo ships don't carry.

**Evidence:**

* Regulatory: IMO SOLAS (2026) requires electronic charts (ECDIS) but ignores active scouting.  
* Market Gap: Multimillion-dollar Navy contracts prove a "high-cost, low-volume" bias; commercial rate sheets show $150/hr survey vessels but zero disposable drone options.

## **Part 3: Five Forces Analysis**

**Rivalry among competitors \- Medium.** Competitors exist, but current Drone companies are very expensive (Anduril, Lockheed, other startups). Additionally, the segment is projected to grow a lot over the next 10 years, so more will inevitably join.

**Buyer power \- High.** Unmanned drones, especially underwater, are in high demand among major military powers. As long as there is conflict, there will always be a need to gain an edge.

**Supplier power \- Medium.** Some parts are very cheap, like recycled housings for components, but the tech components themselves could be hard to get. Computer parts are used in every single industry, and the bigger players like Apple, Samsung, etc. always get higher priority, and can buy at cheaper prices due to their larger scale.

**Threat of Substitutes \- Low.** Sonar exists, but Sonar has existed for a while, and there are ways to ‘fake’ it or get around it. There is a reason innovation is happening in this space. Additionally, there are undersea unmanned vehicles larger than a drone, but those are considerably more expensive.

**Threat of new entrants \- High.** This space is growing rapidly, and is dominated by startups. However, big players like Lockheed, Boeing, and other military contractors are sure to jump in either through acquisition or creating their own products as the space becomes more profitable.


## **Part 4: Differentiation**

**What makes your solution meaningfully different from existing options?**

We use a network of 10 to 20 cheap, relay-linked drones instead of one super expensive autonomous robot. The drones just follow hardcoded paths and act as sensors. All the heavy AI computing happens on the ship's bridge. This keeps costs so low that an entire swarm is still significantly cheaper than a traditional military AUV. 

**Why would a customer choose your solution over competitors or substitutes?**

Right now, ships either wait days for military sweepers or pay up to $50,000 a day for specialized survey vessels. Even if they buy existing undersea drones, those cost a lot of money and operators are scared to actually risk them in dangerous waters. Our drones are built to be disposable. If one gets destroyed, the others keep working, and you only have to replace the one drone that broke. 

**Is your solution slightly better, or meaningfully better?**

Our solution fixes a massive blind spot. Today, ships rely on hull mounted sonar that only looks forward and down. They are completely blind to hazards a kilometer or two away on their sides. Aegis Swarm acts like an extended nervous system that gives the ship a 2 km protective bubble.

## **Part 5 \- Defensibility**

**What prevents competitors from copying you?**

At first, not much if it is only “cheap drones for mine detection.” The defensibility would need to come from execution, from multiple factors: proprietary sensor integration, reliable swarm coordination, low-cost manufacturing, operational data from real deployments, regulatory certifications, and relationships with insurers/shipping companies etc. The competitive advantage would be less about the drones themselves but more about the full system: launch/recovery, communications, detection software, reliability to harsh environments/proven reliability on the field.

**What happens if a large company enters your space?**

A large company could outspend us, but they may also move slowly and build expensive over-engineered systems. Our advantage would be speed, lower cost, and focus on a narrow use case: disposable or semi-disposable mine/object detection around commercial vessels. A large company could also become an acquirer, partner, or distribution channel if we prove demand.

**Are you dependent on another platform, company, or ecosystem to operate?**

Partially. We may depend on sensor suppliers, drone component manufacturers, satellite/radio communication providers, ship integration partners, and government/maritime regulatory approvals. For defense customers, we may also depend on procurement processes and export controls. To reduce this risk, we should design the system to be hardware-flexible, avoid single-source suppliers, and keep the core software/control stack in-house.

## **Part 6 \- Key risk**

The single biggest structural risk is that commercial shipping customers may not feel direct ownership of the problem, even if they agree the risk is serious.

For example, oil tankers, LNG carriers, and other expensive vessels already operate within a broader safety ecosystem: route planning, maritime advisories, port authorities, insurers, convoy systems, and government-led security when risks are high. They already have a variety of measures that are taken to prevent potential safety issues (physical barriers, alarms, monitors etc.). Because of this, ship operators may think: “This is a real danger, but it is already managed through existing systems, so we do not need to buy additional onboard hardware ourselves.”

That creates a business risk: the product may be technically useful, but still hard to sell if customers see it as an external safety issue rather than an onboard operational need. To overcome this, we would need to show a clear commercial benefit, such as reducing delays, lowering insurance risk, avoiding rerouting costs, improving crew safety, or giving ship operators more control in uncertain waters.

## **Appendix:**

### **Direct Competitors**

* General Dynamics Mission Systems. “General Dynamics (GD) Arm Wins $11.8M Deal for Knifefish UUV.” Yahoo Finance.  
  https://finance.yahoo.com/news/general-dynamics-gd-arm-wins-164300007.html  
* Kongsberg Maritime. “Kongsberg Maritime wins multiple contracts for HUGIN AUV.” Naval Technology.  
  https://www.naval-technology.com/news/kongsberg-maritime-contracts-hugin-auv/  
* General Dynamics Mission Systems. “Bluefin Robotics Unmanned Underwater Vehicles.”  
  https://gdmissionsystems.com/underwater-vehicles/bluefin-robotics

### **Indirect Competitors / Substitutes**

* International Maritime Organization. “Hydrographic data, nautical charts and nautical publications.”  
  https://www.imo.org/en/OurWork/Safety/Pages/Charts.aspx  
* International Maritime Organization. “Vessel Traffic Services.”  
  https://www.imo.org/en/OurWork/Safety/Pages/VesselTrafficServices.aspx  
* U.S. Coast Guard Navigation Center. “Vessel Traffic Services.”  
  https://www.navcen.uscg.gov/vessel-traffic-services  
* NOAA Office of Coast Survey. “National Bathymetric Source (NBS).”  
  https://nauticalcharts.noaa.gov/learn/nbs.html  
* MarineTraffic. “Global Ship Tracking Intelligence | AIS Marine Traffic.”  
  https://www.marinetraffic.com

### **Supporting Cost Evidence**

* University of Connecticut Marine Sciences. “Vessel Rates.”  
  https://marinesciences.uconn.edu/mstc/vesselops/rates/  
* Global Marine Surveys. “Survey Rates.”  
  https://globalmarinesurveys.com/rates.html

### **Extra Context Sources**

* U.S. Department of Commerce, International Trade Administration. “Maritime Services Trade Data.”  
  https://www.trade.gov/maritime-services-trade-data

### **Key Risk**

* Best Management Practices (BMP) for Maritime Security, published by major shipping industry associations including ICS and BIMCO.  
  https://www.ics-shipping.org/wp-content/uploads/2025/03/BMP-Maritime-Security-2025-.pdf