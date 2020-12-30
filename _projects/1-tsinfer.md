---
title: "Asynchronous Inference Pipeline APIs for Streaming Data Applications"
collection: projects
type: "Deep Learning"
permalink: /projects/tsinfer
link: https://github.com/alecgunny/tsinfer
---

Set of tools for building client-side inference pipelines for reading and preprocessing streaming data, then sending it via a gRPC inference request to a running [Triton Inference Server](https://github.com/triton-inference-server/) instance. Includes base class for building Bokeh-server based visualization applications for measuring throughput, latency, and model performance (in the sense of that overloaded word most akin to "accuracy").