# DAI — Decentralized Artificial Intelligence

This repository serves as a research hub for work on **Decentralized Artificial Intelligence (DAI)**, with emphasis on the intersection of artificial intelligence, federated and distributed learning, blockchain, trust, incentives, privacy, governance, and accountable decentralized systems.

The repository originally supported a systematic literature review and knowledge synthesis on blockchain-enabled decentralized AI. It is now being expanded to support a broader research program that includes evidence synthesis, conceptual frameworks, system models, experimental studies, reproducible research artifacts, and related publications.

## Research Scope

The broader DAI research program examines how intelligent systems can operate across distributed or decentralized environments while maintaining reliability, privacy, accountability, and appropriate incentives for participating entities.

Current and emerging research themes include:

* Decentralized and semi-decentralized artificial intelligence
* Federated and distributed learning
* Blockchain-enabled AI systems
* Trust and reputation mechanisms
* Incentive and penalty mechanisms
* Robust and adversarial federated learning
* Privacy-preserving AI
* Smart contracts and auditable enforcement
* Decentralized storage and verifiable research artifacts
* AI governance and accountability
* Systematic reviews and evidence synthesis
* Reproducibility and experimental evaluation of decentralized AI systems

## Research Areas

### 1. Decentralized AI Evidence Synthesis

The original work associated with this repository investigates the architectural, technological, and governance foundations of decentralized AI systems.

The systematic review addresses the following research questions:

* **RQ1:** What architectural patterns and core technologies enable Decentralized AI?
* **RQ2:** How are blockchain and smart contracts used to coordinate and govern these systems?
* **RQ3:** What are the primary application domains and benefits of DAI systems?
* **RQ4:** What are the open challenges, limitations, and opportunities for future research?

The repository includes the literature-review dataset and supporting scripts used to collect, organize, and process publication metadata.

### 2. Trustworthy and Incentive-Aware Federated Learning

A second research direction investigates how trust, contribution quality, and incentives can be incorporated into federated and semi-decentralized learning systems.

This work considers mechanisms such as:

* Dynamic trust evaluation
* Multi-factor contribution assessment
* Trust decay and recovery
* Participant admission, probation, and suspension
* Update screening
* Trust-weighted aggregation
* Robust aggregation under adversarial behavior
* Reward allocation
* Stake-backed penalties and slashing
* Auditable enforcement using blockchain and smart contracts

A dedicated implementation and reproducibility repository for this work is maintained separately:

**Trust and Incentive Mechanisms for Semi-Decentralized Federated Learning**
Repository: `csci-viu/trust-incentives-sdfl`

### 3. Blockchain and Auditable AI Infrastructure

The research program also examines the role of blockchain as an accountability and enforcement layer for decentralized AI.

Topics include:

* Smart-contract-based incentive execution
* Tamper-resistant recording of system events
* Compact on-chain commitments
* Off-chain model and experiment artifacts
* IPFS-based content-addressed storage
* Verification of rewards, penalties, and participant decisions
* Scalability and blockchain overhead

The objective is not to move AI computation onto the blockchain, but to study how decentralized ledgers can support transparent, verifiable, and accountable AI coordination.

### 4. Robustness, Security, and Adversarial Behaviour

Another major research theme examines decentralized learning under unreliable or adversarial participation.

Example behaviours include:

* Data or model poisoning
* Byzantine updates
* Sign-flipping and update scaling
* Random-noise attacks
* Free-riding
* Stale or low-effort submissions
* Strategic participation
* Client dropout and intermittent availability
* Collusion and coordinated attacks

Research in this area investigates how trust, screening, aggregation, and incentive mechanisms can jointly limit harmful participation while preserving useful contributions from heterogeneous clients.

### 5. Privacy and Governance

Although decentralized and federated approaches reduce the need to centralize raw data, they introduce new governance and privacy questions.

Relevant topics include:

* Privacy leakage from model updates
* Data and model accountability
* Participant transparency
* Governance of decentralized AI ecosystems
* Fairness in participant admission and rewards
* Auditability of automated decisions
* Responsible use of blockchain-based enforcement
* Complementary use of secure aggregation and differential privacy

## Repository Contents

The repository currently contains resources associated primarily with the systematic review and evidence-synthesis component of the research program.

### `Final_List.xlsx`

Contains the curated publication dataset used in the decentralized AI literature review.

### Python Scripts

The Python scripts support publication metadata extraction, cleaning, consolidation, and preparation.

Current scripts include:

* `importfromcrossref.py`
* `importfromseveral.py`
* `mendeleytoexcel.py`
* `review2.py`

These scripts were developed to assist with literature collection and metadata preparation from scholarly sources.

## Repository Evolution

The repository is being retained as the umbrella location for the broader DAI research program.

Substantial implementation projects may be maintained in dedicated repositories so that their experimental environments, code, configurations, results, and reproducibility materials remain clearly separated.

The intended organization is:

```text
dai
├── literature-review/
├── publications/
├── research-notes/
└── links to dedicated implementation repositories
```

Dedicated repositories may contain:

```text
src/
experiments/
configs/
contracts/
blockchain/
ipfs/
results/
figures/
docs/
```

This separation allows the `dai` repository to remain a high-level research hub while individual studies maintain focused and reproducible software artifacts.

## Publications

Research associated with this program includes work on decentralized AI, blockchain-enabled artificial intelligence, federated learning, trust, incentives, privacy, and decentralized governance.

Publication details and links will be maintained here as the research program develops.

### Systematic Review

The decentralized AI systematic review examines architectures, enabling technologies, blockchain coordination, application domains, governance mechanisms, and research gaps across decentralized AI systems.

### Trust-Based Federated Learning

Ongoing work investigates trust- and incentive-aware semi-decentralized federated learning, including dynamic trust evaluation, participant governance, robust aggregation, adversarial resilience, and blockchain-assisted enforcement.

## Reproducibility

Reproducibility is an important objective of this research program.

Where applicable, research artifacts may include:

* Source code
* Dataset-processing scripts
* Experimental configuration files
* Random seeds
* Simulation environments
* Attack definitions
* Model and training parameters
* Result files
* Analysis scripts
* Figures and tables
* Smart-contract implementations
* Blockchain deployment information

Dedicated implementation repositories will provide study-specific instructions for reproducing experimental results.

## Usage

Materials in this repository are primarily intended to support academic research and publication.

For the systematic-review component:

1. Refer to `Final_List.xlsx` for the curated literature dataset.
2. Use the accompanying Python scripts for metadata preparation and processing.
3. Consult the associated publication for the complete review methodology, inclusion criteria, and interpretation of results.

For newer experimental projects, refer to the corresponding dedicated repository.

## Research Group

This repository is maintained as part of computer science research activities at **Vancouver Island University (VIU), Canada**.

Research areas include decentralized artificial intelligence, trustworthy federated learning, blockchain-enabled AI, privacy, security, and AI governance.

## Collaboration

This repository is primarily maintained by the project's research team.

Research collaboration, replication studies, and academic inquiries may be considered where they align with the research program.

## Citation

If you use materials from this repository, please cite the corresponding publication associated with the specific dataset, code, or research artifact.

Publication-specific citation information will be added alongside each released research artifact.

A `CITATION.cff` file may also be provided for software and reproducibility releases.

## License

Licensing information for code, datasets, and research artifacts will be specified within the repository or within individual project repositories.

Unless explicitly stated otherwise, publication content remains subject to the copyright and licensing terms of the corresponding publisher.

## Contact

**Ajay Kumar Shrestha**
Department of Computer Science
Vancouver Island University
Nanaimo, British Columbia, Canada

Research interests: decentralized AI, federated learning, blockchain, trust and incentive mechanisms, privacy, security, and AI governance.
