# STACK-GFD: Stacked Ensemble Learning for Graph-Based Fraud Detection

## Overview
STACK-GFD is a two-level stacked ensemble combining four GNN-based 
anomaly detectors with an XGBoost meta-learner for fraud detection 
across multiple graph domains.

## Results
| Dataset     | AUC-ROC | Improvement |
|-------------|---------|-------------|
| Amazon      | 95.08%  | +19.78%     |
| DGraph-Fin  | 83.50%  | +40.81%     |
| MulDiGraph  | 99.70%  | +5.39%      |

## Requirements
See requirements.txt

## Datasets
- Amazon: Available via PyGOD BOND benchmark
- DGraph-Fin: https://dgraph.ecs.soton.ac.uk/
- MulDiGraph: http://xblock.pro/ethereum/

## How to Run
1. Install requirements: pip install -r requirements.txt
2. Run notebook
