CAN Intrusion Detection System
This project is an attempt to detect impersonation attacks on Controller Area Network (CAN) bus data using machine learning. We train a Random Forest Classifier on labeled CAN messages—some from normal driving conditions and others from simulated attacks.

Dataset
We used two CSV datasets:

attack_free_sample.csv – contains normal (benign) CAN messages.

Impersonation_attack_dataset_sample.csv – contains CAN messages captured during an impersonation attack.

Each message includes:

Timestamp

CAN ID

DLC (Data Length Code)

DATA[0] through DATA[7] (CAN message payload bytes)

Label (0 = Normal, 1 = Attack)
