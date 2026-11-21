# PP-OCRv6 (Tiny / Small / Medium) · ONNX

上游模型权重的 ONNX 转换分发，供 HiTi_code 的「设置 → 本地模型」页按需下载。**非官方渠道**，与上游项目及 HiTi_code 项目均无隶属关系。

- 上游：<https://github.com/PaddlePaddle/PaddleOCR>
- 模型卡：<https://huggingface.co/PaddlePaddle>
- 许可证：Apache License 2.0，全文见 LICENSE；权利归属与修改说明见 NOTICE.md

## 下载

每个变体单独一个资产，只下要用的那一档：

| 变体 | 体积 | 直接下载 |
| --- | --- | --- |
| Tiny | 4.4 MB | [ppocrv6-tiny.zip](https://github.com/xixi3548942758-design/PP-OCRv6-ONNX-for-HiTi_code/releases/download/v1.0/ppocrv6-tiny.zip) |
| Small | 20.5 MB | [ppocrv6-small.zip](https://github.com/xixi3548942758-design/PP-OCRv6-ONNX-for-HiTi_code/releases/download/v1.0/ppocrv6-small.zip) |
| Medium | 73.4 MB | [ppocrv6-medium.zip](https://github.com/xixi3548942758-design/PP-OCRv6-ONNX-for-HiTi_code/releases/download/v1.0/ppocrv6-medium.zip) |

## 目录结构

解压后目录名与 HiTi 的 AI_model 目录下同名目录一致，直接放进去即可：

```
PP-OCRv6-Tiny/  PP-OCRv6-Small/  PP-OCRv6-Medium/
  det/inference.onnx  inference.json  inference.yml
  rec/inference.onnx  inference.json  inference.yml
```

## 使用与再分发

- 同一模型的不同量化档（int4 / int8）只选一个放进目录，不要同时放。
- 再分发时必须保留 LICENSE 与 NOTICE.md，保留模型名称，并注明上游出处。
