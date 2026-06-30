# Quantization Research Dashboard

## Objective

Evaluate the impact of quantization on Llama-3.2-3B-Instruct.

### Quantization Methods
- FP16
- INT8
- INT4
- NF4

### Metrics
- VRAM Usage
- First Token Latency
- Throughput
- Perplexity
- BoolQ Accuracy

## Repository Structure

01_FP16_Benchmark.ipynb
→ Establish FP16 baseline.

02_INT8_Benchmark.ipynb
→ Evaluate 8-bit quantization.

03_INT4_Benchmark.ipynb
→ Evaluate 4-bit quantization.

04_NF4_Benchmark.ipynb
→ Evaluate NormalFloat4 quantization.

05_Quantization_Dashboard.ipynb
→ Compare all experiments and generate plots.
