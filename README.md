> **Bilingual Disclosure Notice:** This is a bilingual disclosure - same content in KR/EN, v4.1 2026-09-06 (Korean version: [README.ko.md](README.ko.md))  
> **Original Authority Notice:** This English version was drafted and translated with the assistance of AI tools (Meta AI, Google Gemini), so phrasing and expressions may not be perfectly smooth or fully precise. The authoritative original for all legal, technical, and engineering interpretations belongs exclusively to the Korean document (`README.ko.md`). (PHILOSOPHY.ko.md is authoritative original)

# LAST-LIGHT — Technical Specification for Auxiliary Wayfinding System via Standard Illuminated Signs, Fire Cabinets, Smart Raceways, Space/Orbital Pressurized Modules, Multi-Sensory Acoustic/Haptic Infrastructure, and Distributed Blackbox Telemetry (Ver. 4.1 Final Revision)

* **Official Classification:** Defensive Publication / Prior Art Technical Specification  
* **Initial Conception Date:** July 30, 2026 / **Final Revision Date (v4.1):** September 6, 2026  
* **Primary IP Holder:** soma-moa (`soma-moa` / Sole Inventor: `deundeuni`)  
* **Primary Repository:** `github.com/soma-moa` | **Official Domain:** `somamoa.ai.kr`  
* **Applicable Licenses:** CC BY 4.0 & DPL v1.0 (Defensive Patent License)  
* **Keywords:** LAST-LIGHT, Wayfinding, Offset Calibration, ISO 7010, Co-Survival Haptic Receiver, Haptic Compass, BLE Auracast, Tri-State Isolation, T-Reg Suppressor, Distributed Local Blackbox, Space Station Evacuation, Microgravity Evacuation, Orbital Module Anchors, IVA/EVA Suit Haptics, Prior Art, ARCHITECTURE_STRATEGY, chiplet-apu, CWP, MAX-LIFE ICE-BELT

---

## 0. Inventor's Declaration and Motivation

### 0.1 Field-Driven Motivation
This architecture originates from a fundamental human purpose: **"To ensure that every person can evacuate safely during a disaster, and to guarantee that firefighters, first responders, and crew members who risk their lives to enter hazardous environments return safely to their families."**

In emergency disaster environments, ambient fire noise and statutory emergency sirens exceeding 100dB render auditory voice prompts completely ineffective, causing temporary auditory paralysis in evacuees. Furthermore, during fire or depressurization disasters in microgravity or zero-gravity orbital modules (such as space stations) and pressurized habitats, the absence of thermal buoyancy prevents smoke from rising, causing dense smoke to disperse uniformly in 3D space and resulting in total visual blockout (Zero-Visibility). Addressing these field challenges, this architecture introduces a tactile compass mechanism that provides direct, intuitive spatial direction via bone-conduction and haptic interfaces, eliminating language, nationality, and sensory barriers for civilians, elderly individuals, tourists, hearing-impaired persons, and spacesuit-clad astronauts.

By establishing permanently illuminated exit signs (ISO 7010), fire hose cabinets, alarm terminal boxes, underground electrical raceways, orbital module structural frames, and wireless RF beacons as **Visual/Optical/Acoustic/RF Absolute Anchors (ANCHOR)**, this system delivers visible green guidance pathways, 3D spatial audio, and localized tactile vibration cues for civilians and crew members, alongside high-contrast infrared (IR) pathways and specialized haptic guidance for first responders equipped with Night Vision Goggles (NVG). Furthermore, by embedding non-volatile heat-resistant flash memory logging modules within fire cabinet chambers and orbital module enclosures, the architecture establishes a distributed local blackbox infrastructure for post-disaster forensics and AI-driven evacuation model self-evolution.

### 0.2 Master Concept & Sensor Fusion Standard
The visual/optical/acoustic/RF ANCHOR-based zero-point calibration and offset correction mechanism disclosed in this specification serves as the **Master Reference Framework** for the overall positioning and wayfinding system.

Any additional integration of secondary positioning or sensing modalities—including gyroscopes, accelerometers, Inertial Measurement Units (IMUs), microphone arrays, acoustic/ultrasonic transducers, bone-conduction transducers, tactile haptic actuators, BLE Auracast RF modules, UWB modules, heat-resistant blackbox memories, LiDAR, Time-of-Flight (ToF) sensors, thermal imaging, and infrared sensors—whether applied individually or in combination, constitutes a subordinate combination that relies on this master zero-point calibration. All such sensor fusion implementations fall entirely within the scope of this prior art.

* **Upper Architecture & Linked Hardware Implementation Reference:** The zero-point anchor calibration, 100ms self-healing mesh network, and Tri-State isolation control defined in this LAST-LIGHT specification constitute a sub-implementation of the universal survival architecture in `ARCHITECTURE_STRATEGY v3.2.4` and the T-Reg suppression and localized isolation logic in `chiplet-apu-multi-system-survival-architecture v2.6`, applied to disaster evacuation environments. Furthermore, raceway and fire cabinet clamping attachments represent infrastructure implementations of the CWP 4-Hardware mechanisms, sharing identical survival control philosophy with `MAX-LIFE ICE-BELT v1.6`.

### 0.3 Zero-Downtime Resilience & Non-Contact Principle
This architecture strictly prohibits physical or electrical modifications to mandatory statutory fire, safety, or space module infrastructure. The system prioritizes organic, zero-downtime fail-over resilience. Each module maintains an independent multi-mesh network topology to mitigate single points of failure (SPOF). Upon the physical destruction of any node, adjacent modules autonomously assume positioning, calculation, spatial guidance rendering, and local telemetry logging tasks without system crash.

### 0.4 Non-Exclusive Interoperability & Open Public Standard
This architecture is not proprietary to any specific optical camera, vision sensor, microphone array, tactile receiver, LiDAR, mobile device, spacesuit HMD/haptic transducer, or robotic vision framework. It operates as an Open Public Standard capable of utilizing all public-domain illuminated signs (e.g., ISO 7010 series), fire service cabinet indicators (internal/external), directional sound anchors, BLE Auracast transmitters, and ceiling raceway optical anchors as reference points.

### 0.5 Operational Priority Control
In event of computational or sensory overload during an emergency, the system prioritizes absolute reference (ANCHOR) identification, position offset correction, and core blackbox telemetry logging over secondary tasks (such as high-definition visual reconstruction or decorative UI rendering), maintaining continuous wayfinding execution.

### 0.6 Universal Application Scope
This architecture comprehensively applies to smartphone-based pedestrian evacuation applications, Co-Survival Haptic Receivers, intra-vehicular/extra-vehicular activity (IVA/EVA) spacesuit haptic guidance pads, distributed blackbox telemetry forensic modules, autonomous mobile robot (AMR) and orbital exploration rover relocation modules, smart emergency lighting/acoustic anchors, internal/external fire cabinet anchors, underground raceway and spacecraft raceway multi-spectrum anchors, disaster relief AR glasses, firefighter/astronaut NVG equipment, and tactile rescue headsets.

### 0.7 Disclosure Purpose and Limitation Notice
This document is published as defensive prior art. The descriptions of features, configurations, and performance herein are illustrative and do not limit or guarantee specific implementations. This system does not replace, alter, or expand statutory fire safety facilities or statutory space safety equipment, functioning purely as a supportive reference mechanism.

### 0.8 Acknowledgement of Independent Prior Research
While this architecture was independently conceived and formulated by the inventor, it does not exclude the possibility that similar concepts regarding visual, acoustic, or RF reference utilization were independently developed by other researchers or entities. The primary objective of this publication is not to claim exclusive monopoly, but to record this intuitive framework as public prior art, preventing private monopolization and allowing public access for safety implementation.

---

## 1. Revision History Summary

* **v1.0 (2026-07-30) ~ v3.9 (2026-09-01):** Formulated initial visual anchoring concept, expanded to full-stack structural design, Co-Survival Haptic Receiver protocols for 100dB+ siren environments, distributed heat-resistant local blackbox logs, self-healing mesh networking, privacy isolation mechanisms, and legal defensibility over 17 iterations.
* **v4.0 (2026-09-06):** Cross-referenced master survival architecture (`ARCHITECTURE_STRATEGY v3.2.4`), APU controller (`chiplet-apu v2.6`), marine armor (`MAX-LIFE ICE-BELT v1.6`), and CWP 4-Hardware mechanisms.
* **v4.1 (2026-09-06):** Integrated space station pressurized modules, microgravity zero-visibility smoke navigation, IVA/EVA spacesuit haptic compass infrastructure, and unified 8-repository mesh ecosystem patch.

---

## 2. Full-Stack Applied Architecture (3-Tier Applied Architecture)

* **[L2] Auxiliary Guidance & Specialized UI Layer:** Civilian/crew green visual guidance, 3D spatial audio guidance, Co-Survival Haptic Receiver / spacesuit haptic navigation cues, AR/voice wayfinding assistance, firefighter/first-responder/EVA crew IR/NVG high-contrast overlay, tactile guidance, and post-disaster telemetry analytics.
* **[L1] Perception & Estimation Fabric:** Multi-spectrum (visible/IR) feature extraction modules, microphone array Direction of Arrival (DOA) & acoustic signal processing, BLE Auracast / UWB RF processing, estimation filtering algorithms (EKF, Doppler/phase probabilistic models), sensor fusion engines (gyro/IMU/acoustic/LiDAR), AI state estimators, self-healing mesh networking, confidence verification modules, and local ring-buffer telemetry loggers.
* **[L0] Infrastructure & Optical/Acoustic/RF Layer:** ISO 7010 emergency signage, fire hose cabinet/alarm terminal box internal & external status indicators (red/multi-spectrum LED) & directional sound emitters, spacecraft/ceiling raceway multi-spectrum/acoustic/BLE Auracast/UWB emitters, non-volatile heat-resistant flash memory modules embedded within fire cabinet / space module internal chambers, passive QR tags, emergency power interfaces, and non-contact reception sensors.

---

## 2.5 AI Governance & Model Architecture

* **Abstract Master AI Engine Definition (Anti-Circumvention):**
  The AI processing unit is not restricted to specific model parameters, neural topologies, chipsets, or execution environments. It encompasses all abstract perception and estimation entities, including edge AI, small Language/Vision/Audio models (sLLM/SVM/SAM), cloud/satellite-tethered large models (LLM/VLM), multi-spectrum vision and acoustic signal neural networks (CNN/Transformer/Audio Spectrogram Transformer), and hybrid edge-cloud topologies.

* **Rationale for Edge AI / sLLM / Small Vision-Audio Model Deployment:**
  Disaster environments involve severe blackout conditions, power cuts, server destruction, and communications blackout. Additionally, mobile, tactile, spacesuit-embedded, and AR end-user devices operate under strict power and compute constraints. Therefore, optimized edge-native AI models (sLLM, SVM/SAM, NPU firmware engines) capable of low-latency, offline multi-sensory operation are established as the primary implementation embodiment.

* **Core AI Functions:**
  * **Multi-Spectrum & Spatial Acoustic/RF Perception:** Asynchronously isolates ISO 7010 pictograms, internal/external fire cabinet indicators, raceway IR/visible emitters, acoustic anchor frequencies, and BLE Auracast/UWB signals amidst dense smoke, ambient fire noise, backlight distortion, and zero-gravity uniform smoke dispersion.
  * **Dynamic Offset Correction:** Computes real-time zero-point calibration matrix to mitigate cumulative IMU/gyroscope drift errors via Kalman filtering, Direction of Arrival (DOA) audio phase calculations, and probabilistic state estimation.
  * **Confidence Control & Adaptive Signal Generation:** Suppresses hallucinated guidance when perception confidence drops below thresholds, and independently generates tailored multi-sensory guidance (visible/spatial audio/vibrations for civilians and crew, IR/NVG/tactile vibrations for first responders and EVA personnel).
  * **Data Feedback & Model Self-Evolution:** Utilizes recovered blackbox telemetry logs as AI training datasets to analyze actual human and crew evacuation behaviors and structural bottlenecks, dynamically refining real-time rerouting algorithms and zero-point calibration weights.

---

## 3. Core System Blocks and Mechanisms

### A. ANCHOR Signage, Internal/External Fire Cabinets, Acoustic/RF Anchors & Raceway Sensing Unit (Absolute Reference Infrastructure)
* ISO 7010 standard emergency signs, building fire hose cabinets, alarm terminal boxes, power control panels (surface status LEDs, housing geometry, internal protective chambers, inner door surfaces), ceiling/wall raceways, directional audio speakers / spatial sound anchors (Acoustic Anchors), and BLE Auracast / UWB wireless broadcast modules act as absolute spatial reference nodes (ANCHOR).
* Under zero-visibility dense smoke environments and microgravity smoke blockouts, directional spatial audio, frequency-modulated acoustic signals, and BLE/UWB Auracast emergency broadcast streams emitted from ANCHOR nodes provide multi-sensory zero-point calibration.
* Transmits specialized multi-channel guidance to first responders, search-and-rescue teams, and astronauts via tactile vibration signals, high-penetration acoustic frequencies, and specialized RF data streams, ensuring clear directionality even in deafening fireground environments.
* Operates via non-contact optical, acoustic, and RF reception without requiring electrical or physical modifications to existing legacy infrastructure or spacecraft hulls.

### B. ESTIMATION & Multi-Sensory Auxiliary Guidance Unit (Estimation & Processing)
* **Feature Extraction:** Extracts ISO pictogram geometries, internal/external fire cabinet status indicators, raceway multi-spectrum corner points, acoustic phase/delay/DOA (Direction of Arrival) spectrogram features, and BLE/UWB RF signal metrics from optical camera, microphone array, and RF receiver feeds.
* **Estimation Algorithm (Input / Process / Output):**
  * **Input:** Relative movement vectors from IMU/gyroscope/LiDAR/acoustic/RF sensors, optical ANCHOR features, and acoustic/RF phase/DOA observations.
  * **Process:** Real-time correction of IMU cumulative drift matrices using AI state estimators, Extended Kalman Filters (EKF), acoustic triangulation, and Gaussian probability models.
  * **Output:** 3D spatial state coordinates with error covariance matrices, alongside synchronized visual, spatial audio, BLE LC3 audio, and haptic direction signals (e.g., localized tactile vibrations indicating directional guidance).
* **Signal Generation & Confidence Control:** Produces complementary visual, acoustic, and tactile wayfinding outputs; automatically halts guidance rendering if spatial confidence falls below safety thresholds.

### C. Emergency Power Integration & Operating Duration
* **Mandatory Emergency Power Interface:** Integrates with building and space module emergency power systems (generators, UPS, auxiliary battery circuits) or incorporates dedicated local energy storage to guarantee blackout operation.
* **Power Source Agnosticism:** Encompasses all energy storage formats, including lithium-based cells, LFP, solid-state batteries, supercapacitors, optical/thermal/acoustic energy harvesting, and hybrid configurations.
* **Comprehensive Operating Duration Range:** Encompasses all operating durations, ranging from initial evacuation periods under 2 hours (including statutory 20-minute and 60-minute baselines) to extended mission windows of 2 to 4+ hours (extending up to 6h, 12h, 24h+) required for firefighter and astronaut rescue operations.

### D. Self-Healing Multi-Mesh & Zero-Downtime Fail-Over
* **Independent Multi-Mesh Topology:** Nodes form peer-to-peer (P2P) N-mesh topologies independent of single central lines.
* **Dynamic Self-Healing:** Upon physical destruction of any node, the mesh isolates the failed node within 100ms and reroutes communication, compute, acoustic, RF broadcast, and telemetry logging tasks around the failure point.
* **Zero-Downtime Fail-Over:** Adjacent functional nodes autonomously assume spatial calculation, optical emission, RF broadcasting, telemetry logging, and spatial audio/haptic rendering tasks of destroyed units, maintaining uninterrupted wayfinding execution.

### E. Co-Survival Haptic Receiver — High-Efficiency Emergency Haptic Compass & Co-Survival Integration Specification
* **Acoustic Component Elimination for High-Noise & Zero-G Immunity:** To overcome the complete degradation of voice prompts in emergency environments exceeding 100dB siren noise or microgravity visual blockout, speaker drivers, DACs, and high-cost audio circuitry are eliminated. The standard receiver architecture consists strictly of a `receiver SoC + MCU + dual left/right haptic transducers`, establishing a high-efficiency, low-power, and highly resilient dedicated emergency device. This architecture includes direct integration into spacesuit (IVA/EVA) headbands and inner linings.
* **Single-Purpose Design for Dedicated Public Utility:** By omitting general audio playback capabilities, the receiver functions strictly as a single-purpose emergency tool. When stored within AED boxes, fire cabinets, or space module lockers, this functional restriction suppresses risks of theft or private misuse, securing its role as dedicated public infrastructure.
* **Standard Haptic Compass Protocol:**
  * **Turn Left:** Left Pulse-Pulse (2x) — Signal: Left: 100ms ON / 100ms OFF / 100ms ON — Tactile Location: Left transducer positioned against temple or left spacesuit lining.
  * **Turn Right:** Right Pulse-Pulse (2x) — Signal: Right: 100ms ON / 100ms OFF / 100ms ON — Tactile Location: Right transducer positioned against temple or right spacesuit lining.
  * **Move Forward:** Dual Continuous Pulse — Signal: Dual: 400ms Continuous Pulse — Tactile Location: Simultaneous activation of both transducers.
  * **Stop / Hazard:** Dual Long Vibration — Signal: Dual: 1200ms Long Vibration — Tactile Location: Simultaneous long pulse warning of hazard.
  * **Anchor Reached:** Dual Triple Pulse (3x) — Signal: Dual: 50ms ON / 50ms OFF (3 Cycles) — Tactile Location: Zero-point calibration completion signal.
* **Co-Survival Leadership & Evacuation Guide Hub Role:** Evacuees equipped with the receiver receive intuitive spatial orientation without spoken words. This enables them to act as field evacuation hubs who actively guide and lead disoriented civilians, children, elderly individuals, or crew members toward safety.

### F. Rapid Onboarding & Normal-State Privacy Isolation Specification
* **Normal-State Disconnection & Privacy Preservation:** Prior to an emergency, L0 ANCHOR Auracast/RF transmissions remain inactive (transmitting low-power bursts under 0.1s per minute). Physical and logical connections with civilian mobile devices are severed. Location tracking, data harvesting, and battery drain during normal conditions are strictly suppressed.
* **Active Emergency Switch & 3-Second Onboarding:** Upon fire or emergency alarm signal detection, RF broadcasting automatically activates. Scanning a passive QR tag affixed near signage, fire cabinets, or space module hatches triggers a deep-link (`last-light://{anchor_id}?b={broadcast_id}&k={public_temp_key}`), onboarding the device into the emergency guidance channel within 3 seconds without app installation or complex pairing.
* **Visibility-Impaired Auto-Discovery:** If smoke or microgravity smoke dispersion obscures the physical QR tag, mobile devices automatically search and attach to the two strongest nearby RF Auracast anchor signals.
* **Passive QR Tag Installation Standards:** QR tags contain no personal data and require no external power. Tags must be placed so as not to obscure statutory lighting surfaces or mandatory safety markings.

### G. Multi-Sensory Anchor Evacuation Guidance Structural Specification
* **Context:** Designed for blackout, smoke-filled, and space station pressurized module disaster environments where visual navigation is severely impaired.
* **Wearable Hub Execution:** Evacuees and crew members utilizing Co-Survival Haptic Receivers process RF haptic cues to maintain directionality while guiding disoriented individuals toward safety.
* **Multi-Anchor Synergy:** ISO 7010 exit signs and red fire cabinet indicators act as primary visual spatial anchors, while ceiling raceway/tray units project spatial audio waves and RF coverage, forming an integrated multi-sensory guidance matrix.

### H. Distributed Heat-Resistant Local Blackbox Telemetry Specification
* **Distributed Heat-Resistant Local Blackbox Architecture:** L0 ANCHOR modules (embedded within fire-resistant internal cabinet chambers or space module protective enclosures) incorporate high-temperature non-volatile flash memory. During disaster events involving communication collapse, the module records spatial calibration matrices, RF transmission logs, and node destruction timelines in a local ring-buffer format covering the preceding N hours (1–2 hours).
* **Post-Disaster Forensics & Liability Proof:** In events involving central server destruction, structural collapse, or space module depressurization, surviving blackbox modules recovered from fire cabinets or module chambers provide physical evidence to reconstruct evacuation trajectories and verify system operational integrity.
* **Data Feedback & Model Self-Evolution:** Recovered blackbox telemetry datasets are ingested into offline AI training pipelines to analyze actual human movement latency, bottleneck formations, and smoke propagation dynamics, continuously refining real-time dynamic rerouting algorithms and calibration weights.

---

## 4. Dynamic Resource Management & Defensive Safety Control

* **Rate Limiter:** Dynamically caps frame, audio packet, and RF reception rates to prevent processor saturation under excessive inputs.
* **Random Sampling Scan:** Asynchronously samples ambient lighting, glare, and acoustic/RF noise variations to isolate invalid inputs into sandboxed buffers.
* **Relocation Interception:** Blocks offset correction routines if unauthorized glare, reflections, spoofed audio, or rogue RF packets are detected.
* **T-Reg Suppressor:** Hardware-throttles AI and positioning compute cycles if system power or compute utilization exceeds safety limits.
* **Tri-State Isolation:** Switches control interfaces to a High-Z (High-Impedance) state within 0.1 seconds upon detecting internal processing faults, suppressing interference with statutory equipment.

---

## 5. Standards Alignment and Legal Boundaries

* **Standards Compliance:** Conforms to ISO 7010, ISO 16069, Bluetooth SIG specifications, UWB standards, statutory fire safety optical conventions, and acoustic signaling standards without claiming exclusive proprietary rights over international standards.
* **Non-Replacement of Statutory Equipment:** Does not replace, alter, or satisfy statutory fire safety lighting/alarm requirements or space module statutory safety requirements; operates strictly as a supplementary reference framework.
* **Physical Operational Limits:** Acknowledges that extreme smoke density, severe acoustic noise, or RF shielding may degrade sensory line-of-sight; primary evacuation responsibility remains with statutory systems and emergency authority personnel.

---

## 6. Industrial Applicability and Future Extensions

* **Smart Underground Raceway & Spacecraft Raceway Anchors:** Multi-spectrum dual emitters, directional audio modules, and BLE Auracast/UWB anchors deployed along ceiling raceways for autonomous parking robot calibration, orbital rover positioning, and emergency wayfinding.
* **Internal/External Fire Cabinet & Orbital Module 3D Spatial Anchors:** Utilization of fire hose cabinet status lights, internal chamber modules, and space module chambers as zero-point reference nodes in zero-visibility corridors.
* **Space Station Pressurized Module & IVA/EVA Spacesuit Guidance:** Multi-sensory navigation for space station pressurized modules during fire or depressurization events, routing astronauts to airlocks and escape vehicles via spacesuit-embedded haptic compasses and NVG HMDs.
* **AMR & Disaster Relief Robotics Indoor/Space Positioning:** Absolute offset correction for logistics and search-and-rescue robots operating in GPS-denied underground facilities or space habitats via optical, acoustic, and RF anchor fusion.

---

## 7. Practical Protection

* **Original Authority Principle:** Technical and legal interpretations of this specification strictly prioritize the Korean original document (`README.ko.md`), while English and other translation versions serve solely for reference purposes.
* **Broad Scope Inclusion:** All structural concepts, including ANCHOR zero-point calibration, Co-Survival Haptic Receivers, Auracast/UWB haptic compass protocols, Tri-State Isolation, T-Reg Suppressors, distributed blackbox telemetry, spacesuit haptic integration, and AI model self-evolution described herein, apply generically for broad prior art coverage.
* **Separation of Commercialization Content:** This core whitepaper contains strictly Pure Open Source and prior art disclosures, while proprietary revenue models and business execution details are managed separately.
* **Defensive Publication & DPL License:** Serves as prior art to invalidate third-party patent attempts. Any entity initiating patent litigation against the author or ecosystem participants forfeits all license rights under DPL v1.0.
* **Prior Use Rights & Trade Secret Separation:** Secures legal prior use rights under Korean Patent Act Article 103 and 35 U.S.C. §273, while maintaining specific feature extraction neural weights and precise haptic timing parameters as non-disclosed Trade Secrets.

---

## 8. Sources

* **Linked Survival Architecture:** GitHub - `soma-moa / ARCHITECTURE_STRATEGY.md v3.2.4`
* **Linked APU Controller:** GitHub - `deundeuni / chiplet-apu-multi-system-survival-architecture v2.6`
* **Linked Marine Armor:** GitHub - `soma-moa / MAX-LIFE ICE-BELT v1.6`
* **Linked CWP 4-Hardware Repositories:**
  * GitHub - `deundeuni / CWP-Entry`
  * GitHub - `deundeuni / CWP-Rolling-Self-Align-Battery-Swap-System`
  * GitHub - `deundeuni / CWP-Battery-Swap`
  * GitHub - `deundeuni / CWP-Clamping-Battery-Swap-System`
* **Canonical Gateway:** `somamoa.ai.kr` (Canonical Gateway)
* **International Standards:** ISO 7010, ISO 16069, Bluetooth SIG Auracast / LE Audio Specifications, UWB Standards, Korean Fire Safety Standards.
* **Legal Precedents:** Korean Patent Act Article 103, 35 U.S.C. §273.
* **Document Completeness:** This document possesses self-contained engineering and legal integrity.

---

## Appendix A: Inventorship
* System Architect & Sole Inventor: deundeuni
* Primary Repository: github.com/soma-moa
* License: CC BY 4.0 (Attribution Required) + DPL v1.0

---

## Appendix B: Version History
* v1.0 (2026-07-30): Initial visual anchoring concept formulation.
* v2.0 ~ v3.0 (2026-08-30): Full-stack structural design, raceway dual-spectrum emitters, edge AI governance, and self-healing multi-mesh fail-over.
* v3.1 ~ v3.6 (2026-08-30): Independent prior research (0.8), AI disclosure (Appendix C), emergency power (3.C), sensor fusion baseline (0.2), fire cabinet anchor specs (3.A), spatial audio, and bone-conduction specs.
* v3.7 (2026-08-31): Personal wearable integration (3.E), normal-state privacy isolation and rapid onboarding (3.F), and multi-sensory structural guidance concept (3.G).
* v3.8 (2026-08-31): Co-Survival Haptic Receiver naming adoption, public infrastructure design integration, and standard haptic compass protocol specification (3.E).
* v3.9 (2026-09-01): Integration of Distributed Heat-Resistant Local Blackbox Telemetry (3.H) and telemetry log-driven AI evacuation model self-evolution mechanisms.
* v4.0 (2026-09-06): Cross-referenced master survival architecture (`ARCHITECTURE_STRATEGY v3.2.4`), APU controller (`chiplet-apu v2.6`), marine armor (`MAX-LIFE ICE-BELT v1.6`), and CWP 4-Hardware mechanisms.
* v4.1 (2026-09-06): Integrated space station pressurized modules, microgravity zero-visibility smoke navigation, and IVA/EVA spacesuit haptic compass protocols.

---

## Appendix C: AI Assistance Disclosure
* Original Architecture & Concepts: deundeuni (Human) — Sole Inventor, overall system architecture, field motivation, and final decision-making authority.
* Draft Generation: Meta AI — Initial draft generation and structural scaffolding assistance.
* Document Structuring & Expansion: Gemini — Structural refinement, terminology standardization, raceway/fire cabinet optics, spatial audio anchors, Co-Survival Haptic Receivers, BLE Auracast integration, distributed blackbox telemetry, space station module integration, and master reference framework expansion.
* Review & Technical Validation: Claude — Technical verification, nomenclature standardization, and legal defense framework validation.

---

## Appendix D: Legal Disclaimer & Responsibility Limitation
* **Non-Replacement of Statutory Equipment:** The technology disclosed in this specification (LAST-LIGHT v4.1), including software, QR tags, BLE Auracast/UWB fabrics, spatial audio anchors, Co-Survival Haptic Receivers, and distributed blackboxes, does not replace the statutory, physical, or functional performance of mandatory emergency lighting, fire alarm systems, or hydrant indicators required by fire safety legislation or space agency standards. It functions solely as a supplementary reference aid.
* **Limitation of Liability:** The original inventor (`deundeuni` / `soma-moa`) and development ecosystem contributors assume no civil or criminal liability for evacuation delays, communication failures, sensory perception errors, telemetry data loss, personal injury, property damage, or legal disputes resulting from the implementation or application of this specification, open-source code, or passive QR onboarding tags. All evacuation decisions and safety management remain the sole responsibility of facility operators, evacuees, astronauts, and emergency response authorities.
* **Intellectual Property & Trademark Disclaimer:** All technical standards cited herein (such as Bluetooth SIG and ISO) are referenced strictly for illustrative compliance purposes. There is no intent to infringe upon third-party trademarks or brand rights. All technical expressions shall be construed as general, vendor-neutral technology concepts.
