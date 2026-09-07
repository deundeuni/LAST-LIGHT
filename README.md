> **Multi-language Disclosure Notice:** This document is published in both Korean and English with identical contents. v4.2 2026-09-07 (Korean version: [README.ko.md](README.ko.md))  
> **Original Authority Notice:** `README.ko.md` is the authoritative original text for all legal and engineering interpretations of this technical specification. This English document (`README.md`) serves as a secondary reference only.

# LAST-LIGHT — Technical Specification for Auxiliary Guidance System Utilizing Always-On Standard Signage, Fire Cabinet Interiors/Exteriors, Smart Raceways, Space/Orbital Module Evacuation Infrastructures, Multisensory Acoustics, Co-Survival Bridges, and Distributed Blackboxes (Ver. 4.2 Final Completed Version)

* **Official Document Classification:** Defensive Publication / Prior Art
* **Initial Concept Date:** 2026-07-30 / **Final Revision Date (v4.2):** 2026-09-07
* **Original IP Holder:** soma-moa (Founder: deundeuni)
* **Official Repository:** github.com/soma-moa | **Official Domain:** somamoa.ai.kr
* **License:** CC BY 4.0 & DPL v1.0 (Defensive Patent License)
* **Search Keywords:** LAST-LIGHT, Evacuation Guidance, Position Calibration, ISO 7010, Co-Survival Bridge, Haptic Compass, BLE Auracast, Tri-State Isolation, T-Reg Suppressor, Distributed Local Blackbox, Space Station Evacuation, Microgravity Evacuation, Orbital Module Anchor, IVA/EVA Spacesuit Haptics, Prior Art, ARCHITECTURE_STRATEGY, chiplet-apu, CWP, MAX-LIFE ICE-BELT

---

## 0. Inventor Declaration and Motivation

### 0.1 Field-Driven Motivation & Co-Survival Philosophy
This structural design originates from an earnest commitment: "May even one more person evacuate safely, and may firefighters and rescue personnel entering extreme disaster environments return safely to their waiting families."

In actual fire and disaster scenes, the environment suffers from simultaneous sensory isolation: complete darkness (visual isolation) caused by dense smoke and power outages, alongside auditory paralysis (auditory isolation) induced by statutory sirens and crowd clamor exceeding 100dB. Furthermore, under fire conditions in microgravity orbital modules (space stations) and enclosed living quarters, the absence of thermal buoyancy prevents smoke from rising, causing it to diffuse uniformly across 3D space into zero-visibility. Conventional voice prompts or visual signs become rendered ineffective in such conditions.

Addressing these realities, a tactile compass mechanism was created to convey intuitive direction through bone and skin without dependence on sound, sight, or language barriers (foreigners, elderly, hearing-impaired, or spacesuit wearers), aiming to provide practical assistance for survival in disaster-vulnerable environments. By establishing fixed 24-hour always-on emergency exit signs (ISO 7010), indoor fire hydrant boxes/break-glass terminal boxes, and ceiling/wall raceways as absolute visual, optical, acoustic, and wireless RF reference points (ANCHORs), the system guides general evacuees via green visible light and differential left/right haptic patterns through personal or spacesuit-embedded 'Co-Survival Bridges', while offering firefighters/rescuers a survival path identified via infrared/NVG high-contrast fluorescent/white light and specialized rescue vibration signals. Furthermore, by incorporating heat-resistant local blackbox modules inside fire cabinets and orbital compartments to record recent evacuation trajectories and telemetry into a ring buffer, a self-evolving AI framework based on recovered data was established.

Furthermore, by adopting the solidarity philosophy of 'Co-Survival'—where a wearer who gains directional certainty through intuitive haptic cues naturally leads surrounding confused individuals—as a core structural pillar, the system is designed so that technology serves as an auxiliary safety mechanism supporting human dignity and collaborative instincts under crisis.

### 0.2 Master Concept & Sensor Fusion Standard
The visual, optical, acoustic, and RF ANCHOR-based zero-point calibration and offset mechanism disclosed in this specification functions as the Master Reference Framework for the overall position estimation and auxiliary guidance system.
All expansion forms—whether utilizing Gyroscopes, Accelerometers, Inertial Measurement Units (IMU), Microphone Arrays, Acoustic/Ultrasonic Sensors, Bone-conduction/Tactile Vibration Transducers, BLE Auracast RF Modules, UWB Modules, Heat-resistant Blackbox Memories, LiDAR, ToF, Thermal Imaging, Infrared, or other positioning/sensor means, added individually or in combination—are auxiliary combinations referencing this master 0-point calibration mechanism and remain within the scope of this prior art.

* **Form-Factor & Stimulus Agnostic Rule:** Wearable receivers of this guidance system are not limited to earphone/headphone/bone-conduction forms. The concept encompasses smartwatches/bracelets, smart rings, patches, belts, footwear, garment-embedded modules, spacesuit (IVA/EVA) inner linings, and any other body-contact form factors. Furthermore, directional tactile stimulus mechanisms are not restricted to Eccentric Rotating Mass (ERM) or Linear Resonant Actuators (LRA), but encompass localized differential pressure, electrical stimulation, micro-temperature shifts, piezoelectric haptics, and all human sensation-based directional perception mechanisms, claiming prior art reservation under this framework.
* **Higher Architecture & Hardware Integration:** The zero-point anchor calibration, 100ms self-healing mesh, and Tri-State isolation controls of LAST-LIGHT serve as lower-tier implementations of the universal survival architecture from `ARCHITECTURE_STRATEGY v3.2.4` and the T-Reg suppression/localized isolation logic of `chiplet-apu-multi-system-survival-architecture v2.6`. The raceway/fire cabinet clamping mounts represent infrastructure implementations of CWP mechanisms, while the 100ms isolation life-extension logic shares the core survival philosophy of `MAX-LIFE ICE-BELT v1.6`.

### 0.3 Zero-Downtime & Non-Contact Principle
This structural design strictly prohibits electrical or physical modification of existing statutory fire, safety, or space module infrastructure. It prioritizes organic zero-downtime fail-over capability, ensuring the overall system continues operating even if individual modules are destroyed by impact or fire. Each module maintains independent multi-mesh connections to mitigate single points of failure (SPOF), allowing adjacent modules to assume computation and blackbox telemetry recording.

### 0.4 Non-Exclusive Interoperability & Open Public Standard
This design is not proprietary to specific optical cameras, vision sensors, microphone arrays, LiDARs, mobile devices, Co-Survival Bridges, spacesuit HMD/haptic transducers, or robotic vision frameworks. It operates as an open public standard capable of utilizing ISO 7010 public always-on signs, fire cabinet indicator lights (internal/external), acoustic signaling devices, BLE Auracast transmitters, and raceway optical/acoustic/RF anchors as auxiliary reference points.

### 0.5 Operational Priority Rule
When information processing overloads occur during emergencies, absolute reference point (ANCHOR) identification, position calibration computation, and blackbox telemetry logging take top priority, while secondary tasks like high-definition image reconstruction or auxiliary graphics generation are incrementally suppressed to maintain continuous guidance positioning.

### 0.6 Universal Application Scope
This structural design applies broadly to smartphone evacuation apps, Co-Survival Bridges, bracelet/ring/garment haptic receivers, spacesuit (IVA/EVA) embedded haptic guidance pads, distributed blackbox forensic modules, autonomous logistics and orbital exploration robot emergency repositioning modules, smart emergency lighting/acoustic anchors in buildings and space station modules, fire cabinet internal/external indicator lights and acoustic anchors, underground parking/spacecraft raceway anchors, disaster rescue AR glasses, and firefighter/astronaut NVG and bone-conduction equipment.

### 0.7 Disclosure Purpose & Limitation Notice
This document discloses the conceptual framework as a defensive publication (Prior Art). Functional, structural, and performance descriptions herein are illustrative and do not restrict or guarantee specific implementations. This system does not replace, alter, or extend statutory fire safety equipment functions, duties, or performance requirements, functioning strictly for auxiliary and reference purposes.

### 0.8 Acknowledgement of Independent Prior Research
While this structural design was independently formulated and established by the inventor, it does not exclude the possibility that similar concepts were conceived independently by other researchers or institutions. The purpose of this specification is not to claim exclusive monopolistic rights, but to record intuitive designs and system integration directions as public prior art, preventing private monopolization and enabling free reference for public safety implementations.

---

## 1. Version History

* **v1.0 (2026-07-30):** Initial visual anchoring concept formulation.
* **v2.0 ~ v3.0 (2026-08-30):** Full-stack applied architecture design, raceway dual IR/visible spectrum integration, edge AI lightweight models, and self-healing multi-mesh failover mechanisms.
* **v3.1 ~ v3.6 (2026-08-30):** Independent research acknowledgement clause (0.8), AI transparency disclosure (Appendix C), emergency power scope (3.C), sensor fusion master reference (0.2), fire cabinet anchors (3.A), and spatial audio/bone-conduction specifications (3.A, 3.B) integrated.
* **v3.7 (2026-08-31):** Personal wearable integration (3.E), routine privacy isolation, 3-second onboarding (3.F), and multisensory anchor evacuation architecture (3.G) fully integrated.
* **v3.8 (2026-08-31):** Initial establishment of 'Co-Survival Haptic Receiver' nomenclature to overcome 100dB siren noise, public infrastructure deployment model, and standard haptic compass protocol table (3.E) integrated.
* **v3.9 (2026-09-01):** Distributed heat-resistant local blackbox telemetry (3.H) inside fire cabinet fireproof chambers and log-based self-evolving AI route computation integrated.
* **v4.0 (2026-09-06):** Cross-reference alignment with `ARCHITECTURE_STRATEGY v3.2.4`, `chiplet-apu v2.6`, `MAX-LIFE ICE-BELT v1.6`, and CWP hardware mechanisms.
* **v4.1 (2026-09-06):** Space station orbital module, zero-gravity smoke diffusion evacuation, IVA/EVA spacesuit haptic integration, and form-factor agnostic stimulus expansion patches applied.
* **v4.2 (2026-09-07):** **[Nomenclature Redefinition]** Officially redefined 'Co-Survival Haptic Receiver' to 'Co-Survival Bridge' to encompass broader form factors and core philosophical purpose. **[Technical/Legal Specification Refinement]** Explicit subsystem timescale separation (0.1s communication vs 0.1ms hardware APU E-Stop), professional patent attorney consultation recommendation clause added. **[Document Unification]** Standardized document headers, unified dual-track version histories, and refined defensive legal phrasing.

---

## 2. 3-Tier Applied Architecture

* **[L2] Auxiliary Guidance & Specialized UI Layer**
  * General Evacuees/Crew: Green visible light, spatial audio, Co-Survival Bridge (earphone/bracelet/ring/garment)/spacesuit haptic directional cues, AR/voice evacuation assistance.
  * Firefighters/Rescuers/EVA Crew: IR/NVG high-contrast visuals, specialized tactile/directional acoustic cues, backend telemetry transmission.
  * Command & Forensics: Blackbox data recovery for post-disaster analysis and bottleneck reporting across building/orbital modules.
* **[L1] Perception & Estimation Fabric Layer**
  * Visible/IR multispectral and microphone array direction-of-arrival (DOA) feature extraction, BLE Auracast/UWB reception.
  * Estimation Algorithms: Extended Kalman Filter (EKF), acoustic Doppler/phase shift probability models, IMU/Gyroscope/LiDAR sensor fusion engine.
  * AI state estimator, distributed self-healing mesh communication, confidence validation unit, ring-buffer blackbox logger.
* **[L0] Infrastructure & Optical/Acoustic/RF Layer**
  * ISO 7010 exit signs, indoor fire cabinet / manual call point / orbital module internal and external indicator lights (Red/LED).
  * Fire cabinet and space module internal fireproof chamber-mounted heat-resistant non-volatile flash memory (Blackbox Module).
  * Directional speakers / acoustic anchors, underground parking / spacecraft raceway / cable tray multi-wavelength optical, acoustic, and BLE Auracast/UWB modules.
  * Passive QR tags, emergency power interface / independent power units, non-contact optical/acoustic/RF sensing interfaces.

---

## 2.5 AI Governance & Model Architecture

* **Abstract AI Engine Definition (Anti-Bypass & Scope Expansion):**
  The AI processing unit is not restricted to specific model parameter sizes, neural network topologies, or chipset architectures. It is defined as an abstract cognitive/estimation entity encompassing on-device edge AI, lightweight models, server/cloud/satellite-linked large models (LLM/VLM/Audio AI), multispectral vision/audio processing networks (CNN/Transformer/Audio Spectrogram Transformer), and hybrid configurations.
* **Lightweight Specialized Model (sLLM / Small Vision-Audio Model / Edge AI) Justification:**
  Disaster environments present power cutoffs, central server destruction, and total communication blackouts. Furthermore, AR headsets, Co-Survival Bridges, and spacesuit modules operate under strict power and compute constraints. Accordingly, on-device lightweight specialized models (sLLM, Small Vision/Audio Models, NPU firmware AI engines) optimized for ultra-low power and latency serve as primary implementation embodiments.
* **Core AI Estimation & Governance Roles:**
  * Multispectral Visual, Spatial Acoustic, and RF Perception: Asynchronously isolates ISO pictograms, fire cabinet lights, raceway IR emitters, acoustic anchors, and BLE Auracast/UWB signals despite dense smoke, noise, glare, or microgravity smoke dispersion.
  * Dynamic Offset Compensation: Real-time zero-point calibration combining IMU/Gyroscope cumulative drift error matrices with ANCHOR spatio-temporal gaps via EKF and DOA calculations.
  * Confidence Control & Signal Generation: Suppresses hallucinated guidance when confidence drops below thresholds, independently generating distinct signals for evacuees (visible light/spatial audio/haptic pulses) and rescuers (IR/NVG/specialized vibration).
  * Blackbox Log Data Feedback: Feeds recovered blackbox logs back into AI training datasets to analyze human/crew behavior patterns and bottleneck zones, dynamically updating real-time rerouting algorithms.

---

## 3. Core System Blocks and Mechanisms

### A. ANCHOR Signage, Fire Cabinet Inner/Outer Terminal Boxes, Acoustic/RF Anchors, and Raceway Sensing Units
* Treats ISO 7010 signs, fire cabinet indicator lights, internal modules, and ceiling/wall raceway optical/acoustic/BLE Auracast/UWB modules as absolute reference points (ANCHORs).
* Enables multisensory zero-point position calibration via spatial audio, frequency-modulated signals, and BLE/UWB emergency broadcasts under complete zero-visibility and microgravity smoke diffusion.
* Controls multi-channel signals providing NVG visual cues, tactile vibration, and specialized frequency data for firefighters, rescuers, and astronauts.
* Collects optical, acoustic, and RF features non-invasively without physical or electrical modification of existing statutory infrastructure.
* **General Lighting Fixture-Based Raceway Path Alignment:** Raceway anchoring targets standard general-purpose lighting fixtures (surface-mounted, linear/strip LED lights) widely deployed in office, commercial, public, and industrial facilities rather than specialized interior lighting. While raceways are originally installed for cable protection and wiring routes, standard lighting fixtures are fixed along these routes, and lighting is conventionally arranged along pedestrian corridors in electrical engineering practices. Following this practical workflow, raceway paths tend to significantly overlap with evacuation routes, forming a generic prior art scope not restricted to exceptional building layouts.
* **Overhead Position Visibility & Crowd Line-of-Sight Obstruction Mitigation:** The physical high-elevation placement of raceways along ceilings and upper walls provides optical and RF signal transmission advantages that overcome eye-level visual occlusions caused by dense evacuee crowds and physical obstacles. This contributes to maintaining anchor visibility and calibration signal reception even within dense crowds or partially obstructed visual fields.

### B. ESTIMATION Offset Calibration & Multisensory Auxiliary Guidance Unit
* Feature Extraction: Extracts image corner features, microphone array acoustic phase delays / Direction of Arrival (DOA), and BLE/UWB RF signal strengths.
* Calibration & Estimation Algorithms:
  * Input: Relative motion vectors from Gyroscopes, IMUs, microphone arrays, acoustic sensors, RF receivers, and LiDAR, alongside relative distance, angle, phase, and RF observations from ANCHOR features.
  * Processing: AI state estimator, Extended Kalman Filter (EKF), acoustic triangulation, and Doppler compensation continuously calibrate sensor drift matrices against absolute reference points.
  * Output: 3D spatial coordinates and visual/auditory/haptic directional prompts (including intuitive left/right haptic compass vibration pulses).
* Confidence Control: Automatically halts guidance if perception confidence falls below established safety thresholds.

### C. Emergency Power Interface & Operating Hours Specification
* Emergency Power Requirement: Interfaces with building/spacecraft emergency power grids or incorporates independent backup power units (batteries, supercapacitors, energy harvesters).
* Power Architecture Inclusivity: Encompasses lithium-based, LFP, solid-state, supercapacitor, energy harvesting, and hybrid energy storage systems.
* Operating Duration Range: Covers initial evacuation windows (<2 hours), rescue entry/evacuation windows (2–4 hours), and extended operation windows (6, 12, 24+ hours).

### D. Organic Distributed Mesh & Zero-Downtime Fail-Over Mechanism
* Independent Multi-Mesh: Modules form independent P2P and N-Mesh connection fabrics without relying on single communication trunks.
* Dynamic Self-Healing: Isolates destroyed modules within 100ms, establishing alternative P2P communication, computation, acoustic, and RF broadcast pathways across adjacent active modules.
* Zero-Downtime Fail-Over: Seamlessly transfers calibration, emission, broadcast, guidance, and blackbox telemetry logging tasks from compromised units to adjacent functional modules.

### E. Co-Survival Bridge — Sensory Isolation Mitigation, Public Deployment, and Anti-Theft Design
Recognizing that voice guidance loses efficacy under dense smoke darkness and siren noise exceeding 100dB, and considering that humans under panic rely on instinctive sensory responses over rational processing, a tactile safety augmentation mechanism is adopted to convey intuitive direction through bone and skin.

While initially referred to as a 'Receiver' during early design phases, that term failed to capture the structural scope required to encompass diverse form factors—including earphones, bracelets, rings, footwear, adhesive patches, garment integration, and spacesuit (IVA/EVA) inner linings across terrestrial and orbital environments. Conceived from the outset to bridge humans with safety networks in isolated environments, this hardware is defined as the 'Co-Survival Bridge'. This nomenclature represents the formalization of its original design philosophy rather than an arbitrary retroactive label.

To suppress private misappropriation and theft risks associated with consumer electronics, auxiliary consumer features such as music playback are excluded, establishing a single-purpose survival tool dedicated exclusively to receiving emergency haptic signals during sensory blackouts. This structural constraint reduces everyday utility, mitigating loss and theft rates during public deployment.

* **Standard Haptic Compass Protocol:**
  * Turn Left: Left temple/bracelet/ring/spacesuit transducer taps twice (100ms ON / 100ms OFF / 100ms ON).
  * Turn Right: Right temple/bracelet/ring/spacesuit transducer taps twice (100ms ON / 100ms OFF / 100ms ON).
  * Move Forward: Dual transducers pulse simultaneously (400ms Continuous Pulse).
  * Stop / Hazard: Dual transducers vibrate continuously (1200ms Long Vibration).
  * Anchor Reached / Calibrated: Dual transducers pulse rapidly 3 times (50ms ON / 50ms OFF, 3 Cycles).

Wearers perceiving direction via haptic cues assume the role of evacuation guide hubs, assisting nearby vulnerable individuals without requiring verbal instruction—functioning as a field-integrated collaborative mechanism that collectively enhances crowd survival rates under extreme crisis.

### F. Rapid Onboarding & Privacy Isolation Specification
* Routine Privacy Isolation: During normal operations, L0 ANCHOR Auracast/RF features remain OFF (transmitting ultra-low-power beacons for <0.1s per minute), isolating connections from personal devices and Co-Survival Bridges to prevent tracking and conserve power.
* Emergency Activation & 3-Second Onboarding: Upon emergency detection, RF broadcasts switch to active ON. Scanning passive QR tags on emergency signage or fire cabinets triggers a `last-light://{anchor_id}?b={broadcast_id}&k={public_temp_key}` deep-link, completing onboarding within 3 seconds.
* Automatic Search on Zero-Visibility: If smoke obscures QR tags, devices and bridges automatically search and join active RF broadcasts from the two strongest adjacent ANCHORs.
* QR Installation Rule: Passive, unpowered tags containing no personal data are positioned without obscuring mandatory statutory sign faces.

### G. Multisensory Anchor Evacuation Architecture
* Environmental Context: Designed for zero-visibility fire environments, including underground parking garages, subterranean commercial complexes, and space station modules.
* Co-Survival Leadership: Wearers receiving haptic signals via Co-Survival Bridges guide disoriented evacuees toward safety.
* Multi-Anchor Fusion: Integrates green ISO 7010 exit signs and red fire cabinet indicator lights as visual benchmarks alongside acoustic and RF signals broadcast from ceiling raceway nodes.

### H. Distributed Heat-Resistant Local Blackbox Telemetry
* Distributed Heat-Resistant Blackbox Architecture: Equips L0 ANCHORs (inside fire cabinet fireproof chambers or space module enclosures) with heat-resistant non-volatile memory, recording positional calibration logs, RF transmission history, and failure timelines in a ring buffer covering recent N hours (1–2 hours) during communications blackouts.
* Forensics & Responsibility Determination: Preserves telemetry within fireproof enclosures during structural collapses or space module depressurization, allowing post-disaster recovery to reconstruct evacuation trajectories and verify system operation.
* Log Feedback & AI Self-Evolution: Feeds recovered logs back into AI training pipelines to analyze movement bottlenecks and smoke propagation patterns, optimizing dynamic rerouting algorithms.

---

## 4. Dynamic Resource Management & Defensive Safety Control

* **Dynamic Visual/Acoustic/RF Rate Limiting:** Throttles frame rates, audio packets, and RF sampling frequencies to prevent processor overload.
* **Asynchronous Random Sampling Scan:** Randomly samples acoustic, optical, and RF inputs to isolate glare, smoke noise, and spoofed packets into isolated buffers.
* **Unauthorized Signal Interception:** Halts calibration pipeline entry immediately upon detecting counterfeit lighting, spoofed audio, or unauthorized RF packets.
* **Auxiliary Resource Suppression (T-Reg Suppressor):** Hardware-throttles computation cycles whenever system power or thermal limits exceed thresholds.
* **Tri-State Physical & Logical Isolation:** Shifts control lines to high-impedance (High-Z) states within 0.1s upon internal error detection, preventing interference with statutory equipment. *(Note: The 0.1s / 100ms Tri-State network isolation response operates independently from the 0.1ms / 100µs hardware APU actuator E-Stop mechanism).*

---

## 5. Standards & Legal Boundaries

* **Standard Compliance:** References ISO 7010, Bluetooth SIG, UWB specifications, and statutory fire safety standards for illustrative purposes without claiming exclusive reinterpretation.
* **Non-Replacement of Statutory Equipment:** Does not replace, alter, or fulfill statutory obligations of mandatory exit lights, alarm systems, fire cabinet indicators, or emergency broadcasts under fire and building codes.
* **Safety Margin & Physical Limitations:** Acknowledges that extreme smoke, acoustic noise, or RF shielding may delay auxiliary guidance. Final evacuation decisions remain the responsibility of evacuees and official rescue authorities.

---

## 6. Future Application & Industrial Scope

* **Smart Underground Parking & Spacecraft Raceways:** Deploys dual IR/visible, directional acoustic, and BLE/UWB anchors along raceways for autonomous vehicle/rover calibration during normal operations and evacuation guidance during emergencies.
* **3D Positioning Anchors for Fire Cabinets & Space Modules:** Utilizes fire cabinet surfaces and spacecraft internal chambers as zero-point reference nodes for 3D tactile guidance under zero-visibility.
* **Space Station Modules & IVA/EVA Spacesuit Guidance:** Provides auxiliary navigation toward airlocks and escape modules via spacesuit haptics and NVG HMDs during microgravity fires or depressurization.
* **Robotic Navigation in Underground & Orbital Facilities:** Facilitates position correction and survivor search for autonomous logistics and rescue robots in GPS-denied environments.

---

## 7. Practical Protection & Legal Framework

* **Authoritative Original Text Notice:** Legal and technical interpretations of this specification are governed strictly by the Korean original text (`README.ko.md`). English translations serve secondary reference purposes only.
* **Concept Inclusivity:** All high-level concepts—including ANCHORs, ESTIMATION, Co-Survival Bridges (regardless of form factor), Auracast/UWB haptic compasses, Tri-State Isolation, T-Reg Suppressors, distributed blackboxes, and AI self-evolution—are broadly claimed for defensive prior art reservation.
* **Commercialization Separation:** This document contains pure open-source specifications and prior art disclosures. Commercial execution plans and business models are maintained in separate technical documentation.
* **Defensive Publication & DPL v1.0 License:** Serves as prior art against third-party patent claims. Initiating patent litigation against implementers invalidates the litigant's DPL v1.0 license immediately.
* **Prior Use Rights & Trade Secret Bifurcation:** Preserves prior use rights under Article 103 of the Korean Patent Act and 35 U.S.C. §273. Specific feature extraction weights and neural network parameters are maintained as proprietary trade secrets.
* **Professional Legal Counsel Recommendation:** Implementers are advised to consult qualified patent attorneys regarding DPL licensing, prior use defenses, and utility model filing strategies.

---

## 8. Sources & Completeness

* **Linked Survival Architecture:** GitHub - `soma-moa / ARCHITECTURE_STRATEGY.md v3.2.4`
* **Linked APU Controller:** GitHub - `deundeuni / chiplet-apu-multi-system-survival-architecture v2.6`
* **Linked Marine Armor:** GitHub - `soma-moa / MAX-LIFE ICE-BELT v1.6`
* **Linked CWP Repositories:**
  * GitHub - `deundeuni / CWP-Entry`
  * GitHub - `deundeuni / CWP-Rolling-Self-Align-Battery-Swap-System`
  * GitHub - `deundeuni / CWP-Battery-Swap`
  * GitHub - `deundeuni / CWP-Clamping-Battery-Swap-System`
* **Canonical Gateway:** `somamoa.ai.kr`
* **International Standards:** ISO 7010, ISO 16069, Bluetooth SIG Auracast / LE Audio Specifications, UWB Standards, Korean Act on Fire Protection Installation and Management.
* **Legal Precedents & Guidelines:** Korean Patent Act Article 103, 35 U.S.C. §273.
* **Document Completeness:** This specification stands as an independent, self-contained technical publication.

---

## Appendix A: Inventorship
* System Architect & Sole Inventor: deundeuni
* Primary Repository: github.com/soma-moa
* License: CC BY 4.0 (Attribution Required) + DPL v1.0

## Appendix B: Version History
▶ Refer to Section 1 (Version History) of the main body.

---

## Appendix C: AI Assistance Disclosure & Tool Operational Rules
* Original Architecture & Concepts: deundeuni (Human) — Sole Inventor, solely responsible for system architecture, motivation, circuit integration logic, and technical decisions.
* Subordinate Drafting Tool: Meta AI — Used as an auxiliary tool for initial paragraph structuring and visual concept drafting.
* Subordinate Structuring Tool: Gemini — Used as an auxiliary tool for section formatting and terminology standardization.
* Subordinate Review Tool: Claude — Used as an auxiliary tool for conversational context verification and defensive text refinement.
* ※ **Intellectual Property Ownership Declaration:** All core technical architectures, haptic compass algorithms, circuit control logic, and legal defense frameworks are the sole intellectual creation of the human inventor (deundeuni). AI models functioned strictly as auxiliary text editing tools under direct human instruction.

---

## Appendix D: Legal Disclaimer & Responsibility Limitation
* **Auxiliary Status & Non-Replacement:** The technology disclosed herein (LAST-LIGHT v4.2), associated software, QR tags, BLE/UWB communication fabrics, spatial audio anchors, Co-Survival Bridges (across all form factors), and distributed blackboxes do not replace the legal, physical, or functional performance of statutory emergency lights, alarms, or fire cabinet indicators required under fire and building codes. They function strictly as auxiliary/supplementary guidance tools.
* **Limitation of Liability:** The inventor (deundeuni / soma-moa) and ecosystem contributors assume no civil or criminal liability for evacuation delays, communication failures, sensory perception errors, data losses, personal injuries, or property damage resulting from the implementation or use of this specification or open-source code. Evacuation management remains the sole responsibility of facility managers and official authorities.
* **Intellectual Property & Trademark Disclaimer:** References to technical standards (Bluetooth SIG, ISO, etc.) serve illustrative purposes only and imply no endorsement or trademark infringement. All technical expressions herein represent general, non-proprietary engineering concepts.
