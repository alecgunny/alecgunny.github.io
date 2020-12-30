---
title: "Exporting DL Models to Triton and Accelerating for Inference"
collection: projects
type: "Deep Learning"
permalink: /projects/exportlib
link: https://github.com/alecgunny/exportlib
---

Simplified APIs for taking a trained PyTorch `nn.Module` and exporting it for inference on the Triton Inference Server as an ONNX runtime. Includes tools for converting ONNX representation to an accelerated [TensorRT](https://developer.nvidia.com/tensorrt) executable engine for low latency GPU inference.