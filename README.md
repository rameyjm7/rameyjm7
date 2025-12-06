<p align="center">

  <!-- Row 1: Core Languages & ML Frameworks -->
  <img src="https://img.shields.io/badge/Python-ML%20%7C%20Systems-blue?style=flat-square" />
  <img src="https://img.shields.io/badge/C%2B%2B-Embedded%20%7C%20HPC-green?style=flat-square" />
  <img src="https://img.shields.io/badge/Rust-Systems%20Programming-orange?style=flat-square" />
  <img src="https://img.shields.io/badge/PyTorch-Deep%20Learning-red?style=flat-square" />
  <img src="https://img.shields.io/badge/TensorFlow-Training%20Pipelines-orange?style=flat-square" />
  <img src="https://img.shields.io/badge/HuggingFace-Transformers-yellow?style=flat-square" />

  <br/>

  <!-- Row 2: LLMs / CV / Signal Processing -->
  <img src="https://img.shields.io/badge/LLMs-Qwen%20%7C%20LLaMA%20%7C%20Mistral-blueviolet?style=flat-square" />
  <img src="https://img.shields.io/badge/Activation--Level%20Unlearning-LoRA-critical?style=flat-square" />
  <img src="https://img.shields.io/badge/Computer%20Vision-YOLOv5%20%7C%20YOLOv8%20%7C%20YOLOv10-brightgreen?style=flat-square" />
  <img src="https://img.shields.io/badge/RF%20Signal%20ML-CNN--BiLSTM%20%7C%20Transformers-lightgrey?style=flat-square" />
  <img src="https://img.shields.io/badge/OCR-EasyOCR%20%7C%20Tesseract-critical?style=flat-square" />
  <img src="https://img.shields.io/badge/ONNX-Export%20%7C%20Runtime%20%7C%20Quantization-9cf?style=flat-square" />
  <img src="https://img.shields.io/badge/Model%20Serving-CUDA%20%7C%20NPU%20%7C%20Edge-green?style=flat-square" />

  <br/>

  <!-- Row 3: ML Infra / Feature Engineering -->
  <img src="https://img.shields.io/badge/Feature%20Engineering-Online%20%7C%20Offline-important?style=flat-square" />
  <img src="https://img.shields.io/badge/Feature%20Stores-Training%20%7C%20Inference-red?style=flat-square" />
  <img src="https://img.shields.io/badge/Vector%20Search-FAISS%20%7C%20Milvus-blue?style=flat-square" />
  <img src="https://img.shields.io/badge/Kafka-Event%20Streaming-black?style=flat-square" />
  <img src="https://img.shields.io/badge/Airflow-Orchestration%20%7C%20Pipelines-orange?style=flat-square" />

  <br/>

  <!-- Row 4: Distributed Systems / Deployment -->
  <img src="https://img.shields.io/badge/Kubernetes-Orchestration-326ce5?style=flat-square" />
  <img src="https://img.shields.io/badge/Docker-Containers%20%7C%20Microservices-blue?style=flat-square" />
  <img src="https://img.shields.io/badge/Apptainer%2FSingularity-HPC%20Clusters-brightgreen?style=flat-square" />
  <img src="https://img.shields.io/badge/Slurm-Distributed%20Training-orange?style=flat-square" />
  <img src="https://img.shields.io/badge/AWS-S3%20%7C%20EC2%20%7C%20IoT%20Core-ff9900?style=flat-square" />

  <br/>

  <!-- Row 5: Embedded / Edge AI -->
  <img src="https://img.shields.io/badge/NVIDIA%20Jetson-Nano%20%7C%20Xavier%20%7C%20Orin-green?style=flat-square" />
  <img src="https://img.shields.io/badge/Rockchip-RV1106G%20NPU%20%7C%20ONNX%20Runtime-blue?style=flat-square" />
  <img src="https://img.shields.io/badge/Buildroot%20%7C%20Yocto-Embedded%20Linux-lightgrey?style=flat-square" />
  <img src="https://img.shields.io/badge/CUDA%20%2F%20VPI-Accelerated%20CV-brightgreen?style=flat-square" />

</p>



# Jacob Ramey

Machine learning engineer focusing on LLM fine-tuning, computer vision, and RF signal classification.  
Building end-to-end systems from data engineering to model deployment.

---

## Overview

I work on applied machine learning across large language models, deep computer vision systems, and wireless signal classification.  
My work spans the full development lifecycle, including dataset ingestion, GPU-accelerated training, model optimization, and deployment to both cloud and edge devices.

I maintain a strong focus on reproducibility, containerization, and scalable experimentation using HPC clusters, CUDA-enabled systems, and distributed training tools.

---

## Technical Focus Areas

### Large Language Models
- Supervised Fine-Tuning (SFT) of Qwen, LLaMA, and other transformer models  
- Activation-level unlearning and alignment research  
- LoRA, QLoRA, 4-bit/8-bit quantization  
- RAG systems, evaluation pipelines, and benchmarking  
- Model deployment using FastAPI, Gradio, and containerized inference

### Computer Vision
- YOLOv8 and YOLOv10 object detection  
- Parking detection, LPR (license plate recognition), multi-object tracking  
- Real-time inference pipelines for edge and cloud environments  
- Dataset creation, annotation, and evaluation tooling

### Wireless Signal ML
- RF/IQ dataset modeling (modulation recognition, radar signal classification)  
- LSTM, CNN-BiLSTM, and transformer-based architectures  
- Spectrogram generation and signal preprocessing  
- Applied DSP and feature extraction for ML systems

### ML Systems and Infrastructure
- Distributed GPU training on HPC clusters (Slurm, A100/H100 nodes)  
- Apptainer/Singularity, Docker, and reproducible environments  
- Data engineering with Kafka, S3, Airflow, and Python pipelines  
- Edge deployment on NVIDIA Jetson platforms

---

## Selected Projects

### LLM Preference Unlearning
Research prototype demonstrating activation-level feature removal to improve downstream alignment and robustness in large language models.  
Includes training scripts, evaluation tools, and an extensible experimentation framework.

Repository:  
https://github.com/rameyjm7/llm-preference-unlearning

---

### SFT Training for Qwen and LLaMA
End-to-end training pipeline for supervised fine-tuning of large language models.  
Includes quantization, LoRA integration, evaluation metrics, and reproducible experiment setup.

Repository:  
https://github.com/rameyjm7/SFT-Training-LLM

---

### Parking Detector and LPR
A complete computer vision system for detecting available parking spaces and performing license plate recognition.  
Implements YOLO detection, classical OCR, data preprocessing, and evaluation.

Repository:  
https://github.com/rameyjm7/parking-detector-lpr

---

### Wireless Signal Classification
Machine learning models for modulation recognition and RF/IQ signal classification.  
Includes LSTM/BiLSTM baselines, spectrogram generation, and preprocessing pipelines.

Repository:  
https://github.com/rameyjm7/ML-wireless-signal-classification

---

### Climate Trend Predictor
Full data-engineering and ML workflow using Kafka, AWS S3, TensorFlow, and visualization tools.  
Demonstrates end-to-end pipeline construction and cloud deployment.

Repository:  
https://github.com/rameyjm7/climate-trend-predictor

---

## Tools and Technologies

- Python, PyTorch, TensorFlow, NumPy, SciPy  
- Transformers, Hugging Face ecosystem  
- CUDA, CUDNN, distributed GPU workflows  
- Slurm, Apptainer/Singularity, Docker  
- Airflow, Kafka, AWS (EC2, S3)  
- OpenCV, YOLO, ONNX  
- Bash, Linux systems engineering  
- NVIDIA Jetson and embedded deployment

---

## Contact

Email: rameyjm7@gmail.com  
LinkedIn: https://www.linkedin.com/in/rameyjm  
Kaggle: https://www.kaggle.com/jacobramey  
Hugging Face: https://huggingface.co/rameyjm7


