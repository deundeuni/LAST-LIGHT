LAST-LIGHT — Technical Specification Revision 

License: See LICENSE file (CC BY 4.0 & DPL v1.0)

History for Auxiliary Guidance System Utilizing Permanently Illuminated Standard Signs, Internal/External Fire Terminal Boxes, Smart Raceways, and Multisensory Acoustic/Wearable Infrastructure (Ver. 3.7)
 * Document Classification: Technical Specification Revision History and Version Control Record (Defensive Publication / Prior Art)
 * Original Intellectual Property (IP) Holder: soma-moa (Conceiver: deundeuni)
 * Official Repository: github.com/soma-moa | Official Domain: somamoa.ai.kr
 * Date of Initial Conception: July 30, 2026 / Date of Final Revision: August 31, 2026
 * Original Authority Notice: The Korean text of this document serves as the sole legally and technically authoritative original. English translations are provided strictly for reference and convenience; in the event of any interpretive variance, the Korean original shall prevail.
 * Major Revisions and Integration History by Version
 * v1.0 (July 30, 2026) — [Initial Conception] Established the foundational concept for visual anchoring using ISO 7010 permanently illuminated signs and formulated the baseline auxiliary guidance system specification.
   * Defined the core mechanism of leveraging indoor emergency exit signs (ISO 7010 pictograms) as absolute reference points (ANCHORs) for position calibration across mobile devices and computer vision cameras.
 * v1.5 (August 1, 2026) — [Structural Refinement] Restructured the specification framework to align with both public safety regulations and commercial emergency lighting applications.
   * Refined the system architecture to ensure seamless interoperability with existing fire protection infrastructure.
 * v2.0 (August 30, 2026) — [Full-Stack Integration] Restored the founding motivation ("Auxiliary Evacuation Value of Exit Signs") and integrated a 3-Tier Full-Stack Application Layer (L0–L1–L2) aligned with the Chiplet-APU Survival Architecture v2.6.
 * v2.5 (August 30, 2026) — [Infrastructure Expansion] Integrated anchoring specifications for underground parking facilities, utility raceways, and cable trays.
   * Added reception protocols for multi-wavelength optical modules (visible green and firefighting-grade IR/fluorescent/white) deployed at uniform intervals along overhead raceways.
 * v2.6 (August 30, 2026) — [Terminology Standardization] Replaced metaphorical terminology with standardized engineering terms.
   * Formalized Section 4 under the technical heading "Dynamic Resource Management & Defensive Safety Control Specification."
 * v2.7 (August 30, 2026) — [Algorithm Formalization] Explicitly defined the input, processing, and output relationships of the ESTIMATION calibration algorithm.
   * Detailed system dependencies to ensure technical reproducibility while safeguarding core algorithmic weights and parameters as offline trade secrets.
 * v2.8 (August 30, 2026) — [Philosophy & Timestamp] Officially recorded the initial conception date (July 30, 2026) and incorporated the founding humanistic principles focused on protecting evacuees and emergency responders.
 * v2.9 (August 30, 2026) — [AI Governance] Defined an overarching AI framework and established the necessity of lightweight, on-device models (sLLM / Edge AI).
   * Specified the deployment of embedded AI engines (sLLM, Small Vision-Audio Models, NPU firmware) to guarantee autonomous, local operation during total communication blackout scenarios.
 * v3.0 (August 30, 2026) — [System Resilience] Integrated a distributed self-healing multi-mesh network and zero-downtime fail-over architecture.
   * Established a peer-to-peer N-Mesh topology enabling adjacent nodes to autonomously assume compute and control responsibilities within 100ms of any node failure or physical destruction.
 * v3.1 (August 30, 2026) — [Prior Research & AI Disclosure] Incorporated an explicit acknowledgment of independent prior research (Section 0.8) and added an AI Assistance Disclosure (Appendix C) detailing collaboration with Gemini and Claude.
 * v3.2 (August 30, 2026) — [Power Specifications] Mandated integration with facility emergency power systems and specified comprehensive runtime operational parameters.
   * Mandated fallback integration with emergency power generators, UPS systems, and local secondary batteries, defining operational coverage spans from under 2 hours to beyond 24 continuous hours.
 * v3.3 (August 30, 2026) — [Master Reference Framework] Declared the zero-point calibration framework as the master reference for multi-sensor fusion and strengthened equivalent-workaround defense clauses (Section 7.3).
 * v3.4 (August 30, 2026) — [Fire Cabinet Anchor] Integrated optical anchoring specifications for indoor fire hydrant cabinets, fire alarm terminal boxes, and electrical control panel indicators.
   * Established internal and external enclosures of floor-level fire terminal boxes as fixed visual reference anchors.
 * v3.5 (August 30, 2026) — [3D Anchor Mesh] Defined high-survivability module placement standards within internal fire cabinet chambers to construct a 3D optical/RF/acoustic anchor mesh.
 * v3.6 (August 30, 2026) — [Multisensory Expansion] Fully integrated directional/spatial audio anchors, microphone arrays, and bone-conduction tactile interfaces for zero-visibility smoke environments.
   * Added spatial audio signal processing, Direction of Arrival (DOA) estimation, and haptic bone-conduction feedback mechanisms for navigation when vision is completely impaired.
 * v3.7 (August 31, 2026) — [Final Specification] Fully integrated personal open-ear bone-conduction wearable interfaces (Section 3.E), normal-state privacy isolation with 3-second rapid onboarding (Section 3.F), and structural multi-anchor guidance concepts (Section 3.G).
   * Generalized vendor-specific trademarks into neutral industry standards and finalized comprehensive legal disclaimers and liability limitations.
 * Summary of Revision Metrics and Categories
 * Total Revision Iterations: 17 versions (v1.0 through v3.7)
 * Primary Revision Scope:
   * Infrastructure & Sensor Fusion Expansion: v1.0, v2.5, v3.3, v3.4, v3.5, v3.6
   * System Survivability & Mesh Networking: v2.0, v3.0, v3.2
   * Artificial Intelligence & Algorithmic Governance: v2.7, v2.9, v3.1
   * User & Wearable Interfaces: v3.6, v3.7
   * Legal Defensibility & Scope Protection: v2.6, v2.8, v3.1, v3.7
 * Legal Effect and Original Authority Clause
 * Original Authority Clause: The Korean original text of this revision history serves as the primary legally and technically binding version (Original Authority). In the event of any discrepancies or ambiguities in translated versions, the Korean text shall take precedence.
 * Prior Art Timestamp Validity: The revision dates and technical disclosures documented herein constitute written prior art evidence pursuant to Article 103 of the Korean Patent Act and 35 U.S.C. §273 of the United States Code.
