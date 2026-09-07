> **Multilingual Publication Notice:** This document is a dual-language (Korean/English) publication of identical content. v4.2 2026-09-07 (Korean Version: [README.ko.md](README.ko.md))  
> **Original Authority Notice:** The supreme authority for legal and engineering interpretation of this technical specification belongs to the Korean original (`README.ko.md`), and the English version serves as an auxiliary reference only. (`README.ko.md` is authoritative original)

# LAST-LIGHT — Auxiliary Guidance System Technical Specification Utilizing Always-On Standard Signage, Firefighting Terminal Boxes (Internal/External), Smart Raceways, Space/Orbital Module Evacuation Infrastructure, Multisensory Spatial Audio, Co-Survival Haptic Transceivers, and Distributed Local Black Box Infrastructure (Ver. 4.2 Final Revised)

* **Official Document Classification:** Defensive Publication / Prior Art Specification
* **Initial Conception Date:** 2026-07-30 / **Final Revision Date (v4.2):** 2026-09-07
* **Original Intellectual Property (IP) Holder:** soma-moa (Architect: deundeuni)
* **Primary Repository:** github.com/soma-moa | **Canonical Gateway:** somamoa.ai.kr
* **Applied Licenses:** CC BY 4.0 & DPL v1.0 (Defensive Patent License)
* **Search Keywords:** LAST-LIGHT, Evacuation Guidance, Location Correction, ISO 7010, Co-Survival Haptic Receiver, Haptic Compass, BLE Auracast, Tri-State Isolation, T-Reg Suppressor, Distributed Local Blackbox, Space Station Evacuation, Zero-Gravity Evacuation, Orbital Module Anchor, IVA/EVA Spacesuit Haptics, Prior Art, ARCHITECTURE_STRATEGY, chiplet-apu, CWP, MAX-LIFE ICE-BELT

---

## 0. Inventor's Declaration and Motivation

### 0.1 Field-Driven Motivation
This architectural framework originated from a solemn commitment: "To help even one more person evacuate safely during disasters, and to ensure firefighters and rescue personnel entering extreme hazard zones return safely home to their families."
In fire and disaster emergencies, environments become overwhelmed by legal sirens exceeding 100dB and extreme ambient noise, rendering acoustic voice prompts ("turn left," etc.) completely useless while evacuees suffer acute auditory overload. Furthermore, in microgravity or zero-gravity orbital modules (space stations) and sealed pressure compartments, the absence of thermal buoyancy prevents smoke from rising, causing uniform 3D expansion and zero-visibility conditions. To overcome these limitations, a 'Tactical Haptic Compass' mechanism was invented, transmitting intuitive direction directly through bone and skin independent of vision, sound, language barriers, or protective gear.
By employing 24/7 always-on exit signs (ISO 7010), indoor fire hydrant boxes, call point terminal enclosures, and ceiling/wall cable raceways as "Visual, Optical, Acoustic, and Wireless RF Absolute Anchors," general evacuees receive green visible light and bilateral haptic feedback via personal/spacesuit-integrated "Co-Survival Haptic Receivers." Simultaneously, firefighters and rescue teams receive distinct guidance via IR/NVG high-contrast fluorescent/white markers and specialized tactical vibration signals.
Additionally, fire hydrant enclosures and fire-rated module compartments house "Distributed Heat-Resistant Local Black Boxes" recording recent evacuation trajectories in a ring buffer, establishing a self-evolving AI framework driven by post-disaster data forensics.

### 0.2 Master Concept & Sensor Fusion Standard
The visual, optical, acoustic, and RF ANCHOR zero-point calibration mechanism disclosed herein serves as the Master Reference Framework for the entire positioning and auxiliary guidance architecture.
Any expanded implementation integrating Gyroscopes, Accelerometers, Inertial Measurement Units (IMU), Microphone Arrays, Acoustic/Ultrasonic Sensors, Bone Conduction/Tactile Haptic Transducers, BLE Auracast RF Modules, UWB Modules, Heat-Resistant Black Box Memory, LiDAR, ToF, Thermal Imaging, Infrared, or other positioning/sensing means—whether individually or in combination—constitutes an auxiliary enhancement built upon this core calibration framework, and remains fully within the scope of this prior art declaration.

* **Form-Factor & Stimulus Agnostic Rule:** The wearable receiver of this guidance system is not restricted to earphones, headphones, or bone-conduction devices. It encompasses smartwatches, wristbands, rings (smart rings), patches, belts, footwear, clothing-embedded modules, spacesuit (IVA/EVA) inner linings, and any other human-body contact forms. Furthermore, direction-transmitting tactile mechanisms are not limited to Eccentric Rotating Mass (ERM) or Linear Resonant Actuators (LRA), but broadly encompass localized pressure differentials, electrical stimulation, micro-temperature shifts, piezoelectric haptics, and all sensory methods conveying intuitive directional perception.
* **System Hierarchy Linkage:** The zero-point anchor calibration, 100ms self-healing mesh, and Tri-State isolation control of LAST-LIGHT serve as sub-system implementations of the general survival architecture in `ARCHITECTURE_STRATEGY v3.2.4` and the T-Reg suppression/local isolation logic in `chiplet-apu-multi-system-survival-architecture v2.6`. The raceway/fire-box clamping mechanisms instantiate CWP hardware frameworks, while the 100ms isolation lifecycle algorithm shares the core survival philosophy of `MAX-LIFE ICE-BELT v1.6`.

### 0.3 Zero-Downtime & Non-Contact Principle
This architectural design strictly prohibits physical or electrical modifications to existing statutory fire, safety, or space module infrastructure. It prioritizes zero-downtime fail-over survival, ensuring that even if specific modules are destroyed by impact or fire, the broader network continues operating. Each module maintains independent multi-mesh connections to eliminate Single Points of Failure (SPOF), enabling adjacent nodes to instantly inherit computation and local black box telemetry logging.

### 0.4 Non-Exclusive Interoperability & Open Public Standard
This architecture is not proprietary to any specific optical camera, vision sensor, microphone array, LiDAR, mobile device, Co-Survival Haptic Receiver, spacesuit HMD/haptic transducer, or robotic vision framework. It operates as an open public standard utilizing public always-on visual signage (ISO 7010 series), fire box indicator lights, acoustic beacons, BLE Auracast transmitters, and raceway optical/acoustic/RF anchors as auxiliary reference points.

### 0.5 Operational Priority Control Principle
During emergency bandwidth or computational overload, the system prioritizes absolute reference point (ANCHOR) identification, position calibration, and critical telemetry recording above all else. Secondary tasks, such as high-definition visual restoration or supplementary graphics generation, are systematically suppressed to maintain continuous positioning guidance.

### 0.6 Universal Application Scope
This architectural framework broadly applies to smartphone evacuation applications, Co-Survival Haptic Receivers, wristband/ring/garment haptic units, spacesuit (IVA/EVA) internal haptic guidance pads, distributed black box forensic modules, emergency position recalibration units for autonomous logistics/orbital exploration robots, smart emergency lighting/acoustic anchors in buildings and space stations, indoor fire hydrant indicators, underground parking/spacecraft raceway anchors, disaster rescue AR glasses, firefighter/astronaut NVG equipment, and all auxiliary positioning systems requiring visual, optical, acoustic, or tactile perception.

### 0.7 Disclosure Purpose & Limitation Notice
This document is published as a defensive prior art declaration. All functions, configurations, and performance metrics described herein are illustrative and do not constitute a guarantee of specific implementation. This system does not replace, modify, or alter statutory fire safety equipment, obligations, or standards, and functions purely for auxiliary and reference purposes.

### 0.8 Acknowledgement of Independent Prior Research
This system architecture was independently formulated by the sole inventor. However, the possibility that similar concepts were developed independently by other researchers, inventors, or institutions is explicitly acknowledged. The purpose of this publication is not to claim exclusive monopoly, but to record intuitive conceptual frameworks and system integration strategies as open public prior art, preventing private monopolization and enabling unrestricted development for public safety.

---

## 1. Version History

* v1.0 (2026-07-30): Initial visual anchoring concept.
* v2.0 ~ v3.0 (2026-08-30): Full-stack applied architecture design, raceway dual IR/visible spectrum integration, edge AI light models, and self-healing multi-mesh failover mechanisms.
* v3.1 ~ v3.6 (2026-08-30): Integration of independent research acknowledgment (0.8), AI disclosure appendix (Appendix C), emergency power scope (3.C), sensor fusion master reference (0.2), fire box anchors (3.A), and directional audio/bone conduction specifications (3.A, 3.B).
* v3.7 (2026-08-31): Integration of personal wearable connectivity (3.E), idle-state isolation and emergency onboarding (3.F), and multisensory anchor structural specifications (3.G).
* v3.8 (2026-08-31): Introduction of "Co-Survival Haptic Receiver" for 100dB noise environments, public infrastructure deployment model, and standard haptic compass protocol table (3.E).
* v3.9 (2026-09-01): Integration of fire-box internal "Distributed Heat-Resistant Local Blackbox Telemetry" (3.H) and forensic log-driven AI self-evolving evacuation path re-learning.
* v4.0 (2026-09-06): Integration of cross-references with parent architecture (`ARCHITECTURE_STRATEGY v3.2.4`), APU controller (`chiplet-apu v2.6`), marine armor (`MAX-LIFE ICE-BELT v1.6`), and CWP hardware repositories.
* v4.1 (2026-09-06): Expansion to space station pressurized modules, zero-gravity smoke diffusion evacuation, IVA/EVA spacesuit haptic compass integration, and wearable form-factor/stimulus agnostic rules.
* v4.2 (2026-09-07): **[Technical/Legal Specification Enhancement]** Clarification of subsystem-level response timescales (0.1s network isolation vs. 0.1ms hardware E-Stop), addition of attorney consultation advisory for DPL/prior-use rights. **[Direct Refinement by Designer]** Unified single-source version history structure, standardized terminology, and refined defensive legal phrasing across the specification executed directly by the architect (deundeuni) utilizing conversational AI assistance tools.

---

## 2. 3-Tier Applied Architecture

* **[L2] Auxiliary Guidance & Specialized UI Layer**
  * General Evacuees/Crew: Green visible light, spatial audio, Co-Survival Haptic Receivers (earphones, bands, rings), spacesuit haptic directional prompts, AR/voice guidance.
  * Firefighters/Rescue/EVA Crew: IR/NVG high-contrast visual cues, specialized tactical vibration patterns, directional audio, backend telemetry transmission.
  * Command & Forensics: Post-disaster black box log recovery and bottleneck analytics reporting for buildings/orbital modules.
* **[L1] Perception & Estimation Fabric Layer**
  * Visible/IR multispectral visual feature extraction, microphone array Direction of Arrival (DOA) estimation, BLE Auracast/UWB reception.
  * Estimation Algorithms (Kalman Filter, Doppler/phase-difference probability models), IMU/Gyroscope/LiDAR sensor fusion engine.
  * AI State Estimator, distributed self-healing mesh fabric, confidence validator, ring-buffer local black box logging.
* **[L0] Infrastructure & Optical/Acoustic/RF Layer**
  * ISO 7010 exit signage, indoor fire hydrant/call point indicator lights (Red/LED), space module internal anchors.
  * Heat-resistant non-volatile flash memory (Blackbox Module) inside fire hydrant boxes and module fire-rated chambers.
  * Directional speakers/acoustic anchors, ceiling/wall raceways with multi-wavelength light, sound, and BLE Auracast/UWB broadcast nodes.
  * Passive QR tags, emergency power interconnects/independent power supplies, non-contact optical/acoustic/RF receivers.

---

## 2.5 AI Governance & Model Architecture

* **Broad AI Engine Definition:**
  The AI processing unit is defined as an abstract perception and estimation entity. It is not limited to specific model parameter sizes, neural network topologies, chip architectures, or execution locations. It encompasses on-device edge AI, lightweight networks, server/cloud/satellite-linked large models (LLM/VLM/Audio AI), multispectral vision/audio transformers (CNN/Transformer/Audio Spectrogram Transformer), and hybrid configurations.
* **On-Device Edge AI (sLLM / Small Vision-Audio Model):**
  Disaster environments assume power outages, destruction of central servers, and complete network blackouts. Furthermore, mobile devices, haptic receivers, and spacesuit modules operate under strict power and compute constraints. Therefore, ultra-low-power, ultra-low-latency on-device edge AI models (sLLM, Small Vision/Audio Models, NPU firmware AI engines) are established as the primary implementation embodiment.
* **Core AI Estimation & Governance Roles:**
  * Multispectral Perception: Asynchronously isolates ISO pictograms, fire box LEDs, raceway IR emitters, acoustic anchors, and BLE/UWB RF signals amidst heavy smoke, acoustic noise, glare, or microgravity smoke expansion.
  * Dynamic Drift Calibration: Fuses IMU/Gyroscope relative motion vectors with ANCHOR spatio-temporal observations using Kalman filtering and DOA processing to eliminate cumulative drift.
  * Confidence Validation & Differential Signaling: Automatically suppresses guidance upon confidence degradation to prevent hallucination, generating differentiated output streams for evacuees (visible light/spatial audio/haptics) and rescue teams (IR/NVG/tactile).
  * Forensic Feedback Learning: Re-trains routing models using recovered black box log datasets to evaluate real human/crew behavioral bottlenecks and evolve dynamic evacuation paths.

---

## 3. Core System Blocks and Operational Mechanisms

### A. ANCHOR Signage, Fire Boxes, Acoustic/RF Beacons & Raceway Sensors (Absolute Reference Infrastructure)
* Establishes ISO 7010 signage, fire hydrant indicator lamps, control panel boxes, and ceiling/wall raceways as absolute spatial reference points (ANCHORs).
* Enables multisensory zero-point calibration even during zero-visibility smoke conditions by receiving spatial audio, frequency-modulated acoustic signals, and BLE Auracast/UWB emergency broadcasts.
* Controls multi-channel signal outputs, providing NVG visual markers, tactile haptic patterns, and specialized data feeds for firefighters, rescue teams, and astronauts.
* Collects optical, acoustic, and RF features non-invasively without electrical or physical alteration to statutory infrastructure.

### B. ESTIMATION Correction & Multisensory Guidance Unit (Auxiliary Receiver Domain)
* Feature Extraction: Extracts image corner keypoints, acoustic phase delays, Direction of Arrival (DOA), and BLE/UWB Signal Strength (RSSI/AoA).
* Estimation & Correction Algorithm:
  * Input: Motion vectors from Gyroscope/IMU/LiDAR combined with ANCHOR relative distance, angle, acoustic phase, and RF observations.
  * Processing: AI State Estimator, Extended Kalman Filter (EKF), and acoustic triangulation/Doppler compensation to correct inertial sensor cumulative drift matrix.
  * Output: 3D spatial coordinates and directional guidance signals (including bilateral haptic compass pulse patterns).
* Confidence Control: Automatically halts guidance if feature perception confidence drops below safety thresholds.

### C. Emergency Power & Operating Duration Specifications
* Power Integration: Must interface with building/spacecraft emergency power grids or incorporate independent auxiliary power units (batteries, supercapacitors, energy harvesting).
* Power Architecture Scope: Encompasses lithium-ion, LiFePO4, solid-state, supercapacitor, ambient energy harvesting, and hybrid storage systems.
* Operating Duration: Encompasses immediate evacuation windows (<2 hours), rescue/extinction operational windows (2–4 hours), and extended post-disaster survival windows (6, 12, 24+ hours).

### D. Self-Healing Multi-Mesh & Fail-Over Fabric
* Independent N-Mesh: Nodes form autonomous peer-to-peer (P2P) wireless mesh fabrics independent of central communication trunks.
* Dynamic Self-Healing: Upon node destruction, adjacent nodes isolate the fault within 100ms and re-route telemetry, acoustic, and RF broadcast paths.
* Zero-Downtime Fail-Over: Calibration, optical emission, RF broadcast, and local black box logging duties of a failed node are instantly inherited by surviving neighbor nodes.

### E. Co-Survival Haptic Receiver — High-Efficiency Haptic Compass & Swarm Integration
* High-Noise & Zero-Visibility Resilience: In environments exceeding 100dB siren noise where voice guidance fails, the standard receiver eliminates speakers, DACs, and audio components. It consists solely of an RF/BLE receiver chip, MCU, and two or more lateral haptic transducers. Form factors include earphones, wristbands, rings, footwear, adhesive patches, clothing layers, and spacesuit (IVA/EVA) inner linings.
* Single-Purpose Public Infrastructure Design: Lacks music playback or general audio capabilities, preventing personal misappropriation or theft, thereby ensuring permanent availability as public safety infrastructure.
* Standard Haptic Compass Protocol:
  * Turn Left: Left transducer double pulse (Left: 100ms ON / 100ms OFF / 100ms ON)
  * Turn Right: Right transducer double pulse (Right: 100ms ON / 100ms OFF / 100ms ON)
  * Move Forward: Dual transducers simultaneous medium pulse (Dual: 400ms Continuous Pulse)
  * Hazard / Stop: Dual transducers long continuous vibration (Dual: 1200ms Long Continuous Vibration)
  * Anchor Reached / Calibrated: Dual transducers triple short pulse (Dual: 50ms ON / 50ms OFF, 3 Cycles)
* Co-Survival Swarm Leadership: Wearers navigating via haptic prompts intuitively assume the role of Evacuation Guide Hubs, leading surrounding panic-stricken individuals to safety without requiring verbal communication.

### F. Rapid Onboarding & Privacy Isolation
* Idle State Privacy Protection: During normal operations, L0 ANCHOR Auracast/RF functions remain in an ultra-low-power idle state (<0.1s burst per minute), completely isolated from personal devices to prevent tracking, data collection, or battery drain.
* Emergency Activation & 3-Second Onboarding: Upon fire/disaster detection, RF broadcasting activates. Scanning passive QR tags on signage or fire boxes executes a deep link (`last-light://{anchor_id}?b={broadcast_id}&k={public_temp_key}`), completing channel onboarding within 3 seconds.
* Zero-Visibility Automatic Search: If smoke prevents QR scanning, receivers automatically scan and pair with the strongest ambient emergency RF broadcast signals.
* Tag Deployment Principles: Passive, non-powered QR tags are installed on non-functional surfaces without obscuring statutory signage graphics.

### G. Structural Multisensory Guidance Concept
* Operational Context: Designed for zero-visibility, smoke-filled, or microgravity disaster environments such as underground parking facilities, transit tunnels, or space station modules.
* Swarm Guidance Mechanics: Receivers process RF haptic streams to guide wearers, who physically assist surrounding non-equipped evacuees toward safety.
* Multi-Anchor Fusion: Integrates wall-mounted ISO 7010 exit signs and red fire hydrant LEDs as primary visual anchors, augmented by overhead raceway nodes broadcasting spatial audio and RF positioning signals.

### H. Distributed Heat-Resistant Local Blackbox Telemetry
* Distributed Thermal-Protected Architecture: L0 nodes house heat-resistant non-volatile flash memory within fire-rated enclosures (e.g., hydrant boxes, spacecraft chambers), logging local zero-point calibrations, RF telemetry, and node failure events in a ring buffer for recent operational hours (1–2+ hours).
* Post-Disaster Forensics: Surviving memory chips recovered from collapsed or burnt structures provide immutable evidence to reconstruct evacuee movement paths and verify system operational integrity.
* Self-Evolving Route Feedback: Recovered telemetry datasets are fed back into AI training pipelines to map structural bottlenecks and optimize dynamic evacuation routing algorithms for future events.

---

## 4. Dynamic Resource Management & Safety Control

* **Rate Limiter:** Throttles visual frame processing, acoustic packets, and RF sampling rates to prevent processing pipeline exhaustion.
* **Random Sampling Scan:** Asynchronously samples ambient optical/acoustic noise to isolate glare, reflections, reverberation, and spoofed packets into isolated buffers.
* **Relocation Interception:** Immediately halts position correction routines upon detecting fake lighting, acoustic spoofing, or unauthorized RF packet injection.
* **T-Reg Suppressor:** Hardware-level throttle that suppresses background processing loops when power or thermal thresholds are exceeded.
* **Tri-State Isolation:** Converts signal control lines to high-impedance (High-Z) states within 0.1s of an internal fault, physically and logically isolating the system from statutory equipment. (Note: The 0.1s/100ms isolation response of this network layer is distinct from the 0.1ms/100µs hardware E-Stop of underlying `chiplet-apu` motor controllers, reflecting hierarchical system response scales).

---

## 5. Standards & Legal Boundaries

* **Standard Compliance:** References public specifications including ISO 7010, Bluetooth SIG Auracast, UWB standards, and statutory fire safety codes as technical examples without claiming exclusive interpretation rights.
* **Non-Replacement of Statutory Equipment:** Does not replace, alter, or fulfill the legal obligations of statutory exit lights, fire alarms, or emergency broadcast systems under national fire or building safety regulations. Functions strictly as an auxiliary reference tool.
* **Physical Limitations:** System operation may degrade or halt under extreme smoke density, severe acoustic dampening, or complete RF shielding. Ultimate evacuation decisions remain with human operators and statutory rescue personnel.

---

## 6. Industrial Applications & Future Expansion

* **Smart Underground Parking & Spacecraft Raceways:** Deployment of dual IR/visible optical nodes, directional audio speakers, and BLE/UWB anchors along raceways for autonomous parking/exploration robot calibration and disaster evacuation.
* **3D Positioning Anchors in Fire Boxes & Orbital Modules:** Utilization of fire hydrant panels and space station internal frames as spatial zero-point calibration anchors for touch-based evacuation during zero-visibility events.
* **Space Station Modules & IVA/EVA Spacesuits:** Auxiliary guidance through spacesuit haptic bands and NVG HMDs during microgravity smoke diffusion or pressure vessel emergency events.
* **Autonomous Logistics & Rescue Robotics:** Indoor and orbital spatial drift correction for AGVs, search-and-rescue robots, and maintenance drones operating in GPS-denied environments.

---

## 7. Practical Protection & Legal Framework

* **Authoritative Original:** Legal and technical interpretation of this specification is governed exclusively by the Korean original (`README.ko.md`). English and other translations serve as reference materials only.
* **Broad Conceptual Scope:** All generic concepts—including ANCHORs, ESTIMATION modules, Co-Survival Haptic Receivers (regardless of form factor), Auracast/UWB haptic guidance, Tri-State Isolation, T-Reg Suppressors, distributed blackbox logging, spacesuit haptics, and AI feedback learning—are disclosed broadly as defensive prior art.
* **Commercialization Separation:** This whitepaper contains pure open-source specifications and prior art disclosures. Specific commercial implementations, business models, and monetization strategies are maintained in separate technical documents.
* **Defensive Publication & DPL:** Disclosed to defeat third-party patent claims. If any party implementing this technology initiates patent infringement litigation against the author or ecosystem contributors, their license under DPL v1.0 terminates immediately.
* **Prior-Use Rights & Trade Secrets:** Preserves prior-use rights under Article 103 of the Korean Patent Act and 35 U.S.C. §273. Exact neural network weights, feature extraction parameters, and fine-grained algorithm tuning remain proprietary trade secrets.
* **Attorney Consultation Advisory:** Implementation of DPL terms, prior-use right assertions, and utility model filing strategies should be reviewed by qualified patent attorneys. Specific claims and wording may be adapted during formal patent office filings.

---

## 8. Sources and Complete References

* **Parent Survival Architecture:** GitHub - `soma-moa / ARCHITECTURE_STRATEGY.md v3.2.4`
* **Parent APU Controller:** GitHub - `deundeuni / chiplet-apu-multi-system-survival-architecture v2.6`
* **Parent Marine Armor:** GitHub - `soma-moa / MAX-LIFE ICE-BELT v1.6`
* **Associated CWP Hardware Repositories:**
  * GitHub - `deundeuni / CWP-Entry`
  * GitHub - `deundeuni / CWP-Rolling-Self-Align-Battery-Swap-System`
  * GitHub - `deundeuni / CWP-Battery-Swap`
  * GitHub - `deundeuni / CWP-Clamping-Battery-Swap-System`
* **Canonical Gateway:** `somamoa.ai.kr`
* **International Standards:** ISO 7010, ISO 16069, Bluetooth SIG Auracast / LE Audio Specifications, UWB Standards, Statutory Fire Safety Codes.
* **Legal Guidelines:** Korean Patent Act Article 103, US Patent Code 35 U.S.C. §273.
* **Document Integrity:** This document constitutes a self-contained, complete technical specification.

---

## Appendix A: Inventorship
* System Architect & Sole Inventor: deundeuni
* Primary Repository: github.com/soma-moa
* License: CC BY 4.0 (Attribution Required) + DPL v1.0

## Appendix B: Version History
▶ Refer to Section 1 (Version History) in the main body.

---

## Appendix C: AI Assistance Disclosure & Tool Operational Rules
* Original Architecture & Concepts: deundeuni (Human) — Sole Inventor, responsible for all core architecture, field motivation, circuit topology, and technical decisions.
* Subordinate Drafting Tool: Meta AI — Used strictly as an auxiliary tool for initial paragraph drafting and visual concept structuring.
* Subordinate Structuring Tool: Gemini — Used strictly as an auxiliary tool for document section layout and terminology standardization.
* Subordinate Review Tool: Claude — Used strictly as an auxiliary tool for conversational context review and defensive phrasing refinement.
* ※ **Declaration of Inventorship:** All core system architectures, haptic compass protocols, control logics, and legal defensive frameworks are the exclusive intellectual work of the human inventor (deundeuni). AI models operated purely as subordinate text editing and formatting tools under the direct instruction and oversight of the inventor.

---

## Appendix D: Legal Disclaimer & Responsibility Limitation
* **Auxiliary Nature & Non-Replacement:** Technologies disclosed herein (LAST-LIGHT v4.2), including software, QR links, BLE Auracast/UWB protocols, spatial audio anchors, Co-Survival Haptic Receivers, and local black boxes, do not replace statutory exit signs, fire alarms, emergency lighting, or public address equipment required under building or fire safety codes. They function purely as auxiliary reference tools.
* **Limitation of Liability:** The author (deundeuni / soma-moa) and open-source contributors assume no civil or criminal liability for any direct, indirect, incidental, or consequential damages, evacuation delays, hardware failures, signal errors, or data loss resulting from the implementation or use of this specification, code, or associated documentation. All operations are conducted at the user's sole risk.
* **Trademarks & IP Disclaimer:** Referenced industrial standards (Bluetooth SIG, ISO, etc.) are cited purely for technical context and do not imply endorsement or infringement of third-party trademark rights. All technical terms are to be interpreted as broad, generic engineering concepts.
