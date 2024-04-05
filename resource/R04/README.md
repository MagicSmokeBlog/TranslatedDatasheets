# Resource R04

| Resource                               | Source                                      | Remark                                |
|----------------------------------------|---------------------------------------------|---------------------------------------|
| [FEU-115-scan.pdf](./FEU-115-scan.pdf) |                                             | Scan of document attached to the tube | 
| [FEU-115-ocr.txt](./FEU-115-ocr.txt)   | [ABBYY OCR](https://www.abbyy.com/ocr-sdk/) | See notes below                       |
| [FEU-115-ocr.pdf](./FEU-115-ocr.pdf)   | [ABBYY OCR](https://www.abbyy.com/ocr-sdk/) | See notes below                       |

## Notes

Command to convert the scanned document to plain text:

```shell
abbyyocr11 -rl Russian -f TextUnicodeDefaults --txtUsePageBreaks --txtRetainLayout -if FEU-115-scan.pdf -of FEU-115-ocr.txt
```

Command to convert the scanned document to PDF with selectable text:

```shell
abbyyocr11 -rl Russian --outputFileFormat PDF --pdfFontEmbeddingMode Embed --pdfaComplianceMode Pdfa_2a --pdfTextExportMode ImageOnText --pdfScenario MaxQuality -if FEU-115-scan.pdf -of FEU-115-ocr.pdf
```
