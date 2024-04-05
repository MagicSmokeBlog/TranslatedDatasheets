# Resource R06

| Resource                                        | Source                                      | Remark                                |
|-------------------------------------------------|---------------------------------------------|---------------------------------------|
| [6LO1I-scan.pdf](./resource/R06/6LO1I-scan.pdf) |                                             | Scan of document attached to the tube | 
| [6LO1I-ocr.txt](./resource/R06/6LO1I-ocr.txt)   | [ABBYY OCR](https://www.abbyy.com/ocr-sdk/) | See notes below                       |
| [6LO1I-ocr.pdf](./resource/R06/6LO1I-ocr.pdf)   | [ABBYY OCR](https://www.abbyy.com/ocr-sdk/) | See notes below                       |

## Notes

Command to convert the scanned document to plain text:

```shell
abbyyocr11 -rl Russian -f TextUnicodeDefaults --txtUsePageBreaks --txtRetainLayout -if 6LO1I-scan.pdf -of 6LO1I-ocr.txt
```

Command to convert the scanned document to PDF with selectable text:

```shell
abbyyocr11 -rl Russian --outputFileFormat PDF --pdfFontEmbeddingMode Embed --pdfaComplianceMode Pdfa_2a --pdfTextExportMode ImageOnText --pdfScenario MaxQuality -if 6LO1I-scan.pdf -of 6LO1I-ocr.pdf
```
