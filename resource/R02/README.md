# Resource R02

| Resource                                          | Source                                      | Remark                               |
|---------------------------------------------------|---------------------------------------------|--------------------------------------|
| [8LO39V-scan.pdf](./resource/R02/8LO39V-scan.pdf) |                                             | Scan of document attached to the CRT |
| [8LO39V-ocr.txt](./resource/R02/8LO39V-ocr.txt)   | [ABBYY OCR](https://www.abbyy.com/ocr-sdk/) | See notes below                      |
| [8LO39V-ocr.pdf](./resource/R02/8LO39V-ocr.pdf)   | [ABBYY OCR](https://www.abbyy.com/ocr-sdk/) | See notes below                      |

## Notes

Command to convert the scanned document to plain text:

```shell
abbyyocr11 -rl Russian -f TextUnicodeDefaults --txtUsePageBreaks --txtRetainLayout -if 8LO39V-scan.pdf -of 8LO39V-ocr.txt
```

Command to convert the scanned document to PDF with selectable text:

```shell
abbyyocr11 -rl Russian --outputFileFormat PDF --pdfFontEmbeddingMode Embed --pdfaComplianceMode Pdfa_2a --pdfTextExportMode ImageOnText --pdfScenario MaxQuality -if 8LO39V-scan.pdf -of 8LO39V-ocr.pdf
```
