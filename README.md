# PP-OCRv6 (Tiny / Small / Medium)

PP-OCRv6 OCR 模型三档（Tiny / Small / Medium，各含 det + rec ONNX）。

HiTi 只在内置包里带最基础的那一个模型，其余全部按需下载。本仓库提供「设置 → 本地模型」页里可选的高阶模型，**每个变体单独一个资产，只下你要的那一档**。

## 下载

| 变体 | 体积 | 直接下载 |
| --- | --- | --- |
| Tiny | 4.4 MB | [ppocrv6-tiny.zip](https://github.com/xixi3548942758-design/hiti-model-ocr/releases/download/v1.0/ppocrv6-tiny.zip) |
| Small | 20.5 MB | [ppocrv6-small.zip](https://github.com/xixi3548942758-design/hiti-model-ocr/releases/download/v1.0/ppocrv6-small.zip) |
| Medium | 73.4 MB | [ppocrv6-medium.zip](https://github.com/xixi3548942758-design/hiti-model-ocr/releases/download/v1.0/ppocrv6-medium.zip) |

## 目录结构

解压后目录名与 HiTi `AI_model` 下同名目录一致，直接放进去即可：

```
PP-OCRv6-Tiny/  PP-OCRv6-Small/  PP-OCRv6-Medium/
  det/inference.onnx  inference.json  inference.yml
  rec/inference.onnx  inference.json  inference.yml
```

## 说明

- 同一模型的不同量化档（int4 / int8）只选一个放进目录，不要同时放。
- 原模型由 PaddlePaddle / SenseVoice / BEATs 官方发布，本仓库仅为 ONNX 量化转换后的分发，遵循各自原始许可证。
