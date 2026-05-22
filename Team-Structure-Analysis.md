# Aegis Swarm Team Structure & Talent Plan

## 1. Startup team overview

Aegis Swarm is a low-cost underwater scouting system for commercial ships. Instead of relying on one expensive autonomous underwater vehicle, the product uses a swarm of 10 to 20 cheap, relay-linked drones that form a real-time underwater perimeter around a vessel. The drones scout for submerged hazards, debris, and possible UXO within roughly a 2 km radius, then relay sensor data to a bridge-mounted command unit where heavier detection and decision-making happen.

The customer is the commercial shipping operator, cruise line, or marine insurer that wants fewer delays, fewer grounding or collision events, and lower route risk in chokepoints, port approaches, and poorly charted waters. The product is built around a simple bet: ship operators will use underwater drones more often if the system is cheap enough to risk, easy enough for a crew to operate, and useful enough to reduce insurance or delay costs.

The current founding team is Samyak Kakatur, Daniel Luzzatto, Sam Seban, and Michael Xiong. The team is heavily technical, with backgrounds in robotics, autonomous systems, IoT systems, computer science, mechanical engineering, embedded systems, simulation, sensor calibration, SLAM, cloud software, and applied machine learning. That mix fits Aegis Swarm because the company is not only a drone company. It needs underwater sensing, swarm autonomy, bridge software, fleet monitoring, hardware integration, customer-facing deployment, and a credible business case for conservative maritime buyers.

Michael Xiong brings robotics software, simulation, embedded firmware, heterogeneous compute, and fleet-health experience. Daniel Luzzatto brings acoustic calibration, signal processing, control systems, mechanical engineering, and research credibility. Sam Seban brings autonomous navigation, SLAM, ROS, embedded telemetry, product execution, and team leadership. Samyak Kakatur brings production cloud software, customer-facing web applications, authentication, IoT systems, communication, and the strongest stated interest in business and marketing. Together, the team can build a prototype, test it in simulation, create the detection pipeline, ship the bridge dashboard, and start early customer discovery.

## 2. Founder and team roles

### Samyak Kakatur: Chief Executive Officer

Samyak should own the business side of Aegis Swarm while staying close to the product experience customers see. His background in production software at Sidecar Health maps well to the bridge command unit: a deployed web application with authentication, live data, reliability expectations, and real users. His stated interests in marketing, business, and macroeconomics also make him the best fit to take responsibility for fundraising, customer discovery, pricing, and partnerships.

His responsibilities should include fundraising, customer acquisition, insurer partnerships, pricing strategy, and external communication with investors, shipping operators, and regulators. He should also own the first version of the bridge dashboard with the engineering team, since that is the interface captains and operations managers will judge first. This role supports execution by making sure the company does not become only a technical project. Aegis Swarm needs buyers, pilots, and proof that the system saves money.

### Michael Xiong: Chief Technology Officer

Michael should own the technical architecture. His Farm-ng work on MuJoCo simulation, gRPC hardware abstraction, simulated sensors, logging, and visualization is close to the simulation stack Aegis Swarm needs before expensive water testing. His UCLA NESL work on benchmarking across GPU servers, Jetsons, Raspberry Pis, and macOS also fits the product architecture: low-cost drone-side sensing with more compute on the ship.

His responsibilities should include the overall robotics architecture, simulation infrastructure, swarm system design, drone health monitoring, sensor-compute tradeoffs, and future engineering hiring. He should make the build-vs-buy calls for sensors, communication modules, onboard compute, and fleet management. This role supports execution by giving the team a technical owner who can connect firmware, simulation, networking, and system reliability into one coherent product.

### Daniel Luzzatto: AI and engineering lead for detection and signal processing

Daniel should own the detection pipeline. Aegis Swarm's technical value depends on turning noisy underwater sensor data into reliable hazard alerts. Daniel's experience with acoustic calibration at FUSMobile, pressure and flow control at the Technion Flow Control Lab, MEMS validation at STMicroelectronics, deep learning on sEMG signals, and ML evaluation research gives him the best background for this part of the company.

His responsibilities should include sonar and sensor signal processing, model architecture, data labeling, calibration procedures, validation studies, and technical publications or white papers. He should also work with Michael on deciding what happens on the drone and what happens on the bridge command unit. This role supports execution by focusing the team on detection accuracy, false positives, and scientific credibility, which will matter when talking to insurers and fleet operators.

### Sam Seban: Chief Operating Officer and product lead

Sam should own operations and product execution. He has worked across autonomous driving, SLAM, ROS, embedded telemetry, real-time visualization, and shipped software with a measurable business result. His Formula Student and Technion Rocketry work also show that he can coordinate hardware-software projects under deadlines, which is exactly what early pilot deployments will require.

His responsibilities should include pilot planning, product requirements, deployment logistics, vendor coordination, documentation, crew-training workflows, and the swarm coordination layer, especially localization and navigation without GPS. He should translate customer problems into engineering requirements and keep the team honest about what needs to work in the field. This role supports execution by giving the startup one person accountable for moving from prototype to usable product, not just separate technical demos.

## 3. Skill gaps and weaknesses

### Maritime regulatory and compliance knowledge

The team does not yet have deep knowledge of maritime regulation, shipboard safety standards, port authority requirements, or certification paths for underwater equipment. This matters because commercial ships operate in a highly regulated environment, and even a technically strong product may be blocked if it cannot be approved for use around ports, canals, or international waters. If this gap is not addressed, pilots could stall, customers may hesitate, and the team may build hardware that later needs expensive redesign.

### Enterprise sales and maritime industry relationships

The team has limited direct experience selling to large shipping companies, insurers, cruise lines, or port operators. This matters because the buyer is not an individual consumer; it is a conservative enterprise customer with long procurement cycles and high risk sensitivity. If this gap remains, the team may build a useful product but fail to get meetings, structure pilots, or prove ROI in language that buyers trust.

### Manufacturing and marine hardware production

The founding team has robotics, embedded, and mechanical experience, but not enough manufacturing depth for rugged underwater drone bodies, launch-and-recovery racks, waterproofing, corrosion resistance, and repeatable production. This matters because Aegis Swarm depends on hardware being cheap, reliable, and replaceable. If the team underestimates manufacturing, unit costs could rise, drones could fail too often, and the leasing model could become financially painful.

### Legal, insurance, and liability expertise

Aegis Swarm will likely touch insurance discounts, liability after missed detections, contracts with fleet operators, and possibly IP around sensor integration and swarm operations. The team does not currently have a legal or insurance specialist. This matters because the business model depends partly on convincing insurers that the system reduces risk. If this gap is ignored, the company could take on unclear liability or fail to turn safety improvements into premium reductions.

### UX design for high-stress bridge workflows

Samyak can build customer-facing software, but the team does not yet have a dedicated UX designer for maritime bridge workflows. This matters because captains and crew need alerts that are clear under pressure, not just technically accurate. If the interface creates confusion, alarm fatigue, or slow response, the product may be rejected even if the detection system works.

### Finance and hardware leasing discipline

The leasing model means Aegis Swarm carries the upfront hardware cost and earns it back over time. The team does not yet have strong finance or unit-economics experience for hardware leasing. This matters because slow adoption, high replacement rates, or weak maintenance planning could drain cash. If this gap is not addressed, the company may grow revenue while still losing money on every deployed swarm.

## 4. Future hiring plan

### Year 1: maritime advisor or fractional compliance lead

The first outside talent should be a maritime advisor, compliance consultant, or fractional regulatory lead. This person becomes important before formal pilots, because the team needs to understand where the system can legally operate, what approvals are needed, and how to talk to port authorities and ship operators. This role supports growth by reducing the risk of building something that cannot be deployed.

### Year 1: hardware and manufacturing engineer

As soon as the prototype moves beyond lab testing, the company will need a hardware or manufacturing engineer with marine systems experience. This role becomes important when the drone enclosure, launch rack, waterproofing, repair process, and cost targets need to become repeatable. This hire supports growth by turning one-off prototypes into a small fleet that can survive real use.

### Year 1 to year 2: full-stack or systems software engineer

Once the bridge command unit and fleet-monitoring software become more than a class prototype, the team will need another software engineer. This person would help build telemetry ingestion, dashboards, alerting, deployment tooling, and reliability features. The role supports growth by letting Samyak focus more on CEO work while keeping the customer-facing software moving.

### Year 2: business development lead for shipping and insurance

After a working pilot exists, Aegis Swarm should hire a business development lead with maritime or insurance relationships. This role becomes important when the company needs fleet pilots, insurer conversations, and enterprise contracts. It supports growth by converting technical validation into paid deployments.

### Year 2: field operations and customer support lead

Once systems are installed on vessels, the company will need someone responsible for deployment, training, maintenance coordination, and customer feedback. This role becomes important after the first few pilots, when founders cannot personally support every install. It supports growth by making the product feel reliable to crews and operations managers.

### Year 2 to year 3: ML data engineer or applied scientist

If deployments generate useful underwater sensor data, the team will need someone focused on data pipelines, labeling workflows, model retraining, and performance monitoring. This role becomes important after enough field data exists to improve the detection system. It supports growth by turning deployment data into a technical advantage competitors cannot copy quickly.

### Year 3: product designer for bridge and operations software

A dedicated product designer should be added once the bridge dashboard becomes a daily-use tool rather than a pilot interface. This role supports growth by improving alert design, crew workflows, onboarding, and trust in the system. For maritime customers, a confusing interface can kill adoption almost as fast as a failed sensor.

## 5. Founder and team challenges

The most likely team challenge is balancing technical ambition with business proof. Three of the four founders have very deep robotics, engineering, or research backgrounds, so the team may naturally spend too much time improving the system and not enough time testing whether customers will pay. Samyak's CEO role should reduce this risk, but the team will still need regular customer interviews, pilot milestones, and hard decisions about what is good enough to test.

Unequal workload is another risk. A hardware-and-software startup has long stretches where technical work can dominate, especially during prototype development. Michael, Daniel, and Sam may carry heavy technical loads early, while Samyak may split time between software, fundraising, and customer outreach. The team should manage this by writing clear weekly goals, making ownership visible, and treating business development work as real work rather than a side task.

Founder disagreement could also happen around product scope. For example, the team may disagree about whether to prioritize detection accuracy, swarm navigation, low-cost hardware, or the bridge dashboard. These disagreements are normal, but they can slow execution if nobody owns the final decision. The current role split helps: Michael decides technical architecture, Daniel decides detection tradeoffs, Sam decides product and operations priorities, and Samyak decides business and customer priorities.

Burnout is a real risk because this startup combines hard robotics, expensive testing, conservative customers, and a leasing model that may take time to prove. The team can reduce this by setting narrow pilot goals, avoiding unnecessary features, and separating class-project ambition from what an early startup could actually build. The first goal should not be a perfect commercial fleet. It should be a credible pilot that proves ships can get useful lateral underwater visibility from a low-cost swarm.

Hiring may also be difficult. The company will need people who understand marine hardware, robotics, insurance, sales, and field operations, but early-stage startups cannot hire all of those roles at once. The team should use advisors and fractional experts before making full-time hires. That keeps burn lower while still filling the highest-risk knowledge gaps.

## 6. Reflection

This exercise made it clear that Aegis Swarm is less about having four smart technical founders and more about assigning real ownership. Before mapping the roles, it would be easy to say that everyone can help with everything. That is not enough. The company needs one person responsible for the business, one for the technical architecture, one for detection accuracy, and one for product and operations. The surprising part was that the strongest team structure was not simply putting every technical person into a technical title. Sam's leadership and product experience are more useful as COO/Product Lead than as another engineering role.

The exercise also changed how we think about startup teams. The missing roles are just as important as the current strengths. Our team can probably build a convincing prototype, but a real company would still need maritime compliance, enterprise sales, manufacturing, UX, legal, and finance discipline. The biggest concern is not whether the team has enough raw engineering ability. It is whether we can turn a technically interesting system into something conservative shipping customers trust, pay for, and use correctly in the field.
