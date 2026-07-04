<p align="center">
  <img src="https://img.shields.io/badge/AI%20Systems-LLM%20%7C%20Inference%20%7C%20Evaluation-blue?style=flat-square" />
  <img src="https://img.shields.io/badge/GPU%20ML-PyTorch%20%7C%20TensorFlow%20%7C%20CUDA-green?style=flat-square" />
  <img src="https://img.shields.io/badge/LLM%20Adaptation-LoRA%20%7C%20SFT%20%7C%20Unlearning-orange?style=flat-square" />
  <img src="https://img.shields.io/badge/RF%20Signal%20ML-IQ%20%7C%20SDR%20%7C%20Spectrograms-lightgrey?style=flat-square" />
  <img src="https://img.shields.io/badge/Production%20ML-Docker%20%7C%20CI%2FCD%20%7C%20Telemetry-blueviolet?style=flat-square" />
  <img src="https://img.shields.io/badge/Linux%20Systems-Python%20%7C%20C%2B%2B%20%7C%20Edge-critical?style=flat-square" />
</p>

# Jacob Ramey

Senior AI systems software engineer focused on production ML systems, LLM adaptation and evaluation, RF/sensor intelligence, and GPU-ready inference pipelines.

I build the software layer around models: data pipelines, preprocessing, training/evaluation harnesses, inference services, telemetry, containerized deployment, and Linux systems that make ML workloads repeatable outside a notebook.

## Current Focus

- LLM adaptation and evaluation: LoRA, QLoRA, SFT, activation-level unlearning, reasoning benchmarks
- AI inference systems: preprocessing, model execution, postprocessing, observability, reproducible deployment
- RF and sensor ML: IQ data, spectrograms, modulation recognition, SDR capture, signal-intelligence workflows
- GPU-ready experimentation: PyTorch, TensorFlow, CUDA-enabled environments, Docker, Apptainer, Slurm
- Production software: Python/C++ services, FastAPI, WebSocket streaming, CI/CD, Linux deployment

## Featured Work

### LLM Adaptation and Evaluation

**[masked-emotion-lora-benchmark](https://github.com/rameyjm7/masked-emotion-lora-benchmark)**  
Reproducible LoRA adaptation benchmark for masked-emotion reasoning across encoder and generative model families. Includes continuation training, centralized metrics, and comparison tables showing RoBERTa-large improving from a paper baseline near 0.377 AccV to 0.8304 AccV.

**[qwen-sft-reasoning-benchmark](https://github.com/rameyjm7/qwen-sft-reasoning-benchmark)**  
End-to-end supervised fine-tuning workflow for Qwen2.5-3B-Instruct using LLaMA-Factory, Hugging Face tooling, benchmark evaluation, and reasoning-task analysis.

**[llm-preference-unlearning](https://github.com/rameyjm7/llm-preference-unlearning)**  
Research engineering prototype for activation-guided masked LoRA, concept suppression, prompt perturbation analysis, Fisher/saliency profiling, and before/after behavior evaluation.

### RF, Sensor, and Applied ML Systems

**[rf-signal-intelligence](https://github.com/rameyjm7/rf-signal-intelligence)**  
GPU-ready RF/IQ machine-learning workspace for modulation recognition, radar waveform analysis, signal preprocessing, recurrent/CNN hybrid models, Docker/Apptainer environments, and benchmark artifacts across RML2016, RML2018, and DeepRadar2022.

**[sdr-shark](https://github.com/rameyjm7/sdr-shark)**  
Applied signal-intelligence platform with React UI, Python backend, SDR streaming, signal statistics, annotation tools, and a path toward ML-assisted RF classification.

**[rf-sentinel](https://github.com/rameyjm7/rf-sentinel)**  
Multi-protocol RF intelligence platform for passive discovery, normalized event processing, SDR gateway integration, Bluetooth/BLE/Zigbee/Sub-GHz plugins, dashboards, alerts, and reports.

### Data and ML Infrastructure

**[climate-trend-predictor](https://github.com/rameyjm7/climate-trend-predictor)**  
Kafka/S3/Airflow/TensorFlow data pipeline for time-series ML workflow experimentation, batch and stream ingestion, visualization, and model training.

**[multi-agent-market-intelligence-system](https://github.com/rameyjm7/multi-agent-market-intelligence-system)**  
Multi-agent intelligence workflow for structured research, document processing, and decision support.

## Technical Stack

Python, C++, PyTorch, TensorFlow, Hugging Face Transformers, LLaMA-Factory, ONNX, CUDA, OpenCV, FastAPI, Flask, React, Docker, Apptainer/Singularity, Slurm, Kafka, Airflow, AWS S3/EC2, Linux, SDR/SoapySDR, Jetson-class edge deployment.

## Contact

LinkedIn: https://www.linkedin.com/in/rameyjm  
Hugging Face: https://huggingface.co/rameyjm7
