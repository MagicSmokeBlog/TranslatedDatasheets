# Resource R03

| Resource                                      | Source                                      | Remark                                          |
|-----------------------------------------------|---------------------------------------------|-------------------------------------------------|
| [ILD3-scan.pdf](./resource/R03/ILD3-scan.pdf) |                                             | eBay image of an item of a Ukraine based seller | 
| [ILD3-ocr.txt](./resource/R03/ILD3-ocr.txt)   | [ABBYY OCR](https://www.abbyy.com/ocr-sdk/) | See notes below                                 |
| [ILD3-ocr.pdf](./resource/R03/ILD3-ocr.pdf)   | [ABBYY OCR](https://www.abbyy.com/ocr-sdk/) | See notes below                                 |

## Notes

Command to convert the scanned document to plain text:

```shell
abbyyocr11 -rl Russian -f TextUnicodeDefaults --txtUsePageBreaks --txtRetainLayout -if ILD3-scan.pdf -of ILD3-ocr.txt
```

Command to convert the scanned document to PDF with selectable text:

```shell
abbyyocr11 -rl Russian --outputFileFormat PDF --pdfFontEmbeddingMode Embed --pdfaComplianceMode Pdfa_2a --pdfTextExportMode ImageOnText --pdfScenario MaxQuality -if ILD3-scan.pdf -of ILD3-ocr.pdf
```
