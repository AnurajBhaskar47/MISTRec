# MISTRec: Multi-modal Interest-aware Sequence Transformer for Recommendation

## 1. Introduction
MISTRec is a state-of-the-art recommendation system that leverages multi-modal data to capture complex user interests over time. By using pre-training and fine-tuning strategies, MISTRec improves the accuracy of personalized recommendations across diverse domains such as e-commerce, video streaming, and social media.

## 2. Preparation

```bash
git clone https://github.com/AnurajBhaska47/MISTRec.git
cd MISTRec/
```

### 2.1 Requirements

- cuda 11.7
- python 3.7.8
- pytorch 1.13.1
- numpy 1.21.6
- cupy 11.6.0
- tqdm 4.64.1

### 2.2 Data Preparation

Before running the code, we need to make sure that everything needed is ready. The working directory is expected to be organized as below:

## 3. Pre-training

To pre-train the model for 100 epochs, run the following command in a multi-GPU environment:

```python
# an example: pre-training on 4 GPUs
CUDA_VISIBLE_DEVICES="0,1,2,3" python ddp_pretrain.py
```
