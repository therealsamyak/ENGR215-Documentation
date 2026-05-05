### **Aegis Swarm**

### **1\. Problem Statement**

Commercial maritime transport is responsible for 80% of global trade and it faces a critical "last-mile" visibility gap. High-value vessels (VLCC oil tankers, LNG carriers, and massive container ships) navigate through congested chokepoints and hazardous coastal waters where submerged obstacles, shifting debris, or unexploded ordnance (UXO) pose catastrophic risks.

The problem is three-fold:

* Ships rely on hull-mounted sonar that only looks forward/down; they have zero lateral visibility for submerged hazards 1-2 km away.  
* A single collision or grounding (like the *Ever Given* in the Suez Canal) costs the global economy billions and the ship owner millions in insurance/repairs.  
* Critical chokepoints (Straits of Malacca, Panama Canal) and poorly charted port approaches during low-visibility weather.

### **2\. Target Customer**

The target customer is Safety & Operations Managers at Tier-1 Global Shipping Conglomerates (e.g., Maersk, MSC, or Euronav) who manage fleets of Ultra-Large Crude Carriers (ULCC).

Specifically, we are targeting the "Marine Insurance Risk Officers" within these firms who are incentivized to lower premiums by proving the implementation of active hazard-mitigation technology.

This can also include insurance companies who manage luxury yachts and/or cruise ships.

### **3\. Current Process / Pain Points**

Currently, hazardous area scouting is handled in two ways:

1. Ships rely on outdated bathymetric charts and "vessel traffic services" (VTS) provided by local governments.  
2. In high-risk areas, ships wait for state-funded mine-sweepers or specialized salvage vessels to clear paths.

Pain Points:

* Specialized underwater survey vessels cost $20,000–$50,000 per day.  
* Ships often wait days for "cleared" windows, leading to massive fuel, labor waste and significant delays.  
* Current undersea drones (AUVs) are "exquisite" tech, as they cost over $250k per unit. Losing one to a collision is a major financial loss, making operators hesitant to use them in tight, dangerous spaces.

### **4\. Initial Idea**

**Aegis Swarm** is a "disposable-first" swarm of low-cost, sensor-equipped underwater scouting drones. Instead of one expensive, autonomous robot, we deploy a distributed network of 10–20 tethered or relay-linked drones that act as the "extended nervous system" of the ship.

The drones form a perimeter around the vessel, scouting a 2 km radius. Because they autonomously follow predefined, hardcoded search tasks, they do not require expensive hardware to run complex AI locally. Instead, the drones relay acoustic imaging back to a single "Central Command" unit installed on the ship's bridge, which handles the heavy decision-making. If an anomaly is detected, ship personnel can seamlessly take manual, remote control over individual drones to investigate the threat.

Because the drones are cheap, and the compute is done on the ship directly, they are disposable. If a drone is lost to a hazard or debris, the swarm recalibrates. The cost of an entire swarm is less than 10% of a single traditional military-grade AUV.

The drones are stored in a compact "launch-and-recover" rack on the deck, requiring no specialized ROV pilots. Multiple ‘swarms’ can be stored on the same ship. The swarm size and amount loaded can be adjusted based on consumer demands, and unharmed drones are recovered for reuse. 

### **5\. Why Existing Solutions Fall Short**

* Existing AUVs (like the *Knifefish* or *Hugin*) are designed for deep-sea scientific research or high-end warfare. They have expensive on-board AI and titanium housings that commercial shipping doesn't need.  
* Current drones collect data and are then retrieved to "download" info. Aegis Swarm provides real-time alerts directly to the ship's Captain, allowing for immediate course correction.  
* If a traditional $250k drone breaks, the mission ends. If an Aegis drone breaks, the other 19 keep scouting.