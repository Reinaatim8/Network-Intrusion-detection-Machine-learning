# Network Intrusion Detection System (IDS)
### Group I using the UNSW-NB15 Dataset
GROUP I ML Project Video link - https://drive.google.com/file/d/1Dhs2QBRftTRcuaThXZpzFcyfc8KLmXNz/view?usp=drive_link

A dual-phase Machine Learning Network Intrusion Detection System that combines supervised and unsupervised models to detect malicious network traffic.
## Project Overview
This project implements a complete Network Intrusion Detection(IDS) using the UNSW-NB15 dataset, covering two phases:
- **Supervised Phase** — Decision Tree, Random Forest
- **Unsupervised Phase** — Isolation Forest, DBSCAN, Autoencoder
 
 ### Models/Methods Used
| Model/Method | Phase | Type | Justification |
|---|---|---|---|
| **Decision Tree** | Supervised | Tree-based | Interpretable baseline; reveals human-readable detection rules |
| **Random Forest** | Supervised | Ensemble | High accuracy; provides feature importance |
| **Isolation Forest** | Unsupervised | Ensemble / Tree-based | Scalable, handles high-dimensional traffic data |
| **DBSCAN** | Unsupervised | Density-based Clustering | Detects anomalies as low-density outliers |
| **Autoencoder** | Unsupervised | Deep Learning | Learns compressed normal traffic; flags high reconstruction error |

## Requirements
- Python 3.12.8+
- Jupyter Notebook or any other equivalent
- pandas, numpy, matplotlib, seaborn
- scikit-learn
- tensorflow / keras
