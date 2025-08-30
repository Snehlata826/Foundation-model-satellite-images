# Foundation Model for Satellite Images (SAC)

## Overview
This project develops a foundation model for satellite imagery, focusing on Indian satellites like HRSAT, Cartosat, etc. It supports multi-task learning for land cover classification, object detection, etc.

## Objectives
1. Design and train a model using large-scale datasets.
2. Enable multi-task learning.
3. Improve generalization.
4. Provide an open-source framework.

## Scope
- Transformer-based architecture.
- Datasets: Optical, infrared, SAR from Indian sources.
- Evaluation on benchmarks.

## Methodologies
- Data collection and preprocessing.
- Model: ViT or hybrid CNN-transformer.
- Training: Self-supervised + fine-tuning.
- Evaluation: Metrics for tasks.

## Installation
pip install -r requirements.txt

## Usage
python scripts\train.py

## License
MIT
