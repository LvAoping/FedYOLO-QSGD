# FedYOLO-QSGD

**Status:** The source code for this repository is currently under organization. We will publish the complete code and documentation soon.

This repository aims to provide an end-to-end implementation of Federated Learning (FL) combined with quantization training techniques for object detection in vehicular environments.

## Overview

The project focuses on improving communication efficiency and privacy preservation in distributed object detection tasks. By integrating Federated Learning (FL) with model compression—specifically quantized stochastic gradient descent (QSGD)—we seek to optimize model training on edge devices. This approach addresses the following key challenges in vehicular networks:

- **Data Heterogeneity (Non-IID distributions):** Ensuring robust performance despite uneven and heterogeneous data distributions across participating clients (vehicles).
- **Communication Efficiency:** Reducing bandwidth usage and latency by transferring quantized updates rather than large, full-precision model parameters.

The chosen models are from the YOLO series, known for their efficiency and accuracy, making them suitable for resource-constrained edge devices. This repository will demonstrate how these models can be trained within an FL setting, evaluated using real-world vehicular datasets such as KITTI and ZOD, to highlight their performance in realistic, data-diverse scenarios.

## Key Features

- **Federated Learning Framework:** Utilizing the Flower framework for flexible and scalable FL training and evaluation.
- **Quantized SGD (QSGD):** Compressing gradients to enhance communication efficiency without significantly degrading model accuracy.
- **Object Detection Models (YOLOv8):** Efficient and accurate real-time detection optimized for vehicular edge applications.
- **Evaluation on Real-World Datasets:** Assessing model performance on KITTI and ZOD datasets to ensure relevance and robustness.

## Getting Started

**Note:** The full source code is still being prepared and will be available soon.
