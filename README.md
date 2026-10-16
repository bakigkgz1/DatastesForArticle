# Task-Dependent Reliability of Compute-in-Memory Accelerators

Layer-wise Mixed-Precision ADC Allocation for Deep-Learning Medical Image
Classification at the Edge.

**Author:** Baki Gokgoz, Gumushane University, Department of Computer Technologies,
Torul Vocational School. ORCID: 0000-0001-8166-6282.

This repository hosts the data tables supporting the manuscript. The study is
simulation-based and fully reproducible on public datasets (MedMNIST, CIFAR-10)
using a circuit-level, hardware-aware simulation framework for compute-in-memory
(CIM) accelerators. A VGG8 network is evaluated under 8-bit WAGE quantization,
sweeping analog-to-digital converter (ADC) precision and layer-wise
mixed-precision ADC allocation.

## Contents

| File | Description |
|------|-------------|
| `data/table1_auc_adc.csv`                  | AUC vs. ADC precision across tasks |
| `data/table2_variation_pneumonia.csv`      | Device-variation sweep (PneumoniaMNIST) |
| `data/table3_layer_ablation_pneumonia.csv` | Leave-one-low layer ablation (PneumoniaMNIST) |
| `data/table4_mixed_adc_pneumonia.csv`      | Layer-wise mixed-precision ADC (PneumoniaMNIST) |
| `data/table5_cross_dataset_mixed_adc.csv`  | Mixed-precision ADC across datasets |
| `data/table6_hw_cost_adc.csv`              | Hardware cost vs. ADC precision |

## Datasets

MedMNIST (PneumoniaMNIST, DermaMNIST, BloodMNIST, RetinaMNIST) and CIFAR-10 are
publicly available; no private or clinical data are included here.
