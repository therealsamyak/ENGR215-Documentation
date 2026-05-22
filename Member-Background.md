Aegis Swarm — Team Structure & Role Assignments

Team: Samyak Kakatur, Daniel Luzzatto, Sam Seban, Michael Xiong

This document covers Sections 1 and 2 of the team assignment: a high-level overview of the founding team's relevant experience and strengths, followed by recommended founder roles and responsibilities. Each of the four members is assigned exactly one role; the remaining roles from the assignment list are reserved for future hires (covered in the hiring-plan section of the broader submission).

================================================================
1. TEAM MEMBER PROFILES
================================================================


----------------------------------------------------------------
MICHAEL XIONG
----------------------------------------------------------------

Background: M.Eng Robotics & Autonomous Systems, UCLA (in progress); B.S. Computer Science, UC Santa Cruz (2024). Multi-time Dean's Honors recipient.

Most relevant experience:

• Robotics SWE Intern, Farm-ng (7 months): Built a physics-based MuJoCo simulation environment with a gRPC HAL interface for the Amiga rover, enabling virtual testing without hardware dependencies. Simulated IMU, GPS, and CAN bus data streams; implemented elevation-map generation; built real-time logging and visualization tooling for autonomy algorithm tuning. → This is essentially the simulation infrastructure Aegis Swarm will need; ocean trials are expensive, and cheap iteration depends on a high-fidelity sim.

• Graduate Researcher, UCLA NESL: Currently leading HoliBench, a cross-platform ML benchmarking framework spanning NVIDIA GPU servers, Jetson, Raspberry Pi, and macOS. → Directly mirrors Aegis Swarm's heterogeneous-compute architecture (cheap drone-side sensors + central bridge inference).

• Incoming SWE Intern, GM Cruise (Lidars & AV Health): Sensor-health monitoring for autonomous vehicles — directly analogous to fleet-health monitoring across 10–20 active drones.

• Embedded SWE Intern, SproutLabs: C++ firmware for a consumer IoT device with BLE/NFC, interrupt-driven multithreaded architecture, and OTA updates.

• Teaching: Group tutor for Principles of Computer Systems Design and Applied Deep Learning at UCSC.

Core strengths: Physics simulation for autonomous systems, embedded firmware (C++/BLE/OTA), ML benchmarking across heterogeneous hardware, distributed systems and computer networking, sensor data fusion.


----------------------------------------------------------------
DANIEL LUZZATTO
----------------------------------------------------------------

Background: M.Eng Robotics & Autonomous Systems, UCLA (in progress); B.Sc. Mechanical Engineering, Technion (2025).

Most relevant experience:

• Mechanical Engineering Intern, FUSMobile (7 months): Automated acoustic calibration in C++/Python, reducing calibration time from 30 to 5 minutes. → Acoustic calibration translates directly to sonar processing, which is the core sensing modality for Aegis Swarm.

• Research Assistant, Flow Control Lab, Technion (10 months): Designed a motor-pump system to emulate oscillatory flow for desalination research. Implemented PID control to regulate pressure at 10 bar under wind oscillations. Integrated pressure, flow, torque, and RPM sensors with LabVIEW. Co-authored a peer-reviewed publication. → Underwater fluid dynamics, sensor fusion under noisy conditions, and credible research output are all directly relevant.

• Applied ML & Signal Processing: Built a deep-learning system to decode QWERTY keystrokes from sEMG signals, achieving a 44% reduction in error rate through architecture design and physically grounded data augmentation. → "Physically grounded augmentation" is the right mental model for underwater acoustics, where signal physics matters more than pure data volume.

• Engineer Intern, STMicroelectronics: MEMS sensor testing/validation under inertial, pressure, and environmental conditions.

• UCLA Research, LLM Agents: Scalable evaluation pipelines and generalization studies (Mind2Web → WebArena).

• Value Verdict: Full-stack analytics platform serving real-time insights from 220k+ events, combining Shin-method probabilistic modeling and Monte Carlo simulation.

Core strengths: Deep learning on temporal/signal data, acoustic and pressure sensor calibration, control systems (PID, LabVIEW), probabilistic modeling, peer-reviewed research output, mechanical engineering fundamentals.


----------------------------------------------------------------
SAM SEBAN
----------------------------------------------------------------

Background: M.Eng Robotics & Autonomous Systems, UCLA (in progress); B.Sc. Mechanical Engineering, Technion (2025). Dean's Award for Excellence (top 15%), multiple semesters. Native French and English; fluent Hebrew and Spanish.

Most relevant experience:

• Software Engineer, Marions-Nous / Lesitedumariage.com (6 months): Designed and deployed a full application for the Paris Wedding Expo (40,000+ attendees). Developed an AI-powered predictive engagement algorithm leveraging behavioral analytics that produced a 14% increase in sales. → Rare on this team: shipped a product with a measurable business outcome attached.

• Autonomous Systems Engineer, Formula Student Technion (2.5 years): Programmed an autonomous driving algorithm using FastSLAM for the Technion racecar; competed at Formula Student competitions across Europe. → SLAM is directly relevant to coordinating a drone swarm underwater where GPS is unavailable.

• Software Team Leader, Technion Rocketry Club (1+ year): Led a team of 5 to develop and integrate telemetry sensors into the rocket's embedded system and build a real-time data visualization stack. → Demonstrated team leadership on a complex hardware/software project.

• Avionics System Engineer, Technion Rocketry Club: Embedded software for telemetry (altitude, speed, acceleration, etc.).

• Research Intern, Cognitive Robotics Lab, Technion: Built a ROS framework enabling service robots to interpret natural-language commands using PDDL and NLP.

Core strengths: Autonomous navigation and SLAM, ROS, embedded telemetry, real-time data systems, demonstrated team leadership (5 engineers), product instinct backed by measurable business outcomes, multilingual (French, English, Hebrew, Spanish — useful for European and Mediterranean shipping customers).


----------------------------------------------------------------
SAMYAK KAKATUR
----------------------------------------------------------------

Background: M.Eng IoT Systems, UCLA (in progress); B.S. Computer Science, UC Riverside (2025).

Most relevant experience:

• Software Engineer Intern, Sidecar Health (two stints, ~10 months total): Built a containerized audit-automation NextJS application that compressed audit timelines. Deployed production applications on AWS (ECS, RDS, SDM, Amplify). Overhauled the authentication framework using WorkOS AuthKit. Earlier stint: TypeScript migration (10% computation improvement), brought test coverage to 80%, modernized component styles, overhauled internal documentation. → This is exactly the production cloud + customer-facing web stack the bridge command unit dashboard will need.

• Self-stated interests: Coding, Marketing, Business, and macroeconomics. → The only team member with explicit interest in the business side.

• Student Tutor, Kumon (10 months): Tailored instruction to individual student needs, collaborated with peers, incorporated feedback to revise methodologies. → Communication training useful for varied stakeholders (shipping execs, insurance underwriters, regulators).

• M.Eng concentration: IoT Systems — aligns with the connected-fleet architecture of Aegis Swarm.

Core strengths: Production cloud deployment (AWS full stack), customer-facing web applications (NextJS, TypeScript, Tailwind), authentication and security, IoT systems education, stated business/marketing motivation, strong communication.


================================================================
2. RECOMMENDED ROLE ASSIGNMENTS
================================================================


----------------------------------------------------------------
MICHAEL XIONG → Chief Technology Officer (CTO)
----------------------------------------------------------------

Why he fits: Michael is the strongest cross-stack robotics builder on the team. His Farm-ng MuJoCo work is a direct template for the simulation infrastructure Aegis Swarm needs (cheap iteration before expensive ocean trials). His current HoliBench research targets exactly the heterogeneous-compute architecture the product uses: cheap drone-side sensors plus a central bridge doing inference. His incoming GM Cruise work on AV fleet health is the closest analog to monitoring a 10–20 drone swarm in production. Add embedded firmware (BLE/OTA from SproutLabs) and the technical stack is end-to-end covered.

Responsibilities:
  • Own the overall technical architecture: drone hardware, swarm coordination protocol, bridge command unit, data pipeline.
  • Build and own the simulation infrastructure that enables cheap iteration on drone behavior and detection algorithms before ocean trials.
  • Make build-vs-buy decisions on sensor modules, comms hardware, and onboard compute.
  • Define the swarm health monitoring and fleet management system (drones lost, recharge cycles, recalibration after losses).
  • Recruit and lead future engineering hires (firmware, robotics, ML infra).
  • Lead technical due diligence sessions with investors and pilot customers.


----------------------------------------------------------------
DANIEL LUZZATTO → AI / Engineering Lead (Detection & Signal Processing)
----------------------------------------------------------------

Why he fits: The defensible moat of Aegis Swarm is detection accuracy — turning noisy underwater sensor signals into reliable hazard alerts. Daniel uniquely sits at the intersection of acoustic calibration (FUSMobile), physically grounded signal-processing ML (sEMG paper, 44% error reduction), control systems with pressure/flow sensors (Flow Control Lab), MEMS validation (STMicro), and modern ML research (UCLA). He is also the only team member with a peer-reviewed publication, which directly addresses the business plan's explicit need for "scientific-backed studies" to validate the system to insurers and shipping operators.

Responsibilities:
  • Own the detection software stack: sonar/sensor signal processing pipeline, ML model architecture, training infrastructure.
  • Lead the scientific validation studies the business plan calls out as a prerequisite for industry credibility.
  • Drive sensor selection and calibration procedures across the drone fleet.
  • Define data labeling, quality, and curation protocols as deployment data accumulates (the data flywheel is the long-term moat).
  • Author technical white papers and conference submissions to support insurance, regulatory, and partnership conversations.
  • Collaborate with the CTO on the boundary between drone-side preprocessing and bridge-side inference.


----------------------------------------------------------------
SAM SEBAN → Chief Operating Officer (COO) / Product Lead
----------------------------------------------------------------

Why he fits: Sam is the team's hybrid — deep technical (SLAM, ROS, embedded telemetry), demonstrated leadership (managed a 5-engineer rocketry software team), and the only member who has shipped something with an attached business-outcome number (the 14% sales lift at Marions-Nous). A COO at an early-stage hardware startup coordinates execution across engineering, supply chain, pilot deployments, and customer operations — Sam's track record at Formula Student (competition deadlines, cross-functional integration) and the Rocketry Club (hardware/software integration under deadlines) fits this exactly. His SLAM background also means he can credibly own the swarm coordination engineering effort, which sits naturally at the COO/Product boundary. Multilingual ability (French, Italian-adjacent Hebrew, Spanish) is a real asset given the European and Mediterranean concentration of Aegis Swarm's target customers (Maersk, MSC, Euronav, Mediterranean chokepoints).

Responsibilities:
  • Own day-to-day execution and operations: project timelines, pilot deployment logistics, supply chain coordination, vendor management.
  • Lead product definition — translate customer needs (fleet operators, insurers) into engineering requirements.
  • Own swarm coordination engineering (SLAM, formation control, localization without GPS) — his deepest technical expertise.
  • Manage pilot programs with initial fleet customers, including on-site deployment, crew training, and feedback loops.
  • Build the operational processes and documentation that need to be in place before scaling hiring.


----------------------------------------------------------------
SAMYAK KAKATUR → Chief Executive Officer (CEO)
----------------------------------------------------------------

Why he fits: The fit is two-fold. First, Samyak has explicitly stated business and marketing motivation — critical because none of the other three founders have demonstrated business experience or stated interest in the commercial side. A CEO who genuinely wants the role outperforms a CEO assigned by default. Second, the bridge command unit (the dashboard ship captains will actually use) is a production cloud-deployed customer-facing web application, which is precisely Samyak's deepest technical skillset (NextJS, AWS ECS/RDS/Amplify, authentication, production bug triage). A CEO at a hardware/SaaS hybrid startup who can credibly own both the customer relationship AND ship the customer-facing software is a strong asymmetric advantage. His Kumon tutoring background also reflects communication skills tailored to individuals — useful when pitching shipping execs, insurance underwriters, and maritime regulators, each of whom respond to different framings.

Responsibilities:
  • Own the business: fundraising, customer acquisition, pricing strategy, partnerships.
  • Lead outreach to target fleet operators (Maersk, MSC, Euronav) and cruise lines.
  • Establish the insurer partnership track — the business plan identifies this as the central adoption lever (premium reductions for Aegis-equipped vessels create the financial incentive that regulation does not).
  • Own the bridge command unit's customer-facing software (dashboard, auth, production deployment) — this keeps the CEO close to the actual product experience customers see.
  • Build the early sales pipeline; later hire and manage Marketing, BD, and Customer Success leads as the company scales.
  • Represent the company externally: investors, press, industry conferences.


================================================================
NOTES ON NON-OBVIOUS ROLE-ASSIGNMENT CALLS
================================================================

A few decisions worth flagging explicitly, since reasonable people might pick differently:

• Why not Michael as CEO? He has the strongest technical breadth, and the product's primary risk over the next 12 months is technical: can the swarm actually work cheaply and reliably enough? CEO can be revisited once technical feasibility is proven and commercial scale becomes the bottleneck.

• Why Sam at COO rather than another pure-engineering seat? With Michael as CTO and Daniel as AI Lead, putting Sam in another engineering-only role would leave operations and product unowned by a founder. His Marions-Nous outcome (concrete sales lift) is rare and underused if buried in an internal-only role.

• Why Samyak as CEO over Sam? Samyak's stated business interest plus his customer-facing software stack fits CEO at this stage better than Sam's strength, which is shipping things that work — that profile is more COO-shaped.

• Roles left unfilled (future hires): Marketing Lead, Customer Success Lead, Business Development Lead, and a dedicated Hardware Engineering Lead (mechanical/manufacturing for the drone bodies and recovery cradles) are intentionally open. These become the priority hires once a pilot fleet validates the model.


