# NVIDIA Triton Inference Server Organization
[NVIDIA Triton Inference Server](https://github.com/triton-inference-server/server)
provides a cloud and edge inferencing solution optimized for both CPUs and GPUs.

This top level GitHub organization host repositories for officially supported 
backends, including [TensorRT](tensorrt_backend), [TensorFlow](tensorflow_backend), 
[PyTorch](pytorch_backend), [Python](python_backend), 
[ONNX Runtime](onnxruntime_backend), and [OpenVino](openvino_backend). The
organization also hosts several popular Triton tools, including:

* [Model Analyzer](https://github.com/triton-inference-server/model_analyzer):
A tool to analyze the runtime performance of model and provide an optimized 
model configuration for Triton Inference Server.

* [Model Navigator](https://github.com/triton-inference-server/model_navigator):
a tool that provides the ability to automate the process of moving model from source to optimal format and configuration for deployment on Triton Inference Server.

## Getting Started
To learn about NVIDIA Triton Inference Server, refer to the 
[Triton developer page](https://developer.nvidia.com/nvidia-triton-inference-server) 
and read our [Quickstart Guide](server/blob/main/docs/quickstart.md). Official 
Triton Docker containers are available from [NVIDIA NGC](https://catalog.ngc.nvidia.com/orgs/nvidia/containers/tritonserver).

## Product Documentation
User documentation on Triton features, APIs, and architecture is located in the [server
documents on GitHub](server/tree/main/docs). A table of contents for the User 
documentation is located in the [server README file](server#documentation).

Release Notes, Support Matrix, and Licenses information are available in the 
[NVIDIA Triton Inference Server Documentation](https://docs.nvidia.com/deeplearning/triton-inference-server/index.html).

## Examples
Specific end-to-end examples for popular models, such as ResNet, BERT, and DLRM 
are located in the [NVIDIA Deep Learning Examples page on GitHub](https://github.com/NVIDIA/DeepLearningExamples). Additional generic examples can be found in the 
[server documents](server/tree/main/docs/examples).

## Feedback
Share feedback or ask questions about NVIDIA Triton Inference Server by filing a 
[GitHub issue](server/issues).