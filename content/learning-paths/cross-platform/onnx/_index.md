---
title: ONNX in Action. Building, Optimizing, and Deploying Models on Arm64 and Mobile

minutes_to_complete: 120

who_is_this_for: This is an introductory topic for developers who are interested in creating, optimizing, and deploying machine learning models with ONNX. It is especially useful for those targeting Arm64-based devices (such as Raspberry Pi, mobile SoCs, or Android smartphones) and looking to run efficient inference at the edge.

learning_objectives:
   - Describe what ONNX is, and what it can offer in the ML ecosystem.
   - Build and export a simple neural network model in Python to ONNX format.
   - Perform inference and training using ONNX Runtime on Arm64.
   - Apply optimization techniques such as layer fusion to improve performance.
   - Deploy an optimized ONNX model inside an Android app.

prerequisites:
    - A development machine with Python 3.10+ installed.
    - Basic familiarity with PyTorch or TensorFlow.
    - An Arm64 device (e.g., Raspberry Pi or Android smartphone).
    - [Android Studio](https://developer.android.com/studio) installed for deployment testing.

author: Dawid Borycki

### Tags
skilllevels: Introductory
subjects: Machine Learning, Edge AI
armips:
    - Cortex-A
    - Neoverse
operatingsystems:
    - Windows
    - Linux
    - macOS
tools_software_languages:
    - Python
    - PyTorch
    - TensorFlow
    - ONNX
    - ONNX Runtime
    - Android
    - Android Studio
    - Kotlin
    - Java

further_reading:
    - resource:
        title: ONNX
        link: https://onnx.ai
        type: documentation
    - resource:
        title: ONNX Runtime
        link: https://onnxruntime.ai
        type: documentation
    - resource:
        title: Getting Started with ONNX Runtime on Mobile
        link: https://onnxruntime.ai/docs/tutorials/mobile
        type: tutorial
    - resource:
        title: Optimizing Models with ONNX Runtime
        link: https://onnxruntime.ai/docs/performance/model-optimizations.html
        type: documentation

### FIXED, DO NOT MODIFY
# ================================================================================
weight: 1                       # _index.md always has weight of 1 to order correctly
layout: "learningpathall"       # All files under learning paths have this same wrapper
learning_path_main_page: "yes"  # This should be surfaced when looking for related content. Only set for _index.md of learning path content.
---
