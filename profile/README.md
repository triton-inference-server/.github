# NVIDIA Triton Inference Server Organization
[NVIDIA Triton Inference Server](https://github.com/triton-inference-server/server)
provides a cloud and edge inferencing solution optimized for both CPUs and GPUs.

This top level GitHub organization host repositories for officially supported 
backends, including [TensorRT](https://github.com/triton-inference-server/tensorrt_backend), [TensorFlow](https://github.com/triton-inference-server/tensorflow_backend), 
[PyTorch](https://github.com/triton-inference-server/pytorch_backend), 
[Python](https://github.com/triton-inference-server/python_backend), 
[ONNX Runtime](https://github.com/triton-inference-server/onnxruntime_backend), 
and [OpenVino](https://github.com/triton-inference-server/openvino_backend). The
organization also hosts several popular Triton tools, including:

* [Model Analyzer](https://github.com/triton-inference-server/model_analyzer):
A tool to analyze the runtime performance of a model and provide an optimized 
model configuration for Triton Inference Server.

* [Model Navigator](https://github.com/triton-inference-server/model_navigator):
a tool that provides the ability to automate the process of moving a model from source to optimal format and configuration for deployment on Triton Inference Server.

## Getting Started
To learn about NVIDIA Triton Inference Server, refer to the 
[Triton developer page](https://docs.nvidia.com/deeplearning/triton-inference-server/user-guide/docs/introduction/index.html) 
and read our [Quickstart Guide](https://github.com/triton-inference-server/server/blob/main/docs/getting_started/quickstart.md). Official 
Triton Docker containers are available from [NVIDIA NGC](https://catalog.ngc.nvidia.com/orgs/nvidia/containers/tritonserver).

## Product Documentation
User documentation on Triton features, APIs, and architecture is located in the [server
documents on GitHub](https://github.com/triton-inference-server/server/tree/main/docs).
A table of contents for the user documentation is located in the [server README file](https://github.com/triton-inference-server/server#documentation).

Release Notes, Support Matrix, and Licenses information are available in the 
[NVIDIA Triton Inference Server Documentation](https://docs.nvidia.com/deeplearning/triton-inference-server/index.html).

## Examples
Specific end-to-end examples for popular models, such as ResNet, BERT, and DLRM 
are located in the [NVIDIA Deep Learning Examples page on GitHub](https://github.com/NVIDIA/DeepLearningExamples). Additional generic examples can be found in the 
[server documents](https://github.com/triton-inference-server/server/tree/main/docs/examples).

## FAQ
For technical questions about Triton Inference Server, please consult the [Triton FAQ Guide](https://github.com/triton-inference-server/server/blob/main/docs/user_guide/faq.md). Information about future support & updates for Triton can be found in the [Dynamo FAQ Guide](https://forums.developer.nvidia.com/t/nvidia-dynamo-faq/327484).

## Feedback
Share feedback or ask questions about NVIDIA Triton Inference Server by filing a 
[GitHub issue](https://github.com/triton-inference-server/server/issues).
