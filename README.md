# Benchmarking and Fine-tuning Computer Vision Models for Object Detection Tasks

This repository contains the research code for Benchmarking and Fine-tuning Computer Vision Models for Object Detection Tasks

## Abstract

Object detection is a fundamental task in computer vision with applications across domains such as autonomous systems, robotics, environmental monitoring, and defense. While modern object detection models achieve strong performance on large benchmark datasets such as COCO, their effectiveness often degrades when applied to domain-specific environments with different visual characteristics. This paper benchmarks several computer vision architectures and fine-tuning strategies for object detection across diverse datasets to better understand how model design and training approaches influence performance on specialized tasks.

We evaluate both zero-shot transfer and domain-adapted fine-tuning using datasets from multiple operational contexts, including underwater imagery and tactical surveillance-style data. Our analysis compares detection accuracy, classification performance, and generalization across models trained under different configurations. The results demonstrate that domain-specific fine-tuning significantly improves performance compared to zero-shot deployment. Among the evaluated architectures, the YOLOv8 model consistently achieved the highest classification and detection accuracy after fine-tuning, indicating strong suitability for real-world object detection tasks in specialized environments.

These findings highlight the importance of targeted model adaptation and provide practical guidance for deploying object detection systems in field settings where data distributions differ from standard benchmark datasets.
