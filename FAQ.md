# ❓ Technical FAQ

### Can’t an AI just learn to fake the lens pattern?
AI excels at replicating patterns it has been trained on. Because each TruthHorizon lens is physically unique—created by chaotic, non-linear processes like resin bubbles or fiber distribution—an attacker would need the "training set" of *your specific lens* to fake it. Replicating the 3D refraction of light through random physical matter is a physical barrier that software alone cannot bridge.

### What if my lens gets scratched? Won't that change the pattern?
The protocol uses **Fuzzy Matching** for verification. The software focuses on the deep, internal impurities of the lens (the "core constellation") which are typically protected within the resin. Surface scratches are treated as external "noise." As long as the core signature remains identifiable above a specific threshold (e.g., 80%), the media is verified. If the damage is too severe and obstructs the signature, the app will prompt you to "retire" the old lens and register a new one.

### How do you handle illegal content if the blockchain is immutable?
We follow the principle of **Separation of Attestation and Distribution**:
1.  **The Hash (On-Chain):** The blockchain only stores the mathematical hash (the fingerprint). This contains no visual data and is essential for legal and historical integrity.
2.  **The Content (Off-Chain):** The actual video files are stored on decentralized or distributed servers (like IPFS).
3.  **Community Moderation:** TruthHorizon implements a community-governed "Blacklist." If content violates international laws, the community can vote to stop hosting the file and block it from appearing in the official TruthHorizon viewer. The proof remains on the ledger for legal purposes, but the harmful content is removed from public view.

### Why do we need a Blockchain?
To eliminate the "Gatekeeper." A central server is a single point of failure and a target for censorship. If a government or corporation wants a video deleted, they could pressure a central authority. The blockchain ensures that once a moment is signed and anchored, it is mathematically impossible to erase or alter the *record* of that truth, even by the TruthHorizon founders.

### Is this only for professional journalists?
No. TruthHorizon is built for humanity. Whether you are documenting a protest, a natural disaster, or a local council meeting, the goal is to empower every individual to say: *"I was there, this is what I saw, and here is the physical proof."*

### Is the hardware expensive?
Our goal is "Garage-Level Manufacturing." By using 3D printing and common resins, a functional "Truth Lens" should cost less than $5 to produce. Truth should be a public utility, not a luxury.