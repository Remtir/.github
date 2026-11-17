# Remtir

**Remtir is a Thai AI research lab working on computer vision.** We focus on what Thai documents
and images need, which global models often get wrong: stacked vowels and tone marks, Thai digits,
government forms, dense tables and pages photographed on a phone.

ห้องวิจัย AI ไทยด้าน Computer Vision พัฒนาโมเดลอ่านเอกสารและภาพภาษาไทยแบบเปิด

## What we work on

- **Document AI:** OCR, layout analysis, reading order and table structure for Thai and English documents
- **Text recognition:** recognizers built around Thai script, such as grapheme-cluster CTC
- **Efficient vision models:** small models that run on CPU and on-premise, so documents never have to leave the building
- **Evaluation:** fair, reproducible benchmarks for Thai OCR

## Projects

| Project | What it is |
|---|---|
| [AksonOCR-Lite](https://github.com/Remtir/AksonOCR-Lite) | Open-source Thai document OCR on ONNX Runtime: PDF/image → Markdown, layout and tables, ~1.5 s/page on CPU. Apache-2.0. [Live demo](https://aksonocr.com/lite-demo) · [Weights](https://huggingface.co/Remtir/AksonOCR-Lite) |
| [AksonOCR](https://aksonocr.com) | Our document parsing API for harder pages: handwriting, charts, formulas and key extraction. |

## Links

[Website](https://aksonocr.com) · [Hugging Face](https://huggingface.co/Remtir) · [Blog](https://aksonocr.com/blog)
