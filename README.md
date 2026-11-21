# PP-OCRv6 (Tiny / Small / Medium)  PP-OCRv6 三档 OCR 模型（各含 det + rec ONNX）。HiTi 仅内置最基础模型，此仓库提供按需下载的高阶模型。  ## 下载（每个变体单独一个资产）  | 变体 | 体积 | 直接下载 | | --- | --- | --- |
| Tiny | 4.4 MB | [ppocrv6-tiny.zip](upload ppocrv6-tiny.zip -> hiti-model-ocr (4.4 MB)   ok https://github.com/xixi3548942758-design/hiti-model-ocr/releases/download/v1.0/ppocrv6-tiny.zip https://github.com/xixi3548942758-design/hiti-model-ocr/releases/download/v1.0/ppocrv6-tiny.zip) |
| Small | 20.5 MB | [ppocrv6-small.zip](upload ppocrv6-small.zip -> hiti-model-ocr (20.5 MB)   ok https://github.com/xixi3548942758-design/hiti-model-ocr/releases/download/v1.0/ppocrv6-small.zip https://github.com/xixi3548942758-design/hiti-model-ocr/releases/download/v1.0/ppocrv6-small.zip) |
| Medium | 73.4 MB | [ppocrv6-medium.zip](upload ppocrv6-medium.zip -> hiti-model-ocr (73.4 MB)   ok https://github.com/xixi3548942758-design/hiti-model-ocr/releases/download/v1.0/ppocrv6-medium.zip https://github.com/xixi3548942758-design/hiti-model-ocr/releases/download/v1.0/ppocrv6-medium.zip) |

## 目录结构

解压后与 HiTi `AI_model` 下同名目录一致，直接放入即可：

```
PP-OCRv6-Tiny/  PP-OCRv6-Small/  PP-OCRv6-Medium/
  det/inference.onnx + inference.json/yml
  rec/inference.onnx + inference.json/yml
```

模型来源：PaddlePaddle / SenseVoice / BEATs 官方发布，仅做 ONNX 量化转换，遵循各自原始许可证。