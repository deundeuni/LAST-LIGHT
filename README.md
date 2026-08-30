LAST-LIGHT — Technical Specification for Auxiliary Wayfinding System via Standard Illuminated Signs, Internal/External Fire Cabinets, Smart Raceways, and Multi-Sensory Acoustic/Haptic Infrastructure (Ver. 3.7)

> Document Classification: Defensive Publication / Prior Art Technical Specification
> Initial Conception Date: July 30, 2026 / Final Revision Date (v3.7): August 31, 2026
> Original IP Holder: soma-moa (soma-moa / Sole Inventor: deundeuni)
> Primary Repository: [github.com/soma-moa](https://github.com/soma-moa) | Official Domain: somamoa.ai.kr
> Applicable Licenses: CC BY 4.0 & DPL v1.0 (Defensive Publication License)
> Original Language Authority Notice: The Korean original text of this specification constitutes the legally and technically binding authority. English and other translations are provided for reference purposes only. In the event of any linguistic, semantic, or legal discrepancy, the Korean original text shall take strict precedence.
> 

0. Inventor's Declaration and Motivation

0.1 Field-Driven Motivation

This structural design originates from a fundamental human purpose: "To ensure that every person can evacuate safely during a disaster, and to guarantee that firefighters who risk their lives to enter hazardous environments return safely to their families."
This core intent led to a field-driven technical intuition: "Can standard exit signage (pictograms) affixed to building walls serve as absolute visual references for smartphones, robots, and AR glasses during disasters?" and "Can multi-spectrum optical modules, directional acoustic emitters, BLE Auracast broadcast fabrics, and bone-conduction tactile interfaces placed within fire hose cabinets, alarm terminal boxes, and along ceiling raceways act as active survival anchors under complete zero-visibility conditions for both civilians and emergency responders?"
Existing emergency lightings remain passive markers, while GPS and Wi-Fi positioning suffer from severe signal attenuation and drift in indoor or blackout environments. By establishing permanently illuminated exit signs, internal/external fire service cabinets, underground electrical raceways, spatial sound anchors, and wireless RF beacons as Visual/Optical/Acoustic/RF Absolute Anchors (ANCHOR), this system provides high-visibility green guidance, 3D directional spatial audio, and personal wearable tactile vibrations for civilians, alongside high-contrast infrared (IR) signal pathways and bone-conduction haptic feedback for first responders.

0.2 Master Concept & Sensor Fusion Standard

The visual/optical/acoustic/RF ANCHOR-based zero-point calibration and offset correction mechanism disclosed in this specification serves as the Master Reference Framework for the overall positioning and wayfinding system.
Any additional integration of secondary positioning or sensing modalities—including gyroscopes, accelerometers, Inertial Measurement Units (IMUs), microphone arrays, acoustic/ultrasonic transducers, bone-conduction actuators, BLE Auracast RF modules, LiDAR, Time-of-Flight (ToF) sensors, thermal imaging, Ultra-Wideband (UWB), and infrared sensors—whether applied individually or in combination, constitutes a subordinate combination that relies on this master zero-point calibration. All such sensor fusion implementations fall entirely within the scope of this prior art.

0.3 Zero-Downtime Resilience & Non-Contact Principle

This structural design strictly prohibits physical or electrical modifications to mandatory statutory fire/safety equipment. The system prioritizes organic, zero-downtime fail-over resilience. Each module maintains an independent multi-mesh network topology to eliminate single points of failure (SPOF). Upon the physical destruction of any node, adjacent modules autonomously assume positioning, calculation, and multi-sensory guidance control without system crash.

0.4 Non-Exclusive Interoperability & Open Public Standard

This structural design is not proprietary to any specific optical camera, vision sensor, microphone array, bone-conduction headset, LiDAR, mobile device, or robotic framework. It operates as an Open Public Standard capable of utilizing all public-domain illuminated signs (e.g., ISO 7010 series), fire service cabinet indicators (internal/external), directional sound anchors, BLE Auracast transmitters, and ceiling raceway optical anchors as reference points.

0.5 Operational Priority Control

In the event of computational or sensory overload during an emergency, the system prioritizes absolute reference (ANCHOR) identification and position offset correction over secondary tasks (such as high-definition visual reconstruction or decorative audio/UI rendering), maintaining continuous wayfinding execution.

0.6 Universal Application Scope

This structural design comprehensively applies to smartphone-based pedestrian evacuation applications, autonomous mobile robot (AMR) relocation modules, smart emergency lighting/acoustic anchors, internal/external fire cabinet anchors, underground raceway multi-spectrum anchors, disaster relief AR glasses, firefighter NVG equipment, personal bone-conduction wearable interfaces, and haptic rescue headsets.

0.7 Disclosure Purpose and Limitation Notice

This document is published as defensive prior art. The descriptions of features, configurations, and performance herein are illustrative and do not limit or guarantee specific implementations. This system does not replace, alter, or expand statutory fire safety facilities, functioning purely as a supportive reference mechanism.

0.8 Acknowledgement of Independent Prior Research

While this structural design was independently conceived and formulated by the inventor, it does not exclude the possibility that similar concepts regarding visual, acoustic, or RF reference utilization were independently developed by other researchers or entities. The primary objective of this publication is not to claim exclusive monopoly, but to record this intuitive framework as public prior art, preventing private monopolization and allowing public access for safety implementation.

1. Revision History Summary

 * v1.0 (2026-07-30) ~ v3.7 (2026-08-31): Formulated initial visual anchoring concept, expanded to full-stack structural design, multi-sensory (spatial audio/bone-conduction/BLE Auracast) integration, self-healing mesh networking, privacy isolation mechanisms, rapid onboarding, and legal defensibility over 17 iterations. (Note: For complete itemized revision details, refer to the standalone document "LAST-LIGHT Technical Specification Revision History for Auxiliary Guidance System (Ver. 3.7)".)

2. Full-Stack Applied Structural Design
 (3-Tier Applied Architecture)

 * [L2] Auxiliary Guidance & Specialized UI Layer: Civilian green visual, 3D spatial audio guidance, personal bone-conduction tactile vibration cues, AR/voice wayfinding assistance, firefighter/first-responder IR/NVG high-contrast overlay, bone-conduction tactile guidance, and telemetry backhaul.
 * [L1] Perception & Estimation Fabric: Multi-spectrum (visible/IR) feature extraction modules, microphone array Direction of Arrival (DOA) & acoustic signal processing, BLE Auracast RF signal processing, estimation filtering algorithms (EKF, Doppler/phase probabilistic models), sensor fusion engines (gyro/IMU/acoustic/LiDAR), AI state estimators, self-healing mesh networking, and confidence verification modules.
 * [L0] Infrastructure & Optical/Acoustic/RF Layer: ISO 7010 emergency signage, fire hose cabinet/alarm terminal box internal & external status indicators (red/multi-spectrum LED) & directional sound emitters, ceiling raceway multi-spectrum/acoustic/BLE Auracast emitters, passive QR tags, emergency power interfaces, and non-contact reception sensors.

2.5 AI Governance & Model Architecture

 * Abstract Master AI Engine Definition (Anti-Circumvention):
   The AI processing unit is not restricted to specific model parameters, neural topologies, chipsets, or execution environments. It encompasses all abstract perception and estimation entities, including edge AI, small Language/Vision/Audio models (sLLM/SVM/SAM), cloud-tethered large models (LLM/VLM), multi-spectrum vision and acoustic signal neural networks (CNN/Transformer/Audio Spectrogram Transformer), and hybrid edge-cloud topologies.
 * Rationale for Edge AI / sLLM / Small Vision-Audio Model Deployment:
   Disaster environments involve severe blackout conditions, power cuts, server destruction, and cellular network paralysis. Additionally, mobile, bone-conduction, and AR end-user devices operate under strict power and compute constraints. Therefore, optimized edge-native AI models (sLLM, SVM/SAM, NPU firmware engines) capable of zero-latency, offline multi-sensory operation are established as the primary implementation embodiment.
 * Core AI Functions:
   * Multi-Spectrum & Spatial Acoustic/RF Perception: Asynchronously isolates ISO 7010 pictograms, internal/external fire cabinet indicators, raceway IR/visible emitters, acoustic anchor frequencies, and BLE Auracast signals amidst dense smoke, ambient fire noise, and backlight distortion.
   * Dynamic Offset Correction: Computes real-time zero-point calibration matrix to eliminate cumulative IMU/gyroscope drift errors via Kalman filtering, Direction of Arrival (DOA) audio phase calculations, and probabilistic state estimation.
   * Confidence Control & Adaptive Signal Generation: Suppresses hallucinated guidance when perception confidence drops below thresholds, and independently generates tailored multi-sensory guidance (visible/spatial audio/vibrations for civilians, IR/NVG/bone-conduction tactile vibrations for first responders).

3. Core System Blocks and Mechanisms

 * A. ANCHOR Signage, Internal/External Fire Cabinets, Acoustic/RF Anchors & Raceway Sensing Unit (Absolute Reference Infrastructure):
   * ISO 7010 standard emergency signs, building fire hose cabinets, alarm terminal boxes, power control panels (surface status LEDs, housing geometry, internal protective chambers, inner door surfaces), ceiling raceways, directional audio speakers / spatial sound anchors (Acoustic Anchors), and BLE Auracast wireless broadcast modules act as absolute spatial reference nodes (ANCHOR).
   * Under zero-visibility dense smoke environments, directional spatial audio, frequency-modulated acoustic signals, and BLE Auracast emergency broadcast streams emitted from ANCHOR nodes provide multi-sensory zero-point calibration.
   * Transmits specialized multi-channel guidance to first responders via bone-conduction tactile vibration signals, high-penetration acoustic frequencies, and specialized RF data streams, ensuring clear directionality even in deafening fireground environments.
   * Operates via non-contact optical, acoustic, and RF reception without requiring electrical or physical modifications to existing legacy infrastructure.
 * B. ESTIMATION & Multi-Sensory Auxiliary Guidance Unit (Estimation & Processing):
   * Feature Extraction: Extracts ISO pictogram geometries, internal/external fire cabinet status indicators, raceway multi-spectrum corner points, acoustic phase/delay/DOA (Direction of Arrival) spectrogram features, and BLE RF signal metrics (RSSI/AoA) from optical camera, microphone array, and RF receiver feeds.
   * Estimation Algorithm (Input / Process / Output):
     * Input: Relative movement vectors from IMU/gyroscope/LiDAR/acoustic/RF sensors, optical ANCHOR features, and acoustic/RF phase/DOA observations.
     * Process: Real-time correction of IMU cumulative drift matrices using AI state estimators, Extended Kalman Filters (EKF), acoustic triangulation, and Gaussian probability models.
     * Output: 3D spatial state coordinates with error covariance matrices, alongside synchronized visual, spatial audio, BLE LC3 audio, and bone-conduction haptic direction signals (e.g., directional audio prompts and localized tactile vibrations indicating "Exit 3m Left" or "Fire Cabinet Anchor Ahead").
   * Signal Generation & Confidence Control: Produces complementary visual, acoustic, and tactile wayfinding outputs; automatically halts guidance rendering if spatial confidence falls below safety thresholds.
 * C. Emergency Power Integration & Operating Duration:
   * Mandatory Emergency Power Interface: Integrates with building emergency power systems (generators, UPS, auxiliary battery circuits) or incorporates dedicated local energy storage to guarantee blackout operation.
   * Power Source Agnosticism: Encompasses all energy storage formats, including lithium-based cells, LFP, solid-state batteries, supercapacitors, optical/thermal/acoustic energy harvesting, and hybrid configurations.
   * Comprehensive Operating Duration Range: Encompasses all operating durations, ranging from initial evacuation periods under 2 hours (including statutory 20-minute and 60-minute baselines) to extended mission windows of 2 to 4+ hours (extending up to 6h, 12h, 24h+) required for firefighter rescue operations.
 * D. Self-Healing Multi-Mesh & Zero-Downtime Fail-Over:
   * Independent Multi-Mesh Topology: Nodes form peer-to-peer (P2P) N-mesh topologies independent of single central lines.
   * Dynamic Self-Healing: Upon physical destruction of any node, the mesh isolates the failed node within 100ms and reroutes communication, compute, acoustic, and BLE broadcast signals around the failure point.
   * Zero-Downtime Fail-Over: Adjacent functional nodes autonomously assume spatial calculation, optical emission, BLE broadcasting, and spatial audio/haptic rendering tasks of destroyed units, ensuring uninterrupted wayfinding execution.
 * E. Personal Wearable Interface — Open-Ear Bone-Conduction Earphone Integration Specification:
   * Open-Ear Acoustic Architecture: Leverages evacuees' personal open-ear bone-conduction headsets, ensuring that auxiliary wayfinding tones and tactile haptic feedback do not obstruct ambient auditory perception of statutory alarm sirens or firefighter verbal commands.
   * Broadcast Fabric: L0 ANCHORs broadcast emergency streams via BLE Auracast. Evacuee mobile devices receive these broadcasts and relay low-latency audio/haptic cues via BLE LE Audio (LC3 codec) to personal bone-conduction transducers.
   * Zero-Visibility Haptic Guidance: Under zero-visibility conditions, tactile vibration patterns applied to left or right bone transducers (e.g., dual pulses on the left transducer indicating a left turn) deliver intuitive spatial directions with end-to-end latency below 100ms.
   * Evacuation Guide Hub Role: Evacuees equipped with bone-conduction guidance receive clear, real-time spatial orientation, enabling them to act as field evacuation hubs who assist children, elderly individuals, or disoriented civilians.
   * Auditory Safety Control: Operates strictly as a non-intrusive secondary aid, dynamically managing output volume and waveform profiles to prevent interference with primary safety alarms.
 * F. Rapid Onboarding & Normal-State Privacy Isolation Specification:
   * Normal-State Disconnection & Privacy Preservation: Prior to an emergency, L0 ANCHOR Auracast transmissions remain inactive (transmitting low-power bursts under 0.1s per minute). Physical and logical connections with civilian mobile devices are severed. Location tracking, data harvesting, and battery drain during normal conditions are strictly prohibited.
   * Active Emergency Switch & 3-Second Onboarding: Upon fire alarm signal detection, Auracast broadcasting automatically activates. Scanning a passive 2cm QR tag affixed near signage or fire cabinets triggers a deep-link (last-light://{anchor_id}?b={broadcast_id}&k={public_temp_key}), onboarding the device into the emergency guidance channel within 3 seconds without app installation or complex pairing.
   * Visibility-Impaired Auto-Discovery: If smoke obscures the physical QR tag, mobile devices automatically search and attach to the two strongest nearby BLE Auracast anchor signals.
   * Passive QR Tag Installation Standards: QR tags contain no personal data and require no external power. Tags must be placed so as not to obscure statutory lighting surfaces or mandatory safety markings.
 * G. Multi-Sensory Anchor Evacuation Guidance Structural Specification:
   * Context: Designed for blackout and smoke-filled disaster environments (e.g., underground parking facilities) where visual navigation is severely impaired.
   * Wearable Hub Execution: Evacuees utilizing open-ear bone-conduction wearables process BLE Auracast and spatial audio cues to maintain directionality while guiding disoriented individuals toward safety.
   * Multi-Anchor Synergy: ISO 7010 exit signs and red fire cabinet indicators act as primary visual spatial anchors, while ceiling raceway/tray units project spatial audio waves and BLE Auracast RF coverage, forming an integrated multi-sensory guidance matrix.

4. Dynamic Resource Management & Defensive Safety Control

 * Rate Limiter: Dynamically caps frame, audio packet, and BLE reception rates to prevent processor saturation under excessive inputs.
 * Random Sampling Scan: Asynchronously samples ambient lighting, glare, and acoustic/RF noise variations to isolate invalid inputs into sandboxed buffers.
 * Relocation Interception: Blocks offset correction routines if unauthorized glare, reflections, spoofed audio, or rogue BLE packets are detected.
 * T-Reg Suppressor: Hardware-throttles AI and positioning compute cycles if system power or compute utilization exceeds safety limits.
 * Tri-State Isolation: Switches control interfaces to a High-Z (High-Impedance) state within 0.1 seconds upon detecting internal processing faults, isolating the auxiliary system from statutory equipment.

5. Standards Alignment and Legal Boundaries

 * Standards Compliance: Conforms to ISO 7010, ISO 16069, Bluetooth SIG specifications, statutory fire safety optical conventions, and acoustic signaling standards without claiming exclusive proprietary rights over international standards.
 * Non-Replacement of Statutory Equipment: Does not replace, alter, or satisfy statutory fire safety lighting/alarm requirements; operates strictly as a supplementary reference framework.
 * Physical Operational Limits: Acknowledges that extreme smoke density, severe acoustic noise, or RF shielding may degrade sensory line-of-sight; primary evacuation responsibility remains with statutory systems and fire authority personnel.

6. Industrial Applicability and Future Extensions

 * Smart Underground Raceway Visual/Acoustic/RF Anchors: Multi-spectrum dual emitters, directional audio modules, and BLE Auracast anchors deployed along ceiling raceways for autonomous parking robot calibration and emergency wayfinding.
 * Internal/External Fire Cabinet 3D Spatial Anchors: Utilization of fire hose cabinet status lights, internal chamber modules, and multi-sensory beacons as zero-point reference nodes in zero-visibility corridors.
 * Smart Building AR, NVG & Bone-Conduction Navigation: 3D spatial overlay projection, spatial audio, and tactile bone-conduction haptic feedback for AR glasses, NVG devices, and rescue headsets in complete blackout environments.
 * AMR Indoor Positioning: Absolute offset correction for logistics robots operating in GPS-denied underground facilities via optical, acoustic, and RF anchor fusion.
 * Disaster Relief Robotics: Multi-sensory anchor tracking for search-and-rescue robotics in hazardous, smoke-filled structures.

7. Legal and Defensive Publication Declarations

This document establishes a 4-tier legal defense framework to protect the inventor's (soma-moa / deundeuni) non-exclusive rights and prevent third-party patent monopolization:
 * Prior Art Timestamp: Establishes documented prior art to defeat third-party patent claims covering identical or substantially similar concepts.
 * Defensive Publication License (DPL): Enforces conditional termination clauses against any party initiating patent infringement litigation against the inventor or ecosystem participants.
 * Prior User Rights: Establishes evidence supporting non-exclusive prior user rights under applicable patent legislation.
 * Trade Secret Reservation: Precise visual/acoustic feature extraction algorithms, directional audio phase parameters, BLE LC3 haptic translation parameters, and edge-AI NPU optimization weights are retained offline as confidential trade secrets.
7.0 Public Purpose
This disclosure is made not to assert exclusive commercial monopoly, but to place the technology in the public domain as prior art, preventing third parties from privatizing life-safety infrastructure.

7.1 DPL & CC BY 4.0 Defense Conditions

Any entity bringing patent infringement litigation regarding implementations derived from this document shall forfeit all license rights granted under this publication, effective retroactively.

7.2 Statutory Prior User Rights

This document serves as evidence of prior creation and conception under Article 103 of the Korean Patent Act and 35 U.S.C. §273.

7.3 Anti-Circumvention and Doctrine of Equivalents

All terms (structural design, system architecture, blueprint, ANCHOR, ESTIMATION, Master Reference, internal/external fire cabinet anchor, acoustic anchor, spatial audio, directional speaker, microphone array, bone conduction, BLE Auracast, LC3 codec, rapid QR onboarding, sLLM/Edge AI, self-healing mesh, zero-downtime fail-over, etc.) and numerical ranges represent non-limiting embodiments. Any functional equivalents, terminology substitutions, or structural rearrangements fall within the scope of this prior art.

7.4 Software-Defined Equivalents

All optical/acoustic/RF processing, sensor fusion, mesh routing, power management, and AI governance mechanisms may be equivalently implemented via edge-NPU firmware, virtualized software, or software-defined architectures without departing from the prior art scope.

8. References and Document Authority

 * [Standards] ISO 7010 (Graphical symbols — Safety colours and safety signs), ISO 16069 (Safety way guidance systems), Bluetooth SIG Auracast / LE Audio Specifications, Korean Fire Safety Standards.
 * [Legal Statutes] Korean Patent Act Article 103, 35 U.S.C. §273.
 * Completeness: This document constitutes a standalone, self-contained technical specification.
 * Original Language Authority: The Korean original document is the sole original authority (Original Authority). In case of ambiguities in translated versions, the Korean original text governs.
Appendix A: Inventorship
 * System Architect & Sole Inventor: deundeuni
 * Primary Repository: github.com/soma-moa
 * License: CC BY 4.0 (Attribution Required) + DPL v1.0
Appendix B: Version History
 * v1.0 (2026-07-30): Initial formulation of visual anchor concept.
 * v2.0 ~ v3.0 (2026-08-30): Full-stack structural design, raceway dual-spectrum emitters, edge AI governance, and self-healing multi-mesh fail-over.
 * v3.1 ~ v3.6 (2026-08-30): Independent prior research (0.8), AI disclosure (Appendix C), emergency power (3.C), sensor fusion baseline (0.2), fire cabinet anchor specs (3.A), spatial audio, and bone-conduction specs.
 * v3.7 (2026-08-31): Integration of personal open-ear bone-conduction wearable interface (3.E), normal-state privacy isolation and rapid onboarding (3.F), multi-sensory structural guidance concept (3.G), and finalized legal liability disclaimers.
Appendix C: AI Assistance Disclosure
 * Original Architecture & Concepts: deundeuni (Human) — Sole Inventor, overall system architecture, field motivation, and final decision-making authority.
 * Draft Generation: Meta AI — Initial draft generation and structural scaffolding assistance.
 * Document Structuring & Expansion: Gemini — Structural refinement, terminology standardization, raceway/fire cabinet optics, spatial audio anchors, bone conduction, BLE Auracast integration, privacy onboarding, and master reference framework expansion.
 * Review & Technical Validation: Claude — Technical verification, nomenclature standardization, and legal defense framework validation.
This disclosure is provided for transparency. AI prompts, internal chain-of-thought processing, and trade secret algorithms remain undisclosed. All final intellectual property rights belong exclusively to the human inventor (deundeuni / soma-moa).
Legal Boundaries and Liability Disclaimers
 * Non-Replacement of Statutory Equipment: The technology disclosed in this specification (LAST-LIGHT v3.7), including software, QR tags, BLE Auracast fabrics, spatial audio anchors, and wearable interfaces, does not replace the statutory, physical, or functional performance of mandatory emergency lighting, fire alarm systems, or hydrant indicators required by fire safety legislation. It functions solely as a supplementary reference aid.
 * Limitation of Liability: The original inventor (deundeuni / soma-moa) and development ecosystem contributors assume no civil or criminal liability for evacuation delays, communication failures, sensory perception errors, personal injury, property damage, or legal disputes resulting from the implementation or application of this specification, open-source code, or passive QR onboarding tags. All evacuation decisions and safety management remain the sole responsibility of facility operators, evacuees, and emergency response authorities.
 * Intellectual Property & Trademark Disclaimer: All technical standards cited herein (such as Bluetooth SIG and ISO) are referenced strictly for illustrative compliance purposes. There is no intent to infringe upon third-party trademarks or brand rights. All technical expressions shall be construed as general, vendor-neutral technology concepts.
