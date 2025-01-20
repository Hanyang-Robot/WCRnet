# WCRnet
We propose a deep learning framework to estimate WCR using a cost-effective Frequency Domain Reflectometry (FDR) sensor and a deep model, **WCRnet**, which leverages residual connections. This repository provides TensorFlow-Keras code for training and testing WCRnet with deep learning on the FDR sensor data, which represents the physical and electrical properties of mortar.

## A deep learning framework to estimate water-to-cement ratio in mortar exploiting frequency domain reflectometry sensors
[Paper](https://www.sciencedirect.com/science/article/pii/S0950061825000431)

![Image](https://github.com/user-attachments/assets/fca91be4-2c98-4b59-ab77-9b2aed185d4f)

## 1. Installation
This implementation requries the follwing dependencies (Tested on Window 10):
+ Anaconda3
+ Other required libraries will be automatically installed in steps 1-2.

### 1-1. Clone the WCRnet repository
```c
git clone https://github.com/Hanyang-Robot/WCRnet.git
cd WCRnet/
```

### 1-2. Create the conda environment and install the requried packages.
```c
conda env create -f wc_ratio.yaml
conda activate wc_ratio
```

## 2. Run the Jupyter Notebook and feel free to use the implementation code!
+ If you want to use the WCRnet code, run "deep_learning_WCRnet.ipynb."
+ If you want to use the machine learning code, run "machine_learning_[model name].ipynb."
  
```c
jupyter notebook
```

**Note** if you use the WCRnet Framework in your work, please cite the following paper:
```c
@article{yu2025deep,
  title={A deep learning framework to estimate water-to-cement ratio in mortar exploiting frequency domain reflectometry sensors},
  author={Yu, Seunghwan and Park, Homin and Ko, Byungjin and Lee, Han-Seung and Park, Taejoon and Yoon, Jong-Wan},
  journal={Construction and Building Materials},
  volume={462},
  pages={139896},
  year={2025},
  publisher={Elsevier}
}
```
