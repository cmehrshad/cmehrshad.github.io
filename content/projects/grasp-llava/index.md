---
title: Grasp-LLaVA
date: 2023-10-26
authors:
  - admin
links:
  - type: site
    url: "" #https://github.com/pandas-dev/pandas
tags:
  - llm
  - vision
  - ml-systems
---

## Advancing Robust and Generalizable Prosthetic Hand Control

Next-generation prosthetic hand control requires models that can handle real-world variability, not just controlled lab conditions. Existing datasets include a limited number of objects, while real users encounter an infinite variety in daily life. As a result, current grasp models struggle with unseen objects, reducing reliability and user independence.

### Key Contributions

**1. Semantic Projection**  
I define *semantic projection* as a model’s ability to generalize to unseen object types. Conventional models like YOLO achieve around **80% accuracy** in training but drop to **15%** on new objects, revealing the need for semantically grounded grasp estimation.

**2. Grasp-LLaVA**  
I propose **Grasp-LLaVA**, a Grasp Vision-Language Model (GVLM) that uses multimodal reasoning to infer suitable grasp types from an object’s physical and semantic attributes. Grasp-LLaVA achieves **50.2% accuracy** on unseen object types, outperforming a state-of-the-art grasp estimation model (**36.7%**).

**3. Hybrid Grasp Network (HGN)**  
To bridge the gap between performance and latency, I developed **HGN**, a hybrid edge–cloud architecture for grasp inference. With dynamic confidence calibration, HGN switches between edge and cloud computation as needed, improving generalization accuracy by **5.6% (to 42.3%)** and achieving a **3.5× speedup**.  
On real-world object mixes, HGN reaches **86% average accuracy**—a **12.2% gain** over edge-only systems—and runs **2.2× faster** than Grasp-LLaVA alone.

---

**Skills:** PyTorch · LLaVA · Vision-Language Models (VLM) · Large Language Models (LLM) · LoRA  

**Publications:** Accepted at **CODES+ISSS 2025** and **AIRC 2025**

