# LAST-LIGHT — Technical Specification for Auxiliary Wayfinding System via Standard Illuminated Signs, Internal/External Fire Cabinets, and Smart Raceways (Ver. 3.5)

> **Document Classification:** Defensive Publication / Prior Art Technical Specification  
> **Initial Conception Date:** July 30, 2026 / **Final Revision Date (v3.5):** August 30, 2026  
> **Original IP Holder:** soma-moa (`soma-moa` / Sole Inventor: `deundeuni`)  
> **Primary Repository:** `github.com/soma-moa` | **Official Domain:** `somamoa.ai.kr`  
> **Applicable Licenses:** CC BY 4.0 & DPL v1.0 (Defensive Publication License)  
> **Original Language Authority Notice:** The Korean original text of this specification constitutes the legally and technically binding authority. English and other translations are provided for reference purposes only. In the event of any linguistic, semantic, or legal discrepancy, the Korean original text shall take strict precedence.

---

## 0. Inventor's Declaration and Motivation

### 0.1 Field-Driven Motivation
This architecture originates from a fundamental human purpose: **"To ensure that every person can evacuate safely during a disaster, and to guarantee that firefighters who risk their lives to enter hazardous environments return safely to their families."**

This core intent led to a field-driven technical intuition: **"Can standard exit signage (pictograms) affixed to building walls serve as absolute visual references for smartphones, robots, and AR glasses during disasters?"** and **"Can multi-spectrum optical modules placed within fire hose cabinets, alarm terminal boxes, and along ceiling raceways act as active survival anchors for both civilians and emergency responders?"**

Existing emergency lightings remain passive markers, while GPS and Wi-Fi positioning suffer from severe signal attenuation and drift in indoor or blackout environments. By establishing permanently illuminated exit signs, internal/external fire service cabinets, and underground electrical raceways as **Visual/Optical Absolute Anchors (ANCHOR)**, this system provides high-visibility green/visible guidance for civilians, and high-contrast infrared (IR)/multi-spectrum signal pathways visible through Night Vision Goggles (NVG) for first responders.

### 0.2 Master Concept & Sensor Fusion Standard
The visual/optical ANCHOR-based zero-point calibration and offset correction mechanism disclosed in this specification serves as the **Master Reference Framework** for the overall positioning and wayfinding system.

Any additional integration of secondary positioning or sensing modalities—including gyroscopes, accelerometers, Inertial Measurement Units (IMUs), LiDAR, Time-of-Flight (ToF) sensors, thermal imaging, ultrasonic sensors, Ultra-Wideband (UWB), and infrared sensors—whether applied individually or in combination, constitutes a subordinate combination that relies on this master zero-point calibration. All such sensor fusion implementations fall entirely within the scope of this prior art.

### 0.3 Zero-Downtime Resilience & Non-Contact Principle
This architecture strictly prohibits physical or electrical modifications to mandatory statutory fire/safety equipment. The system prioritizes organic, zero-downtime fail-over resilience. Each module maintains an independent multi-mesh network topology to eliminate single points of failure (SPOF). Upon the physical destruction of any node, adjacent modules autonomously assume positioning, calculation, and guidance control without system crash.

### 0.4 Non-Exclusive Interoperability & Open Public Standard
This architecture is not proprietary to any specific optical camera, vision sensor, LiDAR, mobile device, or robotic vision framework. It operates as an Open Public Standard capable of utilizing all public-domain illuminated signs (e.g., ISO 7010 series), fire service cabinet indicators (internal/external), and ceiling raceway optical anchors as reference points.

### 0.5 Operational Priority Control
In event of computational overload during an emergency, the system prioritizes absolute reference (ANCHOR) identification and position offset correction over secondary tasks (such as high-definition visual reconstruction or decorative UI rendering), maintaining continuous wayfinding execution.

### 0.6 Universal Application Scope
This architecture comprehensively applies to smartphone-based pedestrian evacuation applications, autonomous mobile robot (AMR) relocation modules, smart emergency lighting anchors, internal/external fire cabinet anchors, underground raceway multi-spectrum anchors, disaster relief AR glasses, and firefighter NVG equipment.

### 0.7 Disclosure Purpose and Limitation Notice
This document is published as defensive prior art. The descriptions of features, configurations, and performance herein are illustrative and do not limit or guarantee specific implementations. This system does not replace, alter, or expand statutory fire safety facilities, functioning purely as a supportive reference mechanism.

### 0.8 Acknowledgement of Independent Prior Research
While this architecture was independently conceived and formulated by the inventor, it does not exclude the possibility that similar concepts regarding visual reference utilization were independently developed by other researchers or entities. The primary objective of this publication is not to claim exclusive monopoly, but to record this intuitive framework as public prior art, preventing private monopolization and allowing public access for safety implementation.

---

## 1. Revision History

* **v1.0 (2026-07-30)** — Initial formulation of visual anchor concept based on ISO 7010 signs and auxiliary guidance framework.
* **v1.5 (2026-08-01)** — Refinement of dual-purpose public/commercial emergency guidance patent specification structure.
* **v2.0 (2026-08-30)** — Restoration of original field motivation; full-stack layer integration corresponding to chiplet-APU architecture v2.6.
* **v2.5 (2026-08-30)** — Integration of fixed-interval multi-spectrum (visible green / firefighter IR & fluorescence) raceway anchor specifications.
* **v2.6 (2026-08-30)** — Standardized section 4 nomenclature ("Dynamic Resource Management & Defensive Safety Control").
* **v2.7 (2026-08-30)** — Explicit definition of ESTIMATION algorithm Input/Process/Output (IPO) structures to guarantee reproducibility while preserving trade secrets.
* **v2.8 (2026-08-30)** — Formal timestamp correction (2026-07-30) and integration of humanity-driven life safety philosophy.
* **v2.9 (2026-08-30)** — Addition of abstract AI governance definitions and edge AI / sLLM deployment rationale under communications blackout (2.5).
* **v3.0 (2026-08-30)** — Integration of self-healing multi-mesh communication and zero-downtime fail-over mechanisms for destroyed modules.
* **v3.1 (2026-08-30)** — Addition of independent prior research acknowledgement (0.8) and AI assistance disclosure (Appendix C).
* **v3.2 (2026-08-30)** — Integration of mandatory emergency power integration and comprehensive operating duration ranges (3.C).
* **v3.3 (2026-08-30)** — Master Reference Framework declaration for sensor fusion (0.2) and comprehensive anti-circumvention provisions (7.3).
* **v3.4 (2026-08-30)** — Integration of fire hose cabinet, alarm terminal box, and emergency power panel indicators as optical anchors (3.A).
* **v3.5 (2026-08-30)** — [Final] Integration of internal fire cabinet chamber/cover deployment and 3D high-survival optical anchor network specifications (3.A).

---

## 2. Full-Stack Applied Architecture (3-Tier Applied Architecture)

* **[L2] Auxiliary Guidance & Specialized UI Layer:** Civilian green visual guidance, firefighter/first-responder IR/NVG high-contrast overlay, AR/auditory wayfinding assistance, and telemetry backhaul.
* **[L1] Perception & Estimation Fabric:** Multi-spectrum (visible/IR) feature extraction modules, estimation filtering algorithms (EKF, Gaussian, probabilistic models), sensor fusion engines (gyro/IMU/LiDAR), AI state estimators, self-healing mesh networking, and confidence verification modules.
* **[L0] Infrastructure & Optical Layer:** ISO 7010 emergency signage, fire hose cabinet/alarm terminal box internal & external status indicators (red/multi-spectrum LED), ceiling raceway/cable tray multi-spectrum emitters (IR/green/fluorescent/white), emergency power interfaces, and non-contact optical sensors.

### 2.5 AI Governance & Model Architecture

* **Abstract Master AI Engine Definition (Anti-Circumvention):**
  The AI processing unit is not restricted to specific model parameters, neural topologies, chipsets, or execution environments. It encompasses all abstract perception and estimation entities, including edge AI, small Language/Vision models (sLLM/SVM), cloud-tethered large models (LLM/VLM), multi-spectrum vision neural networks (CNN/Transformer), and hybrid edge-cloud topologies.

* **Rationale for Edge AI / sLLM / Small Vision Model Deployment:**
  Disaster environments involve severe blackout conditions, power cuts, server destruction, and cellular network paralysis. Additionally, mobile and AR end-user devices operate under strict power and compute constraints. Therefore, optimized edge-native AI models (sLLM, SVM, NPU firmware engines) capable of zero-latency, offline operation are established as the primary implementation embodiment.

* **Core AI Functions:**
  * **Multi-Spectrum Perception:** Asynchronously isolates ISO 7010 pictograms, internal/external fire cabinet indicators, and raceway IR/visible emitters amidst dense smoke, backlight distortion, and camera motion blur.
  * **Dynamic Offset Correction:** Computes real-time zero-point calibration matrix to eliminate cumulative IMU/gyroscope drift errors via Kalman filtering and probabilistic state estimation.
  * **Confidence Control & Adaptive Signal Generation:** Suppresses hallucinated guidance when perception confidence drops below thresholds, and independently generates tailored guidance vectors for civilians (visible) and first responders (IR/NVG).

---

## 3. Core System Blocks and Mechanisms

* **A. ANCHOR Signage, Internal/External Fire Cabinets & Raceway Sensing Unit (Absolute Reference Infrastructure):**
  * ISO 7010 standard emergency signs, building fire hose cabinets, alarm terminal boxes, power control panels (including surface status LEDs, housing geometry, internal protective chambers, inner door surfaces, and translucent window interiors), and ceiling raceway/cable tray optical modules act as absolute spatial anchors (ANCHOR).
  * In the event of upper-ceiling smoke obscuration or external cabinet damage, internal protective chamber emitters continue to transmit IR/multi-spectrum signals to maintain 3D zero-point calibration continuity.
  * Emits high-visibility green spectrum for general civilian vision during normal and emergency states.
  * Emits multi-spectrum signals (IR, high-contrast fluorescent, white) specifically tuned for firefighter NVG and optical rescue gear.
  * Operates via non-contact optical reception without requiring electrical or physical modifications to existing legacy infrastructure.

* **B. ESTIMATION & Auxiliary Guidance Unit (Estimation & Processing):**
  * **Feature Extraction:** Extracts ISO pictogram geometries, internal/external fire cabinet status indicators, and raceway multi-spectrum corner points from optical camera feeds.
  * **Estimation Algorithm (Input / Process / Output):**
    * **Input:** Relative movement vectors from IMU/gyroscope/LiDAR sensors and spatial angle/distance vectors from ANCHOR features.
    * **Process:** Real-time correction of IMU cumulative drift matrices using AI state estimators, Extended Kalman Filters (EKF), or Gaussian probability models.
    * **Output:** 3D spatial state coordinates with error covariance matrices and auxiliary navigation signals.
  * **Signal Generation & Confidence Control:** Produces tailored wayfinding outputs; automatically halts guidance rendering if spatial confidence falls below safety thresholds.

* **C. Emergency Power Integration & Operating Duration:**
  * **Mandatory Emergency Power Interface:** Integrates with building emergency power systems (generators, UPS, auxiliary battery circuits) or incorporates dedicated local energy storage to guarantee blackout operation.
  * **Power Source Agnosticism:** Encompasses all energy storage formats, including lithium-based cells, LFP, solid-state batteries, supercapacitors, optical/thermal energy harvesting, and hybrid configurations.
  * **Comprehensive Operating Duration Range:** Encompasses all operating durations, ranging from initial evacuation periods under 2 hours (including statutory 20-minute and 60-minute baselines) to extended mission windows of 2 to 4+ hours (extending up to 6h, 12h, 24h+) required for firefighter rescue operations.

* **D. Self-Healing Multi-Mesh & Zero-Downtime Fail-Over:**
  1. **Independent Multi-Mesh Topology:** Nodes form peer-to-peer (P2P) N-mesh topologies independent of single central lines.
  2. **Dynamic Self-Healing:** Upon physical destruction of any node, the mesh isolates the failed node within 100ms and reroutes communication and compute tasks around the failure point.
  3. **Zero-Downtime Fail-Over:** Adjacent functional nodes autonomously assume the spatial calculation and guidance rendering tasks of destroyed units, ensuring uninterrupted wayfinding execution.

---

## 4. Dynamic Resource Management & Defensive Safety Control

* **Rate Limiter:** Dynamically caps frame intake rates to prevent processor saturation under excessive visual inputs.
* **Random Sampling Scan:** Asynchronously samples ambient lighting variations to isolate noise, smoke, and backlight artifacts into sandboxed buffers.
* **Relocation Interception:** Blocks offset correction routines if unauthorized glare, reflections, or spoofed optical points are detected.
* **T-Reg Suppressor:** Hardware-throttles AI and positioning compute cycles if system power or compute utilization exceeds established safety limits.
* **Tri-State Isolation:** Switches control interfaces to a High-Z (High-Impedance) state within 0.1 seconds upon detecting internal processing faults, isolating the auxiliary system from statutory equipment.

---

## 5. Standards Alignment and Legal Boundaries

* **Standards Compliance:** Conforms to ISO 7010, ISO 16069, and statutory fire safety optical conventions without claiming exclusive proprietary rights over international standards.
* **Non-Replacement of Statutory Equipment:** Does not replace, alter, or satisfy statutory fire safety lighting requirements; operates strictly as a supplementary reference framework.
* **Physical Operational Limits:** Acknowledges that extreme smoke density may degrade optical line-of-sight; primary evacuation responsibility remains with statutory systems and fire authority personnel.

---

## 6. Industrial Applicability and Future Extensions

* **Smart Underground Raceway Anchors:** Multi-spectrum emitter deployment on ceiling raceways for autonomous parking robot calibration and emergency first-responder guidance.
* **Internal/External Fire Cabinet 3D Spatial Anchors:** Utilization of fire hose cabinet status lights and internal chamber modules as zero-point reference nodes in smoke-filled corridors.
* **Smart Building AR & NVG Navigation:** 3D spatial overlay projection for AR glasses and NVG devices using ceiling raceways, exit signs, and fire cabinets in zero-visibility environments.
* **AMR Indoor Positioning:** Absolute offset correction for logistics robots operating in GPS-denied underground facilities.
* **Disaster Relief Robotics:** Vision-guided anchor tracking for search-and-rescue robotics in hazardous structures.

---

## 7. Legal and Defensive Publication Declarations

This document establishes a 4-tier legal defense framework to protect the inventor's (`soma-moa` / `deundeuni`) non-exclusive rights and prevent third-party patent monopolization:

* **Prior Art Timestamp:** Establishes documented prior art to defeat third-party patent claims covering identical or substantially similar concepts.
* **Defensive Publication License (DPL):** Enforces conditional termination clauses against any party initiating patent infringement litigation against the inventor or ecosystem participants.
* **Prior User Rights:** Establishes evidence supporting non-exclusive prior user rights under applicable patent legislation.
* **Trade Secret Reservation:** Precise visual feature extraction algorithms, multi-spectrum switching parameters, and edge-AI NPU optimization weights are retained offline as confidential trade secrets.

### 7.0 Public Purpose
This disclosure is made not to assert exclusive commercial monopoly, but to place the technology in the public domain as prior art, preventing third parties from privatizing life-safety infrastructure.

### 7.1 DPL & CC BY 4.0 Defense Conditions
Any entity bringing patent infringement litigation regarding implementations derived from this document shall forfeit all license rights granted under this publication, effective retroactively.

### 7.2 Statutory Prior User Rights
This document serves as evidence of prior creation and conception under Article 103 of the Korean Patent Act and 35 U.S.C. §273.

### 7.3 Anti-Circumvention and Doctrine of Equivalents
All terms (ANCHOR, ESTIMATION, Master Reference, internal/external fire cabinet anchor, sLLM/Edge AI, self-healing mesh, etc.) and numerical ranges represent non-limiting embodiments. Any functional equivalents, terminology substitutions, or structural rearrangements fall within the scope of this prior art.

### 7.4 Software-Defined Equivalents
All optical processing, sensor fusion, mesh routing, and AI governance mechanisms may be equivalently implemented via edge-NPU firmware, virtualized software, or software-defined architectures without departing from the prior art scope.

---

## 8. References and Document Authority

* **[Standards]** ISO 7010 (Graphical symbols — Safety colours and safety signs), ISO 16069 (Safety way guidance systems), Korean Fire Safety Standards.
* **[Legal Statutes]** Korean Patent Act Article 103, 35 U.S.C. §273.
* **Completeness:** This document constitutes a standalone, self-contained technical specification.
* **Original Language Authority:** The Korean original document is the sole original authority (`Original Authority`). In case of ambiguities in translated versions, the Korean original text governs.

---

### Appendix A: Inventorship
* **System Architect & Sole Inventor:** deundeuni
* **Primary Repository:** github.com/soma-moa
* **License:** CC BY 4.0 (Attribution Required) + DPL v1.0

---

### Appendix B: Version History
* **v1.0 (2026-07-30):** Initial formulation of visual anchor concept.
* **v2.0 ~ v3.0 (2026-08-30):** Full-stack architecture, raceway dual-spectrum emitters, edge AI governance, and self-healing multi-mesh fail-over.
* **v3.1 ~ v3.4 (2026-08-30):** Independent prior research (0.8), AI disclosure (Appendix C), emergency power (3.C), sensor fusion baseline (0.2), and fire cabinet anchor specs (3.A).
* **v3.5 (2026-08-30):** Internal fire cabinet chamber/cover module deployment and 3D high-survival optical anchor network integration (3.A).

---

### Appendix C: AI Assistance Disclosure
* **Original Architecture & Concepts:** deundeuni (Human) — Sole Inventor, overall system architecture, field motivation, and final decision-making authority.
* **Draft Generation:** Meta AI — Initial draft generation and structural scaffolding assistance.
* **Document Structuring & Expansion:** Gemini — Structural refinement, raceway/fire cabinet internal-external optics, AI governance, emergency power integration, and master reference framework expansion.
* **Review & Technical Validation:** Claude — Technical verification, nomenclature standardization, and legal defense framework validation.

*This disclosure is provided for transparency. AI prompts, internal chain-of-thought processing, and trade secret algorithms remain undisclosed. All final intellectual property rights belong exclusively to the human inventor (deundeuni / soma-moa).*
