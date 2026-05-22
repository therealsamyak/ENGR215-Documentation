# Aegis Swarm Team Structure & Talent Plan

## 1. Startup team overview

Aegis Swarm is a low-cost underwater scouting system for commercial ships. Instead of one expensive autonomous underwater vehicle, the product uses 10 to 20 cheap, relay-linked drones that form a real-time perimeter around a vessel. The drones scout roughly a 2 km radius for submerged hazards, debris, or UXO, then send sensor data back to a bridge-mounted command unit.

The team is Samyak Kakatur, Daniel Luzzatto, Sam Seban, and Michael Xiong. This is a technical founding team, but the mix fits the startup. Aegis Swarm needs robotics, simulation, acoustic sensing, SLAM, embedded systems, cloud software, and someone willing to own the business side. Michael brings robotics software, simulation, embedded firmware, and fleet-health thinking. Daniel brings acoustic calibration, signal processing, control systems, and research depth. Sam brings SLAM, ROS, telemetry, product execution, and team leadership. Samyak brings production cloud software, customer-facing web apps, authentication, IoT systems, and the clearest business/marketing interest on the team.

## 2. Founder and team roles

Samyak Kakatur should be CEO. His job is to own fundraising, customer discovery, pricing, insurer partnerships, and external communication with shipping operators, cruise lines, regulators, and investors. He also fits the bridge-dashboard side of the product because his Sidecar Health work involved production NextJS, AWS deployment, authentication, documentation, and customer-facing internal tools. Aegis Swarm cannot just be a clever robotics project. Someone has to prove that fleet operators will pay for it.

Michael Xiong should be CTO. He is the strongest full-stack robotics builder on the team. His Farm-ng work on MuJoCo simulation, gRPC hardware abstraction, simulated IMU/GPS/CAN data, logging, and visualization is close to the simulation infrastructure Aegis Swarm needs before expensive water trials. He should own the technical architecture, drone/bridge system design, simulation stack, swarm health monitoring, sensor-compute tradeoffs, and future engineering hiring.

Daniel Luzzatto should be AI/Engineering Lead for detection and signal processing. The product only matters if it can turn noisy underwater signals into reliable hazard alerts. Daniel's background fits that problem: acoustic calibration at FUSMobile, pressure and flow control research, MEMS validation, signal-processing ML, and peer-reviewed research. He should own sonar processing, model design, calibration, data-labeling standards, validation studies, and the technical evidence needed for insurers and shipping customers to trust the system.

Sam Seban should be COO/Product Lead. He has the most natural mix of autonomy, hardware/software integration, and execution leadership. Formula Student gave him autonomous navigation and SLAM experience. Technion Rocketry gave him embedded telemetry and experience leading engineers. Marions-Nous gave him a shipped product with a measurable sales result. He should own pilot planning, deployment logistics, product requirements, vendor coordination, crew-training workflows, and swarm coordination in GPS-denied water.

## 3. Skill gaps and weaknesses

The first gap is maritime regulation. The team does not yet know enough about port rules, shipboard safety standards, certification, or where underwater drones can legally operate. That matters because a working prototype is useless if customers cannot deploy it around ports, canals, or international routes.

The second gap is enterprise sales and maritime relationships. Shipping companies and insurers are conservative buyers with long procurement cycles. If we cannot get credible pilots or speak their language, the product could be technically useful and still hard to sell.

The third gap is manufacturing. The founders have robotics and mechanical backgrounds, but cheap underwater hardware is its own problem: waterproofing, corrosion, launch/recovery racks, replacement logistics, and repeatable production. If unit costs rise or drones fail too often, the leasing model breaks.

The fourth gap is legal, insurance, and liability. Aegis Swarm depends partly on insurer partnerships and risk reduction. The team needs help with contracts, liability after missed detections, IP, and the actual path from "safer vessel" to lower premiums.

The fifth gap is UX. The bridge interface has to work under stress. A technically accurate alert is not enough if a captain cannot understand it quickly or if the system creates alarm fatigue.

## 4. Future hiring plan

In year 1, Aegis Swarm should use a maritime advisor or fractional compliance lead before formal pilots. This person would help the team understand deployment rules, port authority concerns, and basic certification risk. Also in year 1, the company needs a hardware/manufacturing engineer with marine experience to move from prototype parts to rugged drone bodies, waterproofing, recovery racks, and realistic unit costs.

In year 1 to year 2, the team should add a full-stack or systems software engineer. The bridge command unit, telemetry pipeline, alerting, dashboard, and deployment tooling will become too much for Samyak to own while also acting as CEO. In year 2, the next important hire is a business development lead with shipping or insurance relationships. That role turns technical validation into pilots, insurer conversations, and eventually enterprise contracts.

After the first pilots, Aegis Swarm should add a field operations/customer support lead. Someone has to handle installation, crew training, maintenance coordination, and feedback from real vessels. By year 2 or 3, the company should also hire an ML data engineer or applied scientist to manage field data, labeling, retraining, and model monitoring. If enough deployments happen, the data becomes one of the few defensible parts of the business.

## 5. Founder and team challenges

The biggest team risk is overbuilding. Three founders are deeply technical, so the natural instinct will be to improve the system instead of proving that buyers care. Samyak's CEO role helps, but the team needs regular customer interviews and pilot milestones so business proof does not get pushed behind engineering polish.

Unequal workload is another risk. Early hardware/software work will fall heavily on Michael, Daniel, and Sam, while Samyak splits time between software, customers, and fundraising. The team should make weekly ownership explicit so business development is treated as real work, not a side activity.

Founder disagreement will probably come from scope. Detection accuracy, swarm navigation, cheap hardware, and the bridge dashboard can all feel like the top priority. The role split should reduce this: Michael owns architecture, Daniel owns detection, Sam owns product/operations, and Samyak owns business priorities. Burnout is also likely because ocean testing is expensive, customers are conservative, and progress may be slow. The team should keep the first pilot narrow: prove useful lateral underwater visibility from a low-cost swarm, not a perfect commercial fleet.

## 6. Reflection

This exercise made the team structure feel less theoretical. It is easy to say "everyone helps with everything," but that is not how a startup survives. Aegis Swarm needs clear owners: business, technical architecture, detection, and operations/product. The surprising part is that the best structure is not just giving every technical person a technical title. Sam's leadership and product instincts are more useful as COO/Product Lead than as another pure engineer.

The exercise also showed that our missing roles matter as much as our current strengths. The team can probably build a convincing prototype, but a real company still needs maritime compliance, enterprise sales, manufacturing, UX, legal, and finance discipline. The main concern is not raw engineering ability. It is whether we can turn a strong technical idea into something conservative shipping customers trust, pay for, and actually use.
