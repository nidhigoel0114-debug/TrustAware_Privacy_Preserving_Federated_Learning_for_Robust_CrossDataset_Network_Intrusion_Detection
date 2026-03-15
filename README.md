**Trust-Aware Privacy-Preserving Federated Learning for Robust Cross-Dataset Network Intrusion Detection**
This project implements a Trust-Aware Privacy-Preserving Federated Learning framework for Network Intrusion Detection Systems (NIDS). The system enables multiple distributed clients to collaboratively train a global model without sharing raw data, ensuring data privacy and secure model aggregation.

The framework introduces a trust-based aggregation mechanism that evaluates the reliability of client updates using a trust score derived from accuracy contribution, update stability, and similarity to the global model. This helps reduce the impact of unreliable or malicious clients during federated training.

To further strengthen security and robustness, the model incorporates differential privacy, adversarial robustness testing, and cross-dataset evaluation. Experiments are conducted on multiple intrusion detection datasets including CICIDS2017, UNSW-NB15, and Bot-IoT, demonstrating strong generalization across heterogeneous network environments.

**Key features include:**

Federated Learning (FL): Enables collaborative model training across multiple clients while preserving local data privacy.

Trust-Weighted Aggregation (T-Krum): Reduces the impact of malicious or low-quality clients during model aggregation.

Differential Privacy (DP): Protects gradients and model updates during federated training.

Adversarial Training (FGSM): Improves robustness against evasion and adversarial attacks.

Zero-Trust Client Selection: Ensures only trustworthy clients participate in model updates.

Ledger-Auditable Architecture: Maintains transparency and traceability of training updates.

The proposed approach improves security, privacy, and robustness of collaborative intrusion detection systems while maintaining high detection accuracy across diverse network datasets.

**Goal**
To build a privacy-preserving, robust, and auditable federated IDS capable of detecting modern cyber threats such as ransomware, DoS attacks, and IoT-based intrusions across heterogeneous network environments.

**Outcomes of the project**
This project proposes SecureTrust-FL, a privacy-preserving federated intrusion detection system designed for collaborative cybersecurity environments. The framework combines Federated Learning (FL) with a zero-trust security approach, allowing multiple organizations to jointly train intrusion detection models without sharing raw network traffic data, thereby maintaining data privacy.

The system is evaluated using three widely used cybersecurity datasets: CICIDS2017, UNSW-NB15, and BoT-IoT. Experimental results show strong performance, achieving 98.6% accuracy and an F1-score close to 0.99, demonstrating that collaborative learning among heterogeneous clients improves intrusion detection capability and generalizes well across different network environments.

However, the study also identifies several challenges in federated IDS systems. These include reduced performance for minority attack classes, vulnerability to adversarial perturbations, strict privacy constraints affecting model performance, and non-IID data distribution across clients.

Despite these limitations, SecureTrust-FL demonstrates the effectiveness of combining federated learning with zero-trust security to build privacy-aware intrusion detection systems. Future work will focus on improving robustness against adversarial attacks, enhancing detection of minority attack classes using imbalance-aware learning, and supporting federated training under stronger privacy constraints.

**Dataset links**
1.CICIDS-2017: https://www.kaggle.com/datasets/cicdataset/cicids2017
2.UNSW-NB15: https://www.kaggle.com/datasets/mrwellsdavid/unsw-nb15
3.Bot-IoT:https://www.kaggle.com/datasets/gauravduttakiit/bot-iot


**Reference links**
1.CICIDS-2017: https://www.unb.ca/cic/datasets/ids-2017.html
2.UNSW-NB15: https://research.unsw.edu.au/projects/unsw-nb15-dataset
3.Bot-IoT:https://research.unsw.edu.au/projects/bot-iot-dataset

