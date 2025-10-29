# SAM_Uranium_Analyzer-
A desktop application using Grounding DINO and SAM (ViT-B) for zero-shot detection and color analysis of uranium glass objects.
# CREDITS AND ATTRIBUTION

This project, "SAM Uranium Glass Analyzer," is proprietary software authored by Fluorescent_Finds ©2025.

Its core functionality for open-world object segmentation and detection relies on the foundational work of several excellent open-source projects. We adhere to the terms of their respective licenses.

## 1. Foundational Models

### A. Segment Anything Model (SAM)
* **Purpose:** Core segmentation engine for converting bounding boxes/points into pixel masks.
* **Organization:** Meta AI
* **License:** **Apache License 2.0**. We distribute the Segment Anything Model and associated code under this permissive license.
* **Citation:** This component is based on the following research paper:
```bibtex
@article{kirillov2023segany,
  title={Segment Anything},
  author={Kirillov, Alexander and Mintun, Eric and Ravi, Nikhila and Mao, Hanzi, ...},
  journal={arXiv:2304.02643},
  year={2023}
}

### B. Grounding DINO
* **Purpose:** Zero-shot object detection, responsible for turning the user's text prompt into initial bounding box prompts.
* **Authors/Organization:** IDEA-Research, Shilong Liu, et al.
* **License:** **Apache License 2.0**.
* **Citation:** This component is based on the following research paper:
```bibtex
@article{liu2023grounding,
  title={Grounding DINO: Marrying DINO with Grounded Pre-Training for Open-Set Object Detection},
  author={Shilong Liu and Zhaoyang Zeng and Tianhe Ren and Feng Li and Hao Zhang and Yang, Jie and Li, Chunyuan and Yang, Jianwei and Hang Su and Jun Zhu and Lei Zhang},
  journal={arXiv:2303.05499},
  year={2023}
}

## 2. Core Dependencies

This project uses the following major libraries under their respective licenses:

* **PyTorch:** BSD-style license.
* **OpenCV (cv2):** Apache 2.0 License.
* **Hugging Face Transformers:** Apache 2.0 License (used for the language model/tokenizer).
