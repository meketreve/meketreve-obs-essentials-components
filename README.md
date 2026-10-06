# Meketreve OBS Essentials — components

Files that [Meketreve OBS Essentials](https://github.com/meketreve/meketreve-obs-essentials)
downloads on first use, so its installers stay small. The plugin checks each
file's size and SHA-256 (fixed in its source code) before saving it and again
before loading it; anything else is refused. Every file is unchanged from its
upstream source.

Arquivos que o Meketreve OBS Essentials baixa no primeiro uso, para os
instaladores continuarem leves. O plugin confere tamanho e SHA-256 (fixos no
código) antes de gravar e de novo antes de carregar; qualquer outro arquivo é
recusado. Todos são idênticos aos da fonte original.

## face-mask-1 — Face Mask filter / filtro Máscara no rosto

| File | Size (bytes) | SHA-256 | Source | License |
|---|---|---|---|---|
| `libonnxruntime.so.1.20.1` (Linux x64) | 16559416 | `a5faaf78a37590d3fe640f887620e74f6022d34550172b91ad2131bf0ad77d64` | [onnxruntime v1.20.1](https://github.com/microsoft/onnxruntime/releases/tag/v1.20.1), `onnxruntime-linux-x64-1.20.1.tgz` | MIT |
| `onnxruntime.dll` (Windows x64) | 11569696 | `4cb41e89b8bf30578e1dd95e9c40292d61974a4bfcd666409302c4f0c5aa8ce0` | [onnxruntime v1.20.1](https://github.com/microsoft/onnxruntime/releases/tag/v1.20.1), `onnxruntime-win-x64-1.20.1.zip` | MIT |
| `libonnxruntime.1.20.1.dylib` (macOS universal) | 54114312 | `b7b762db4fe82fbc681e7c738bc9dfb686f61f7da5d1c903f0bdba1a62641c5c` | [onnxruntime v1.20.1](https://github.com/microsoft/onnxruntime/releases/tag/v1.20.1), `onnxruntime-osx-universal2-1.20.1.tgz` | MIT |
| `face_detection_yunet_2023mar.onnx` | 232589 | `8f2383e4dd3cfbb4553ea8718107fc0423210dc964f9f4280604804ed2552fa4` | [opencv_zoo](https://github.com/opencv/opencv_zoo/tree/main/models/face_detection_yunet) (YuNet) | MIT |
| `headpose_mobilenetv2.onnx` | 8905103 | `1e902872868e483bd0e4f8f4a8ff2a4d61c2ccbca9dadf748e5479b5cc86a9e9` | [yakhyo/head-pose-estimation](https://github.com/yakhyo/head-pose-estimation/releases/tag/weights), `mobilenetv2.onnx` | MIT |
| `face_landmark_468.onnx` | 2440358 | `ed487104519b0a88cb2cb2ec3678e183f447fb9dd63560998e960ffbaa8fb335` | [keijiro/FaceLandmarkBarracuda](https://github.com/keijiro/FaceLandmarkBarracuda) (MediaPipe FaceMesh), `face_landmark_barracuda.onnx` | Apache-2.0 |

The license texts are in [`licenses/`](licenses/), including onnxruntime's
third-party notices.
