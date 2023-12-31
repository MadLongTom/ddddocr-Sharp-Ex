# ddddocr-Sharp-Ex
## base on https://github.com/zixing131/ddddocrsharp
## Improvements
### GPU Support for CUDA users
### SlideMatch algorithm (OpenCV)
## Requirements
ONNX Runtime Version	| CUDA Toolkit Version	| cuDNN Version 
-------- | ----------- | ----- 
1.16	| 11.6	| 8.5.0.96 
## Annotations 
### based on .NET8.0
C# open source project built on dddddocr based on SML2H3's open-source. The source project only provides a pypi version and cannot meet the needs of C# developers. Therefore, i'm attempting to develop this project. 

The project utilized Microsoft ML.OnnxRuntime.Gpu performs inference while relying on OpenCvSharp4. Can be compiled using AOT 

Currently, it supports object detection and text recognition, but does not currently support custom models. 

**Disclaimer: The copyright of the model belongs to the original author sml2h3 and is for learning and communication purposes only. If you have any questions, please feel free to submit an issue.**
