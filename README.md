> **Multilingual Notice:** This document is published in dual languages (Korean/English). v4.8 2026-09-09 (Korean version: [README.ko.md](README.ko.md))  
> **Original Authority Notice:** The supreme authority for legal and engineering judgment of this technical specification belongs to the Korean original (`README.ko.md`), and the English version serves as a secondary reference only. (`README.ko.md` is authoritative original)

# LAST-LIGHT — Auxiliary Guidance System Utilizing Multisensory Acoustics, Co-Survival Bridge, and Heterogeneous Multi-Device Distributed Infrastructure
## Subtitle: Defensive Publication White Paper on 0-Point Calibration, Multisensory Haptics, and Blackbox Infrastructure via ISO 7010 Signage, Hydrant Boxes, Smart Raceways, Orbital Modules, and AR Glasses/Smart Ring/Robotics Infrastructure (Ver. 4.8)

* **Official Document Classification:** Defensive Publication / Prior Art White Paper
* **Initial Conception Date:** 2026-07-30 / **Final Revision Date (v4.8):** 2026-09-09
* **Original Intellectual Property (IP) Holder:** soma-moa (Conceiver: deundeuni)
* **Official Repository:** github.com/soma-moa | **Official Domain:** somamoa.ai.kr
* **Applicable Licenses:** CC BY 4.0 & DPL v1.0 (Defensive Patent License)
* **Keywords:** LAST-LIGHT, Evacuation Guidance, Position Calibration, Infrastructure Anchoring, Structure First Principle, ISO 7010, Co-Survival Bridge, Haptic Compass, BLE Auracast, Tri-State Isolation, T-Reg Suppressor, Distributed Local Blackbox, Fire-Rated Hydrant Chamber, Small Cell DAS Integration, Space Station Evacuation, Microgravity Evacuation, Orbital Module Anchor, IVA/EVA Spacesuit Haptics, AR Glasses HUD, Smart Ring, WebAR Quick Release, Visual SLAM Rapid Drift Reset, Prior Art, chiplet-apu, ARCHITECTURE_STRATEGY, CWP, MAX-LIFE ICE-BELT

---

## 0. Conceiver's Declaration and Motivation

### 0.1 Field-Driven Motivation & Co-Survival Philosophy
This structural design originated from an earnest desire: "I hope even one more person can evacuate safely, and that firefighters entering danger as well as responders in extreme disaster environments can return home safely to their waiting families."

In fires and disasters, the site faces extreme sensory deprivation: severe darkness (visual isolation) due to heavy smoke and power outages, coupled with auditory paralysis (auditory isolation) caused by emergency sirens exceeding 100 dB and crowd panic noise. Furthermore, during fires inside zero-gravity/microgravity orbital modules (space stations) and sealed living quarters, the absence of thermal buoyancy prevents smoke from rising, scattering it uniformly in 3D space and causing severe zero-visibility. Traditional voice announcements or visual signs may be significantly degraded in functionality under these conditions.

Addressing this, and aiming to overcome the fundamental limits of position drift or signal loss inherent in existing wireless positioning or simple inertial navigation (IMU) devices within indoor, underground, and space environments, this system conceived an "Infrastructure Anchoring" evacuation guidance mechanism. By establishing permanently installed infrastructure (24/7 illuminated ISO 7010 emergency exit signs, indoor hydrant/fire alarm terminal boxes, ceiling/wall raceways) in buildings and orbital modules as "Visual, Optical, Acoustic, and Wireless RF Absolute Reference Points (ANCHOR)," it real-time calibrates spatial position to 0.

Through this framework, the system guides general evacuees via intuitive tactile direction delivered through bones and skin via personal or spacesuit-embedded "Co-Survival Bridges," AR glasses 3D HUDs, and smart rings without relying on sound, sight, or language barriers. Simultaneously, by embedding a "Distributed Heat-Resistant Local Blackbox" in hydrant boxes and module fire-rated compartments to store recent evacuation trajectories in a ring buffer, a self-evolving AI framework for post-disaster root-cause analysis and data-driven evacuation route optimization was completed.

Moreover, by adopting the solidarity philosophy of "Co-Survival"—where a wearer who gains directional certainty through intuitive tactile stimuli naturally leads surrounding panicked individuals—as a core structural axis, this technology is designed to operate as an auxiliary safety framework supporting human respect for life and cooperative instincts during crises.

### 0.2 Master Concept & Sensor Fusion Standard
The visual, optical, acoustic, and RF ANCHOR-based 0-point calibration and correction mechanism disclosed in this specification functions as the Master Reference Framework for the entire positioning and auxiliary guidance system.
Any extended configurations adding single or complex combinations of Gyroscopes, Accelerometers, Inertial Measurement Units (IMU), Microphone Arrays, Acoustic/Ultrasonic Sensors, Bone Conduction/Tactile Vibration Transducers, BLE Auracast RF Modules, UWB Modules, 5G/6G Small Cell & Distributed Antenna System (DAS) auxiliary signals, Heat-Resistant Blackbox Memory, LiDAR, ToF, Thermal Imaging, Infrared, AR/MR vision cameras, or other positioning/sensor means represent secondary combinations utilizing this 0-point calibration mechanism as a baseline reference, and are included within the comprehensive protection scope of this prior art.

* **Structure First Principle & Master Survival Philosophy Linkage (Structure First & Topological Anchoring):** This system adopts the topological alignment of existing physical structures (pictograms, hydrant boxes, raceways, etc.) as its primary design principle, rather than prioritizing sensor placement. All sensors function as subordinate auxiliary tools to this structure. This 'Structure First' principle embodies the same design philosophy as the 'Structure over Capacity' principle in Section 0.2 of the master survival architecture `chiplet-apu`, materializing it as a spatial/topological anchoring method for disaster evacuation environments.
* **Infrastructure Anchoring Override:** To structurally mitigate cumulative position drift and communication shadow limitations of devices relying solely on inertial navigation or external wireless signals in indoor, underground, and space environments, this system declares the calibration mechanism utilizing statutory fixed infrastructure signs and modules as absolute 0-point anchors (L0 Anchor) as its core differentiator and primary scope.
* **Non-Obvious Fire-Rated Infrastructure Selection:** The L0 anchor media of this system—such as indoor hydrant boxes and fire alarm terminal boxes—are non-combustible and fire-rated facilities required by relevant fire safety regulations (e.g., National Fire Performance Codes / NFPC) to maintain physical and structural integrity during fires. Grounded in the legal and physical assurance of survival during disasters (unlike standard commercial beacons or decorative interior markers), this system purposefully integrates fire-rated hydrant boxes and compartments as absolute 0-point anchors and local blackbox receptacles, establishing non-obvious distinctiveness over conventional beacon placement methods.
* **Subordinate Telecom Infrastructure & Offline-First Hierarchy:** When 5G/6G small cells or Distributed Antenna Systems (DAS) are deployed in underground or tunnel environments, this system may additionally utilize them as auxiliary position fusion signals and management backhaul paths. However, assuming communication blackouts during disasters, the absolute reference points (ANCHOR) of this system maintain a strict primary hierarchy anchored to fixed infrastructure (ISO 7010 signs, hydrant boxes, raceways) independent of wireless network availability, establishing a master-subordinate relationship where telecom infrastructure functions strictly as a supplementary option.
* **Form-Factor & Stimulus Agnostic Rule:** The wearable receiver of this guidance system is not limited to earphones, headphones, or bone conduction devices. It comprehensively encompasses smartwatches, wristbands, smart rings, AR/MR smart glasses and HUDs, patches, haptic vests, smart shoes/insoles, clothing-embedded modules, spacesuit (IVA/EVA) inner linings, autonomous relief robot (AMR)/drone vision modules, and all other human/machine contact forms. Furthermore, the tactile stimulus mechanism delivering direction is not restricted to Eccentric Rotating Mass (ERM) or Linear Resonant Actuators (LRA); it encompasses local pressure differentials, electrical stimulation, micro-temperature shifts, piezoelectric haptics, and all meaningful drive methods allowing intuitive perception of direction, preempting them under this prior art baseline reference.
* **Master Architecture & Interconnected Hardware System Linkage:** The 0-point anchor calibration, 100ms self-healing mesh, and Tri-State isolation control of LAST-LIGHT constitute a domain application implementation of the bypass and local isolation logic of the master fault-tolerant survival architecture `chiplet-apu-multi-system-survival-architecture` and its subordinate strategy `ARCHITECTURE_STRATEGY` adapted to disaster evacuation environments. The raceway/hydrant box clamping attachment represents an infrastructure implementation of CWP's four hardware mechanisms, while the 100ms isolation lifespan extension algorithm shares the same survival control philosophy as `MAX-LIFE ICE-BELT`.

### 0.3 Zero-Downtime & Non-Contact Principle
This structural design strictly prohibits physical or electrical modification of existing statutory fire, safety, or space module infrastructure. It prioritizes organic zero-downtime fail-over capacity, aiming to ensure the entire system does not halt even if individual modules are destroyed by impact or fire. Each module maintains an independent multi-mesh state to mitigate single points of failure (SPOF), allowing adjacent modules to immediately assume computation and blackbox self-logging.

### 0.4 Non-Exclusive Interoperability & Open Public Standard
This structural design is not proprietary to specific optical cameras, vision sensors, microphone sensors, LiDAR, mobile devices, Co-Survival Bridges, AR glasses, smart rings, spacesuit HMD/haptic transducers, or robot vision frameworks. It operates as an Open Public Standard capable of referencing public-domain 24/7 illuminated visual standard signs such as ISO 7010 series, hydrant location indicators (internal/external), acoustic beacons, BLE Auracast transmitters, and raceway optical/acoustic/RF anchors as auxiliary references.

### 0.5 Operational Priority Principle
In the event of information processing overload during emergencies, absolute reference point (ANCHOR) identification, position calibration computations, and core blackbox telemetry logging are assigned top priority. Secondary tasks such as high-definition visual reconstruction or supplementary graphics generation are suppressed in stages to maintain continuous auxiliary position estimation.

### 0.6 Universal Application Scope
This structural design comprehensively applies to smartphone evacuation applications, Co-Survival Bridges, AR/MR smart glasses Visual HUD navigation, smart rings, wristband/ring/apparel/vest/insole wearable haptic receivers, spacesuit (IVA/EVA) embedded haptic evacuation pads, distributed blackbox data forensics modules, autonomous relief robots (AMR) and orbital exploration robot emergency re-calibration modules, smart emergency lighting/acoustic anchors in buildings and space station modules, hydrant internal/external position indicators and acoustic anchors, underground parking/spacecraft raceway anchors, underground telecom small cell/DAS auxiliary integration modules, disaster rescue AR glasses, firefighter/astronaut NVG/thermal and bone-conduction equipment, and powerless passive QR/ArUco/NFC tag-based WebAR and OS deep-link instant onboarding modules requiring visual, optical, auditory, vibration, or tactile perception-based auxiliary positioning.

### 0.7 Disclosure Purpose & Limitation Notice
This document is published as a Defensive Publication / Prior Art disclosure. Functions, configurations, and performance descriptions herein are exemplary and do not limit or guarantee specific implementations. This system does not replace, alter, or extend the functions, performance, or statutory duties of existing legal fire safety equipment, operating strictly for auxiliary and reference purposes.

### 0.8 Acknowledgement of Independent Prior Research
This structural design was independently conceived and established by the author. However, the possibility that similar ideas were independently formulated by other researchers, inventors, or institutions is not excluded. The purpose of this technical specification is not to claim exclusive proprietary rights, but to record intuitive concepts and system combination directions as public prior art to prevent private monopolization by specific entities, leaving it open for anyone to freely reference for technological development and life safety implementation.

---

## 1. Version History

* **v1.0 (2026-07-30):** Initial visual anchoring concept drafted.
* **v2.0 ~ v3.0 (2026-08-30):** Full-stack applied architecture designed; dual-wavelength raceway IR/visible light, lightweight AI models, and self-healing multi-mesh fail-over structures integrated.
* **v3.1 ~ v3.6 (2026-08-30):** Independent prior research acknowledgement clause (0.8), AI transparency disclosure (Appendix C), emergency power scope (3.C), sensor fusion baseline (0.2), hydrant box anchors (3.A), and directional acoustic/bone conduction specs (3.A, 3.B) integrated.
* **v3.7 (2026-08-31):** Personal wearable integration (3.E), idle isolation and emergency onboarding (3.F), and multisensory anchor evacuation auxiliary structure specs (3.G) fully integrated.
* **v3.8 (2026-08-31):** Renamed device to "Co-Survival Vibration Receiver" to overcome 100 dB emergency siren noise; public infrastructure deployment structure and standard tactile haptic compass protocol table (3.E) integrated.
* **v3.9 (2026-09-01):** Hydrant box fire-rated module "Distributed Heat-Resistant Local Blackbox Telemetry (3.H)" and log-recovery-based evacuation self-evolving AI learning mechanism integrated.
* **v4.0 (2026-09-06):** Master chiplet survival architecture (`chiplet-apu v2.6.1`), subordinate strategy (`ARCHITECTURE_STRATEGY`), marine armor (`MAX-LIFE ICE-BELT v1.6`), and CWP hardware mechanisms cross-reference patch applied.
* **v4.1 (2026-09-06):** Space station orbital module, microgravity smoke diffusion evacuation, IVA/EVA spacesuit haptic compass linkage, and wearable form-factor/directional stimulus abstract rule patch applied.
* **v4.2 (2026-09-07):** Nomenclature refined ("Co-Survival Bridge"); 2-tier title structured; communication path terms corrected in 3.D; privacy specs unified in 3.E/3.F; master hierarchy and sensor fusion closure consolidated.
* **v4.3 ~ v4.7 (2026-09-09):** Extended to heterogeneous multi-devices, SLAM timescale refined, underground telecom (small cell/DAS) auxiliary integration and offline-first hierarchy established, fire-rated infrastructure non-obviousness logic applied, and regulatory grounds separated via cross-references.
* **v4.8 (2026-09-09):** **[Specification of 'Structure First' Principle & chiplet-apu Sec 0.2 Cross-Reference]** Explicitly declared the spatial/topological 'Structure First' design principle in Section 0.2, which prioritizes existing physical structures (pictograms, hydrant boxes, raceways, etc.) over sensor placement. Reflected the cross-reference to the 'Structure over Capacity' philosophy of the master survival architecture `chiplet-apu` Section 0.2. Standardized Appendix C AI disclosures into a generalized AI tools framework without specific corporate brand names.

---

## 2. 3-Tier Applied Architecture

* **[L2] Auxiliary Guidance & Specialized UI Layer**
  * For General Evacuees / Crew: Green visible light, spatial audio, AR/MR glasses Visual HUD 3D guide lines, Co-Survival Bridge (earphones/wristbands/rings/etc.), smart rings, personal smartwatch/band, haptic vest/insole, spacesuit-embedded haptic left/right directional guidance, WebAR/voice evacuation assistance.
  * For Firefighters / Rescuers / EVA Crew: IR/NVG/Thermal high-contrast visual cues, rescuer-dedicated tactile/directional acoustic guidance, backend telemetry transmission.
  * For Unmanned Robotics / AMR / Drones: Visual SLAM/LiDAR 0-point position error reset fabric, survivor tracking telemetry.
  * For Control & Forensics: Post-disaster blackbox data recovery and building/orbital module bottleneck report generation.
* **[L1] Perception & Estimation Fabric Layer**
  * Visible/IR multispectral, AR vision, microphone array direction-of-arrival (DOA) feature extraction, BLE Auracast/UWB reception, 5G/6G small cell & DAS auxiliary signal fusion.
  * Calibration and estimation algorithms (Kalman filter, acoustic Doppler/phase-difference probability models, Visual SLAM Drift Reset), IMU/Gyroscope/LiDAR sensor fusion engine.
  * AI state estimator, heterogeneous device Graceful Fallback controller, distributed self-healing mesh communication unit, confidence verification unit, ring-buffer blackbox self-logging unit.
* **[L0] Infrastructure & Optical/Acoustic/RF Layer**
  * ISO 7010 exit signs, indoor hydrant/fire alarm/space module internal/external location indicators (Red LED).
  * Hydrant box and space module fire-rated internal chamber heat-resistant non-volatile flash memory (Blackbox module).
  * Directional speaker/acoustic anchors, underground parking/spacecraft raceway multi-wavelength emitter, acoustic, and BLE Auracast/UWB modules.
  * Underground/tunnel 5G/6G small cell and Distributed Antenna System (DAS) auxiliary RF reception/backhaul module.
  * Passive powerless QR/ArUco/NFC tags, emergency power linkage / independent power units, non-contact optical/acoustic/RF sensing receivers.

---

## 2.5 AI Governance & Model Architecture

* **Abstract Comprehensive AI Engine Definition:**
  The AI computation unit of this system is not restricted to specific model sizes, neural network topologies, parameter counts, or chipset form factors. It is defined as an abstract perception/estimation entity encompassing on-device edge AI, lightweight models, server/cloud/satellite-linked large artificial intelligence models (LLM/VLM/Audio AI), multispectral vision and acoustic signal processing networks (CNN/Transformer/Audio Spectrogram Transformer), and hybrid interconnected forms thereof.
* **Justification for Lightweight Edge Models (sLLM / Small Vision-Audio Model / Edge AI):**
  Disaster sites presuppose power outages, main server destruction, and total communication blackout. Furthermore, power and compute resources on AR glasses, Co-Survival Bridges, smart rings, smartwatches, and spacesuit modules are severely constrained. Accordingly, on-device lightweight models (sLLM, Small Vision/Audio Models, NPU firmware AI engines) optimized for ultra-low power and ultra-low latency execution are presented as core implementation embodiments.
* **Core AI Estimation & Governance Roles:**
  * Multispectral Visual, AR Vision, and Spatial Acoustic/RF Perception: Asynchronously isolates and perceives ISO pictograms, hydrant indicators, raceway IR emitters, acoustic anchors, BLE Auracast/UWB, and small cell signals despite fire smoke, noise, glare, or microgravity smoke dispersion.
  * Dynamic Error Calibration & SLAM Reset: Combines IMU/Gyroscope cumulative drift errors and ANCHOR/passive tag geometric specifications with Kalman filtering and Visual SLAM computations to calibrate position to 0 in real time.
  * Multi-Device Graceful Fallback Control: Autonomously transfers output control between AR HUD visual guidance and tactile haptic/spatial audio based on fluctuations in smoke or noise density, actively suppressing hallucinated guidance upon confidence drops.
  * Data Feedback via Blackbox Logs: Feeds recovered blackbox logs back into AI training datasets to refine real-time rerouting algorithms by reflecting actual human/crew behavior patterns and facility bottlenecks.

---

## 3. Core System Blocks and Operational Mechanisms

### A. ANCHOR Signage, Hydrant/Terminal Boxes, Acoustic/RF Anchors, and Raceway Sensing (Infrastructure Domain)
* Considers ISO 7010 exit signs, hydrant/control panel location indicators, internal box modules, and ceiling/wall raceway optical/acoustic/BLE Auracast/UWB modules as absolute reference points (ANCHOR).
* Indoor hydrant boxes serve as fire-rated facilities under relevant fire safety regulations (see Section 0.2), operating as fixed anchors with guaranteed physical survival during fires unlike standard commercial markers or arbitrary beacons.
* Performs multisensory position 0-point calibration under ground fires with severe zero-visibility conditions and microgravity smoke blockades by receiving spatial audio, frequency-modulated signals, and BLE/UWB emergency broadcasts.
* Controls multi-channel reception of NVG/Thermal visual cues, tactile vibration signals, and specialized frequency data for firefighter, rescuer, and astronaut equipment.
* Receives light, geometry, acoustic, and RF features indirectly and without physical or electrical modification to existing infrastructure.
* **Raceway Route Alignment via Standard Lighting Fixtures:** Raceway anchoring targets standard commercial/public/industrial lighting fixtures (surface-mounted lights, linear LED strips) rather than specialized decorative lights. While raceways primarily serve to protect wiring and establish cable paths, standard lighting fixtures are fixed along these routes per electrical design conventions, aligning raceway paths closely with human evacuation routes. This practical alignment forms a broad prior art protection scope independent of specific building layouts.
* **Elevated Line-of-Sight & Crowd Occlusion Mitigation:** The elevated physical positioning of raceways along ceilings and upper walls offers optical and RF signal transmission advantages that overcome eye-level line-of-sight blockages caused by dense evacuating crowds during disasters. This helps maintain anchor signal perception and calibration signal reception visibility even amidst dense, chaotic crowds.

### B. ESTIMATION Calibration/Estimation and Multisensory Auxiliary Guidance Generation (Auxiliary Device Domain)
* Feature Extraction: Separately extracts image corner feature points, AR vision frames, microphone array sound phase differences / arrival delays / Direction of Arrival (DOA), and BLE/UWB/small cell RF signal strength.
* Calibration & Estimation Algorithm:
  * Input: Relative motion vectors from gyroscopes, IMUs, microphone arrays, acoustic sensors, RF receivers, LiDAR, AR cameras, and other complex sensors, combined with ANCHOR, passive tag, and auxiliary telecom signal observations.
  * Process: AI state estimator, Extended Kalman Filter (EKF), Visual SLAM drift reset, and acoustic triangulation/Doppler correction real-time calibrate the cumulative drift error matrix of inertial/gyroscope sensors.
  * Output: 3D spatial coordinates, AR HUD 3D guide lines, and visual/auditory/vibrational directional cues (including intuitive left/right haptic compass vibration pulses).
* Confidence Control: Automatically suspends guidance if perception confidence drops below established thresholds.

### C. Emergency Power & Operating Hours
* Mandatory Emergency Power Linkage: Must link to building and space module emergency power systems or include auxiliary independent power units (batteries, supercapacitors, energy harvesters).
* Power Unit Agnosticism: Encompasses lithium-based, LFP, solid-state, supercapacitor, energy harvesting, and hybrid energy storage systems.
* Operating Duration Scope: Covers initial emergency evacuation periods under 2 hours, minimum rescue window operations of 2–4 hours, and extended continuous operation scopes of 6, 12, or 24+ hours.

### D. Self-Healing Multi-Mesh & Zero-Downtime Fail-Over
* Independent Multi-Mesh: Modules form independent P2P and N-Mesh multi-connection fabrics without relying on single communication lines or paths.
* Dynamic Self-Healing: Upon module destruction, aims to isolate the fault within the 100ms band and autonomously establishes alternate communication, computation, acoustic, and RF broadcast bypass routes among surrounding active modules.
* Zero-Downtime Control Transfer: Calibration, emission, transmission, guidance signals, and blackbox self-logging functions of a failed module seamlessly transfer to adjacent operational modules to support continuous operation.

### E. Co-Survival Bridge — Sensory Isolation Breakthrough, Public Placement, Anti-Theft Design, and Heterogeneous Multi-Device Interoperability & Graceful Fallback
In extreme sensory deprivation environments combining zero-visibility smoke (darkness) with emergency sirens over 100 dB (auditory paralysis), voice prompts and visual displays lose practical utility. Under panic, human instinct overrides rational analysis; thus, a tactile auxiliary mechanism conveying direction intuitively through skin and bones is adopted.

Initially termed a "receiver," this name failed to reflect its broader structural scope—encompassing earphones, wristbands, smart rings, AR glasses, patches, haptic vests, smart shoes/insoles, smart apparel, and spacesuit (IVA/EVA) inner linings. Conceived to reconnect isolated humans to safety networks, the device is officially named the "Co-Survival Bridge." This designation reflects its core design philosophy: aiming to ensure even a single individual can reach a lifeline of survival.

To suppress theft or misuse for personal entertainment, non-essential functions (such as music playback) are excluded. The device is deployed in public infrastructure as a single-purpose emergency auxiliary tool housing only necessary haptic reception components. This functional limitation lowers everyday utility, mitigating theft risks during public placement.

* **Standard Haptic Compass Protocol:**
  * Turn Left: Left temple/wristband/ring/watch/spacesuit left transducer double-tap (Left: 100ms ON / 100ms OFF / 100ms ON)
  * Turn Right: Right temple/wristband/ring/watch/spacesuit right transducer double-tap (Right: 100ms ON / 100ms OFF / 100ms ON)
  * Move Forward: Dual transducers simultaneous medium pulse (Dual: 400ms Continuous Pulse)
  * Stop / Hazard: Dual transducers simultaneous long vibration (Dual: 1200ms Long Vibration)
  * Anchor Reached / Calibrated: Dual transducers short triple-tap (Dual: 50ms ON / 50ms OFF, 3 Cycles)
* **Heterogeneous Multi-Device Interoperability & Graceful Fallback (BYOD):**
  In addition to public Co-Survival Bridges, this system encompasses comprehensive software interoperability with heterogeneous multi-devices worn or operated by evacuees and rescue personnel (AR/MR smart glasses Visual HUD, smart rings, smartwatches/bands, haptic vests/patches/insoles, TWS hearables, autonomous AMR robots). If AR glasses camera visibility is blocked by increasing fire smoke, or auditory perception is paralyzed by a surge in emergency noise, the system's computation layer (L1) autonomously transfers output control from the AR HUD visual guidance to the smart ring/watch/vest tactile haptic compass and spatial audio within 0.1 seconds (Graceful Fallback), aiming to secure uninterrupted evacuation continuity.
* **Privacy Isolation & Activation Mechanism for Personal Devices:**
  When linked with personal smartwatches, smart rings, or AR glasses, data collection and wireless background scanning are separated and suppressed during normal times to protect privacy and battery life. Upon emergency detection, background activation occurs via L0 anchor RF broadcast pulses or emergency alert triggers, providing auxiliary directional haptic guidance through skin contact when sight is severely obscured.

Furthermore, wearers who gain directional certainty through haptic signals naturally act as evacuation guides for surrounding companions without needing complex verbal explanation, establishing a field-level safety support network that collectively elevates crowd survival.

### F. Rapid Onboarding, Contactless QR/NFC Quick Release & Visual SLAM Rapid Drift Reset
* Idle Isolation & Privacy Protection: During normal times, L0 anchor Auracast/RF functions remain OFF (transmitting ultra-low-power beacons for under 0.1s per minute), isolating and disconnecting links with personal devices and Co-Survival Bridges to suppress location tracking, data harvesting, and battery drain.
* Emergency State Switch & 3-Second Onboarding: Upon fire/emergency detection, RF broadcasting switches to active ON. Scanning passive powerless QR/ArUco tags or tapping passive NFC tags attached to exit signs, hydrants, or space modules executes an app-less WebAR and OS deep-link (`last-light://{anchor_id}?b={broadcast_id}&k={public_temp_key}`), joining the channel within 3 seconds.
* Visual SLAM Zero-Point Calibration (Rapid Drift Reset): The moment AR glasses, smartphones, or robot vision frameworks capture the geometric specifications of the L0 anchor's passive QR/ArUco tags, the system precisely calibrates the cumulative spatial drift error matrix of the device's inertial sensors (IMU) to zero in real-time within the next-frame computation cycle or 100ms.
* Automatic Search During Sight Blockade: If smoke or zero-gravity dispersion renders optical tag scanning impossible, terminals, bridges, AR glasses, smart rings, and linked smartwatches automatically search and join the strongest RF broadcast signals from two or more adjacent anchors.
* Tag Installation Principle: Non-powered passive tags containing no personal data are installed without obscuring statutory sign surfaces.

### G. Multisensory Anchor-Based Evacuation Structural Concept Specification
* Field Context: Presupposes extreme disaster environments such as underground parking garages, subterranean malls, or space station modules where fire smoke severely restricts visibility.
* Co-Survival Leadership Execution: An evacuee wearing a Co-Survival Bridge, AR glasses, smart ring, or linked smartwatch receives RF haptic vibration signals and visual HUD data, directly assisting disoriented companions toward safety.
* Multi-Anchor Composite Visualization: ISO 7010 green exit signs and red hydrant indicators serve as absolute visual references on walls, while ceiling raceway/tray acoustic and RF modules project wireless broadcast signals through space in an organically unified layout.

### H. Distributed Heat-Resistant Local Blackbox Telemetry
* Physical Survival Assurance via Fire-Rated/Impact-Resistant Compartments: Physical and regulatory survival grounds for L0 blackbox memory receptacles in ground hydrant boxes (domestic NFPC, etc.) and space module chambers (spacecraft structural safety standards, etc.) reference Sections 0.2 and 3.A, housed within protected fire-rated structures.
* Distributed Heat-Resistant Local Blackbox Structure: L0 anchors contain heat-resistant non-volatile flash memory within fire-rated internal chambers, recording recent N hours (1–2 hours) of [position 0-point calibration logs, RF transmission logs, module failure/fail-over timelines] in a ring buffer during communication blackouts.
* Forensics & Liability Mitigation: Allows recovery of blackbox chips from surviving hydrant boxes or module chambers following server destruction or structural collapse to objectively reconstruct evacuation paths and verify system performance.
* Data Feedback & Self-Evolution: Feeds recovered blackbox datasets into AI training pipelines to analyze movement bottlenecks and smoke spread patterns, dynamically enhancing real-time rerouting algorithms.
* **Master Sensor Fusion Closure:** All individual sensor and control blocks mentioned in Section 3—including optical, vision, AR vision, microphone arrays, IMU, Gyroscope, BLE Auracast, UWB, small cell/DAS, haptics, and fire-rated blackbox memory—operate as secondary, expanded driving combinations of the Master Sensor Fusion Framework defined in Section 0.2. All system configurations combining these elements relative to the 0-point calibration mechanism fall fully within the overarching scope of this prior art.

---

## 4. Dynamic Resource Management & Defensive Safety Control

* **Dynamic Rate Limiter:** Throttles visual frames, acoustic packets, and RF sampling rates to help prevent processor overload.
* **Random Sampling Scan:** Asynchronously samples acoustic, light, and RF environments to isolate glare, smoke, noise, and spoofed packets into isolated buffers.
* **Relocation Interception:** Immediately halts calibration procedures upon detecting counterfeit lighting, spoofed audio, or unauthorized RF packets.
* **T-Reg Suppressor:** Hardware-suppresses computation cycles when system power or compute resource usage exceeds established thresholds.
* **Tri-State Physical & Logical Isolation:** Converts control lines to a high-impedance (High-Z) state within 0.1s upon internal computation errors, physically and logically suppressing interference with statutory safety equipment. (Note: The 0.1s / 100ms response speed of this network-layer Tri-State isolation represents a subsystem control layer distinct from the 0.1ms / 100µs real-time actuator/motor E-stop speed defined in the master `chiplet-apu` controller).

---

## 5. Standard Utilization & Legal Boundaries

* **Standard Compliance:** Cites ISO 7010, Bluetooth SIG, UWB, 3GPP Small Cell Specs, national fire codes, National Fire Performance Codes (NFPC), and infrared/visible light/acoustic standards as illustrative public references without claiming exclusive re-interpretation.
* **Non-Substitutability for Statutory Equipment:** Operates purely as an auxiliary reference system and does not replace the legal duties, performance, or installation standards of emergency exit lights, alarm systems, hydrant indicators, or public address systems mandated by fire, building, or space safety codes.
* **Safety Margin & Physical Limitations:** Auxiliary functions may delay or halt under extreme smoke, noise, or RF shielding. Final evacuation decisions remain the responsibility of legal safety facilities and human rescue personnel.

---

## 6. Future Applications & Industrial Expansion Scope

* **Smart Underground Parking & Spacecraft Raceways:** Deploys IR/visible dual-wavelength, directional acoustic, and BLE Auracast/UWB anchors along raceways for autonomous parking/exploration robot positioning during normal times and evacuation guidance during disasters.
* **Underground/Tunnel Telecom Infrastructure Evolution & Subordinate Backhaul Integration:** Interoperates with 5G/6G small cell and DAS networks in underground parking, tunnels, and subterranean malls as auxiliary position fusion and telemetry backhaul, maintaining offline zero-downtime autonomy under fixed infrastructure anchors even during total network failure.
* **Hydrant & Orbital Module 3D Anchors:** Uses hydrant box surfaces and space station module internal chambers as 0-point calibration references to maintain tactile vibration guidance paths amidst severe visibility conditions.
* **AR Glasses Visual HUD & Smart Ring Tactile Evacuation Guidance:** Projects 3D evacuation guide lines in front of AR/MR smart glasses wearers, providing autonomous fallback to smart ring finger-tactile compasses when smoke obscures vision.
* **Space Station Pressurized Modules & IVA/EVA Suits:** Provides auxiliary navigation toward airlocks or escape modules via spacesuit-embedded haptic compasses and NVG HMDs during fires or depressurization events in zero-gravity orbital modules.
* **Autonomous Logistics (AMR) & Rescue Robot Navigation:** Enables automatic Visual SLAM error calibration and survivor tracking in wireless-communication-impaired environments and underground facilities or space modules using raceway and hydrant anchors.

---

## 7. Practical Protection & Legal Framework

* **Original Language Authority Rule:** Legal and technical interpretation of this specification is governed strictly by the Korean original (`README.ko.md`). English and other translations serve solely as secondary references.
* **Comprehensive Scope:** All concepts disclosed herein—including ANCHORs, ESTIMATION, Co-Survival Bridges (across all physical form factors like smart rings, vests, insoles), AR Glasses Visual HUDs, heterogeneous multi-device integration and Graceful Fallback, WebAR/NFC passive quick release, Visual SLAM Rapid Drift Reset, Auracast/UWB haptic compasses, underground small cell/DAS auxiliary integration, fire-rated hydrant physical anchoring, Tri-State Isolation, T-Reg Suppressor, distributed blackbox logs, spacesuit haptic guides, and AI self-evolution logic—apply broadly to secure comprehensive prior art coverage.
* **Separation of Business Execution:** This white paper contains exclusively Pure Open Source and prior art disclosure material. Commercial business models, pricing strategies, and proprietary execution plans are managed in separate technical documentation.
* **Defensive Publication & DPL License:** Disclosed to serve as prior art rejection grounds against third-party patent claims. Under DPL v1.0 terms, any entity initiating patent infringement litigation against the author or ecosystem participants regarding this technology forfeits their license rights immediately.
* **Prior Use Right & Trade Secret Bifurcation:** Maintains prior use rights under Article 103 of the Korean Patent Act and 35 U.S.C. §273. Precise feature extraction weights and neural network parameters are managed separately as trade secrets.
* **Patent Attorney Review Recommendation:** Review by a qualified patent attorney is recommended regarding DPL license application, prior use rights assertion, and utility model filings. Specific claim language may be adjusted during formal patent office filings.

---

## 8. Sources and Document Integrity Declaration

* **Master Survival Architecture:** GitHub - `deundeuni / chiplet-apu-multi-system-survival-architecture`
* **Linked Survival Strategy:** GitHub - `soma-moa / ARCHITECTURE_STRATEGY.md`
* **Linked Marine Armor:** GitHub - `soma-moa / MAX-LIFE ICE-BELT`
* **Linked CWP Hardware Repositories:**
  * GitHub - `deundeuni / CWP-Entry`
  * GitHub - `deundeuni / CWP-Rolling-Self-Align-Battery-Swap-System`
  * GitHub - `deundeuni / CWP-Battery-Swap`
  * GitHub - `deundeuni / CWP-Clamping-Battery-Swap-System`
* **Master Gateway:** `somamoa.ai.kr` (Canonical Gateway)
* **International Standards & Specifications:** ISO 7010, ISO 16069, Bluetooth SIG Auracast / LE Audio Specifications, UWB Standards, 3GPP Small Cell Specs, Korean Fire Safety Acts, National Fire Performance Codes (NFPC).
* **Legal Precedents & Guidelines:** Korean Patent Act Article 103 (Prior Use Right), US Patent Act 35 U.S.C. §273.
* **Document Integrity:** This document possesses full technical completeness as a standalone white paper.

---

## Appendix A: Inventorship
* System Architect & Sole Inventor: deundeuni
* Primary Repository: github.com/soma-moa
* License: CC BY 4.0 (Attribution Required) + DPL v1.0

## Appendix B: Version History
▶ Refer to Section 1 (Version History) of the main text.

---

## Appendix C: AI Assistance Disclosure & Tool Operational Rules
* **AI Assistance Disclosure —** All technical architectures, haptic logic, calculation formulas, and legal defense structures within this white paper belong strictly to the intellectual labor and field intuition of the sole human inventor (deundeuni). Artificial intelligence tools (AI models) were utilized strictly under the explicit direction of the inventor as auxiliary text editing, translation, and layout formatting tools (Auxiliary Text Editing Tools), and were not involved in the original technical ideation or invention process.
* **Declaration of Intellectual Ownership:** All core technical architectures, haptic compass algorithms, circuit control logic, and legal defense structures within this white paper belong entirely to the sole human inventor (deundeuni).

---

## Appendix D: Legal Disclaimer & Responsibility Limitation
* **Non-Substitutability for Statutory Equipment:** Technologies disclosed in this specification (LAST-LIGHT v4.8), associated software, QR/ArUco/NFC tags, BLE Auracast/UWB fabrics, spatial acoustic anchors, underground telecom integration modules, Co-Survival Bridges (in all form factors including smart rings, vests, insoles), AR Glasses Visual HUDs, smartwatch linkage software, and distributed blackboxes do not replace the legal, physical, or functional duties of statutory emergency exit lights, alarms, or fire equipment under national fire or building codes, operating strictly as auxiliary reference tools.
* **Limitation of Liability:** The author (deundeuni / soma-moa) and open-source contributors assume no civil or criminal liability for evacuation delays, communication failures, sensory perception errors, data losses, or personal/property damages resulting from the implementation or application of this document, code, or visual materials. All safety management and evacuation responsibilities remain with site safety managers, evacuees, and statutory equipment operators.
* **Intellectual Property & Trademark Disclaimer:** Technical standards (Bluetooth SIG, ISO, 3GPP, etc.) cited herein serve solely as explanatory public examples without intent to infringe upon third-party trademarks. All technical expressions shall be interpreted as abstract, generic engineering concepts unconstrained by specific commercial brands.
