# Lumoxic Benchmarks

Optimization results across popular architectures using [Lumoxic AI](https://lumoxicai.me). INT8 dynamic quantization + structured pruning.

## Image Classification

| Model | Original | Optimized | Compression | Speedup | Acc Delta |
|-------|----------|-----------|-------------|---------|-----------|
| ResNet-50 | 97.8 MB | 12.1 MB | 8.1x | 7.6x | -0.4% |
| EfficientNet-B0 | 20.4 MB | 5.1 MB | 4.0x | 3.2x | -0.3% |
| MobileNetV3 | 21.1 MB | 5.4 MB | 3.9x | 2.8x | -0.2% |

## NLP

| Model | Original | Optimized | Compression | Speedup | Acc Delta |
|-------|----------|-----------|-------------|---------|-----------|
| BERT-Base | 440 MB | 68 MB | 6.5x | 5.2x | -0.5% F1 |
| DistilBERT | 255 MB | 42 MB | 6.1x | 4.8x | -0.3% F1 |

## Object Detection

| Model | Original | Optimized | Compression | Speedup | Acc Delta |
|-------|----------|-----------|-------------|---------|-----------|
| YOLOv8-M | 52 MB | 8.4 MB | 6.2x | 5.6x | -0.6% mAP50 |
| YOLOv8-S | 22 MB | 4.1 MB | 5.4x | 4.1x | -0.4% mAP50 |

## Speech

| Model | Original | Optimized | Compression | Speedup | Acc Delta |
|-------|----------|-----------|-------------|---------|-----------|
| Whisper Small | 244 MB | 42 MB | 5.8x | 5.0x | +0.4% WER |
| Whisper Tiny | 72 MB | 14 MB | 5.1x | 4.2x | +0.3% WER |

## Energy

Average reduction: **83%** (Joules per inference).

CC BY 4.0. (c) 2026 Lumoxic AI.