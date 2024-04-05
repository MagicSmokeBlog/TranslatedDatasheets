# Resource R05

| Resource                                        | Source                                      | Remark                                |
|-------------------------------------------------|---------------------------------------------|---------------------------------------|
| [7LO1M-scan.pdf](./resource/R05/7LO1M-scan.pdf) |                                             | Scan of document attached to the tube | 
| [7LO1M-ocr.txt](./resource/R05/7LO1M-ocr.txt)   | [ABBYY OCR](https://www.abbyy.com/ocr-sdk/) | See notes below                       |
| [7LO1M-ocr.pdf](./resource/R05/7LO1M-ocr.pdf)   | [ABBYY OCR](https://www.abbyy.com/ocr-sdk/) | See notes below                       |

## Notes

Command to convert the scanned document to plain text:

```shell
abbyyocr11 -rl Russian -f TextUnicodeDefaults --txtUsePageBreaks --txtRetainLayout -if 7LO1M-scan.pdf -of 7LO1M-ocr.txt
```

Command to convert the scanned document to PDF with selectable text:

```shell
abbyyocr11 -rl Russian --outputFileFormat PDF --pdfFontEmbeddingMode Embed --pdfaComplianceMode Pdfa_2a --pdfTextExportMode ImageOnText --pdfScenario MaxQuality -if 7LO1M-scan.pdf -of 7LO1M-ocr.pdf
```
