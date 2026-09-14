# LAST-LIGHT — Specification for Auxiliary Guidance System Technical Revision History (VERSION_HISTORY.md Ver. 5.2 Final Completed Version)

* **Document Classification:** Technical Revision Control & Version Management Record
* **Original IP Holder:** deundeuni (Project: soma-moa)
* **Official Repository:** github.com/deundeuni/LAST-LIGHT | **Official Domain:** somamoa.ai.kr
* **Initial Conception Date:** 2026-07-30 / **Final Revision Date (v5.2):** 2026-09-14
* **Authoritative Language Notice:** The Korean original text (`version_history.ko.md`) serves as the authoritative legal and technical standard. English translations serve as secondary references. In cases of conflict, the Korean original text governs.
* **Document Hierarchy Notice:** This document functions as the detailed chronological log for Section 1 (Version History) of the primary technical specification (`README.ko.md` / `README.md`). While milestone entries align 1:1 with the master whitepaper, this revision history and citation-focused derivative document omits technical detail sections (Sections 4–6) and connects directly to fixed Sections 7 (Intellectual Property Safeguards) and 8 (References).

---

## 1. Key Revision Timeline

* **v1.0 (2026-07-30) — [Initial Concept] Initial visual anchoring concept formulation based on ISO 7010 always-on signage and guidance system framework establishment**
  * Formulated the core concept of utilizing building exit lights (ISO 7010 pictograms) as absolute reference points (ANCHORs) for mobile camera position calibration, establishing public and commercial auxiliary safety frameworks.

* **v2.0 ~ v3.0 (2026-08-30) — [Full-Stack & Infrastructure Integration] Full-stack layer architecture design, raceway anchoring, edge AI models, and self-healing multi-mesh failover**
  * Integrated 3-tier applied architecture (L0-L1-L2) aligned with master survival architecture (`chiplet-apu`); standardized defensive safety control terminology.
  * Specified multi-wavelength optical reception on underground parking raceways and defined input/output matrices for position estimation algorithms.
  * Verified initial concept date (2026-07-30); introduced on-device edge AI (sLLM/Edge AI) and established 100ms P2P N-Mesh zero-downtime failover mechanisms during communication blackouts.

* **v3.1 ~ v3.6 (2026-08-30) — [Master Reference & Multisensory Expansion] Independent research acknowledgement, sensor fusion master reference, fire cabinet anchors, and spatial audio/bone-conduction specifications**
  * Integrated independent research acknowledgement clause (0.8) and AI transparency disclosure (Appendix C).
  * Mandated emergency power interface requirements (under 2 hours to 24+ hours) and established master reference standards for IMU/Gyroscope/LiDAR sensor fusion zero-point calibration.
  * Specified 3D optical/RF/acoustic anchor placement utilizing indoor hydrant box surfaces and fireproof internal chambers.
  * Defined spatial audio, acoustic direction-of-arrival (DOA) extraction, and haptic orientation prompts for zero-visibility fire environments.

* **v3.7 (2026-08-31) — [Open Integration & Rapid Onboarding] Personal wearable integration, routine privacy isolation, 3-second onboarding, and legal liability disclaimers**
  * Fully integrated personal wearable interfaces (3.E), routine privacy isolation, 3-second passive QR / auto-discovery onboarding (3.F), and multisensory anchor evacuation architecture (3.G).
  * Generalized corporate/brand terminology and formalized legal disclaimers.

* **v3.8 (2026-08-31) — [Haptic Compass Paradigm] Establishment of 'Co-Survival Haptic Receiver' nomenclature and standard haptic compass protocol table**
  * Established the 'Co-Survival Haptic Receiver' nomenclature to overcome 100 dB siren noise, detailing speakerless public infrastructure deployment models.
  * Formulated the standard haptic compass protocol table (3.E) based on localized transducer contact points.

* **v3.9 (2026-09-01) — [Distributed Blackbox & Self-Evolution] Fire cabinet fireproof chamber distributed heat-resistant local blackbox telemetry and log-driven AI route self-evolution**
  * Specified distributed heat-resistant local blackboxes (3.H) storing recent 1–2 hour ring-buffer telemetry in fireproof chambers during network blackouts.
  * Integrated post-disaster forensic support mechanisms and log-driven AI self-evolution algorithms for dynamic rerouting.

* **v4.0 (2026-09-06) — [Upper Architecture Cross-Referencing] Interoperability alignment with ARCHITECTURE_STRATEGY, chiplet-apu, MAX-LIFE-ICE-BELT, and CWP mechanisms**
  * Applied cross-referencing patches linking the specification with universal survival architectures, APU controllers, marine armor, and CWP hardware mechanisms.

* **v4.1 (2026-09-06) — [Space/Orbital Infrastructure Expansion] Space station orbital module, microgravity smoke diffusion guidance, IVA/EVA spacesuit haptics, and form-factor agnostic stimulus expansion**
  * Extended 3D guidance to microgravity space environments, defining spacesuit inner lining haptic pads, wearable form factors (smart rings, bracelets, footwear), and diverse tactile stimuli (pressure, electrical, piezoelectric).

* **v4.2 (2026-09-07) — [Nomenclature Redefinition, Technical/Legal Refinement, and Document Unification] Official nomenclature redefinition, subsystem timescale separation, professional legal consultation guidance, and master repository alignment**
  * Officially redefined 'Co-Survival Haptic Receiver' to 'Co-Survival Bridge' to reflect expanded form factors and core philosophical purpose.
  * Defined explicit subsystem timescale separation (0.1s network/mesh isolation vs 0.1ms hardware APU E-Stop).
  * Added recommendations for professional patent attorney consultation regarding DPL licensing, Korean Patent Act Article 103 prior use defenses, and utility model filing strategies.

* **v4.3 ~ v4.7 (2026-09-09) — [Heterogeneous Multi-Device Expansion & Underground Telecom Subordinate Integration] Multi-device interoperability, Visual SLAM drift reset, small cell/DAS subordinate backhaul integration, and fire-rated infrastructure non-obviousness logic**
  * Established comprehensive software interoperability and 0.1s Graceful Fallback mechanisms for heterogeneous multi-devices (AR/MR smart glasses Visual HUD, smart rings, smartwatches, haptic vests).
  * Refined Visual SLAM Rapid Drift Reset timescale to calibrate cumulative IMU errors to zero within 100ms of capturing L0 anchor tags.
  * Integrated 5G/6G small cells and Distributed Antenna Systems (DAS) in underground/tunnel environments as auxiliary position fusion and backhaul paths while enforcing a strict offline-first hierarchy anchored to fixed infrastructure.
  * Formulated non-obviousness justification for utilizing statutory fire-rated structures (indoor hydrant boxes per NFPC standards) as absolute 0-point anchors and local blackbox memory receptacles.

* **v4.8 (2026-09-09) — [Structure First Principle, Master Survival Architecture Cross-Reference & AI Standardisation] Explicit 'Structure First' design principle, chiplet-apu Sec 0.2 cross-reference, and generalized AI tool disclosures**
  * Explicitly declared the spatial/topological 'Structure First' design principle in Section 0.2, prioritizing physical structures (pictograms, hydrant boxes, raceways) over sensor placement.
  * Cross-referenced Section 0.2 'Structure over Capacity' philosophy of the master survival architecture `chiplet-apu`.
  * Standardized Appendix C AI tool disclosures to abstract "Artificial Intelligence Tools (AI models)" without brand names to reinforce defensive prior art protection.

* **v4.9 (2026-09-14) — [Maritime Shipboard & Deep Underground Tunnel Anchor Coverage] Encompassed passenger/cruise ship cabins (IMO SOLAS LLL, fire-rated Bulkheads, Muster Stations) and deep underground tunnel anchors**
  * Encompassed IMO SOLAS Low Location Lighting (LLL), ship fire-rated bulkheads, and Muster Station signs as L0 anchor media, specifying lifejacket-embedded haptics and deep tunnel connection passage 0-point calibration mechanisms.
  * Reinforced brand-agnostic abstract AI computing tool definitions.

* **v5.0 (2026-09-14) — [Ecosystem Citation & Upper Architecture Synchronization] Updated repository names, account ownerships, and Zenodo DOIs across Section 8**
  * Unified ownership handle to `deundeuni`, corrected hyphenated repository name `MAX-LIFE-ICE-BELT`, and updated cross-references to the separated upper survival architecture `smart-system-multi-survival-architecture`.

* **v5.1 (2026-09-14) — [Real Zenodo DOI & deundeuni Account Correction Patch] Precision correction based on screenshot-verified DOIs**
  * Corrected all Zenodo DOI identifiers based on verified account screenshots (chiplet-apu: 22374987, CWP-Entry: 22683234, CWP-Rolling: 22373704, CWP-Battery-Swap: 22373538, CWP-Clamping: 22373722) and designated unissued repositories as 'Pending'.

* **v5.2 (2026-09-14) — [Appendix A Primary Repository Account deundeuni Alignment] Document-wide citation consistency completion**
  * Unified primary repository notation in Appendix A to `github.com/deundeuni/soma-moa`, matching header metadata and Section 8 to complete document-wide structural consistency.

---

## 2. Key Evolutionary Pillars

* **Structure First Principle & Infrastructure Anchoring:** Prioritizes topological placement of physical structures over sensor placement ('Structure First'). Evolved from ISO 7010 signs to underground raceways, fire-rated hydrant boxes, IMO SOLAS shipboard LLL/bulkheads, deep tunnel chambers, small cell/DAS subordinate backhauls, orbital modules, and IVA/EVA spacesuit linings.
* **System Survivability & Distributed Blackbox:** Built 3-tier architecture, P2P N-Mesh self-healing networks, emergency power linkage, fireproof local blackbox forensic telemetry within hydrant boxes and ship bulkheads, and offline-first fallback hierarchies for communication blackouts.
* **Artificial Intelligence & Self-Evolving Algorithms:** Implemented on-device edge AI (sLLM/Edge AI), Kalman filter/DOA offset calibration, confidence control checks, heterogeneous multi-device Graceful Fallback, and log-driven AI rerouting self-evolution algorithms.
* **User Interface & Co-Survival Bridge:** Developed single-purpose Co-Survival Bridges overcoming 100 dB noise, standard tactile haptic compass protocols, BYOD multi-device integration (AR glasses, smart rings, smartwatches, ship lifejacket receivers), and 3-second WebAR emergency onboarding.
* **Legal Framework, Prior Use Rights, and Generalized Defense:** Enforced DPL v1.0 licensing, Korean Patent Act Article 103 / 35 U.S.C. §273 prior use rights, patent attorney review recommendations, generalized AI tool definitions, and human conceiver (deundeuni) IP ownership assertions.

---

## 3. Legal Effect & Originality Notice

* **Authoritative Original Text Clause:** The Korean original version (`version_history.ko.md`) serves as the authoritative legal standard. In cases of translation ambiguity, the Korean text prevails.
* **Prior Art Timestamp Validity:** Revision dates and technical details in this history serve as defensive prior art evidence under Article 103 of the Korean Patent Act and 35 U.S.C. §273.

---

*(Note: As a standalone version history and defensive citation log, this document omits technical detail sections 4–6 of the main whitepaper—Dynamic Resource Management, Standard Utilization, and Future Applications—connecting directly to fixed Sections 7 [Practical Protection] and 8 [References] per whitepaper structure rules).*

---

## 7. Practical Protection & Legal Framework

### 7.1 Intellectual Property Safeguards & Defensive Publication
* The chronological revision history and milestone combinations detailed in this document are recognized as proprietary intellectual assets, serving as prior art grounds against third-party patent claims.
* Prior use rights are maintained under Article 103 of the Korean Patent Act and 35 U.S.C. §273 based on the initial conception and revision dates.

### 7.2 Defensive Licensing & Professional Review
* This document is published under DPL v1.0 (Defensive Patent License) terms. Any entity asserting patent infringement claims against the conceiver or ecosystem participants forfeits license rights immediately.
* Formal patent office filings, prior use right assertions, and utility model strategies are recommended to be reviewed by qualified patent attorneys.

---

## 8. References & Primary Source Clause

### 8.1 Linked Master Architectures & Repositories
* **Master Upper Survival Architecture:** GitHub - `deundeuni / smart-system-multi-survival-architecture` (Zenodo DOI: Pending)
* **Master Fault-Tolerant Survival Architecture:** GitHub - `deundeuni / chiplet-apu-multi-system-survival-architecture` (Zenodo DOI: 10.5281/zenodo.22374987 / `ARCHITECTURE_STRATEGY.md` embedded)
* **Linked Marine Armor:** GitHub - `deundeuni / MAX-LIFE-ICE-BELT` (Zenodo DOI: 10.5281/zenodo.22373686)
* **This Defensive Publication White Paper (LAST-LIGHT v5.2):** GitHub - `deundeuni / LAST-LIGHT` (Zenodo DOI: 10.5281/zenodo.22373189)
* **Linked CWP Hardware Repositories:**
  * GitHub - `deundeuni / CWP-Entry` (Zenodo DOI: 10.5281/zenodo.22683234)
  * GitHub - `deundeuni / CWP-Rolling-Self-Align-Battery-Swap-System` (Zenodo DOI: 10.5281/zenodo.22373704)
  * GitHub - `deundeuni / CWP-Battery-Swap` (Zenodo DOI: 10.5281/zenodo.22373538)
  * GitHub - `deundeuni / CWP-Clamping-Battery-Swap-System` (Zenodo DOI: 10.5281/zenodo.22373722)
* **Master Gateway & Brand:** `deundeuni / soma-moa` (Zenodo DOI: 10.5281/zenodo.22435773) | `somamoa.ai.kr` (Canonical Gateway)
* **International Standards & Specifications:** ISO 7010, ISO 16069, IMO SOLAS (International Convention for the Safety of Life at Sea), ISO 15370 (Low Location Lighting), Bluetooth SIG Auracast / LE Audio Specifications, UWB Standards, 3GPP Small Cell Specs, Korean Fire Safety Acts, National Fire Performance Codes (NFPC), Ship Safety Act.

### 8.2 Master Originality Clause
* The official authoritative reference for this specification and revision history is the Korean original text (`README.ko.md` / `version_history.ko.md`).
* All non-Korean translations serve reference purposes only; in the event of legal or technical interpretation disputes, the Korean text takes precedence.
