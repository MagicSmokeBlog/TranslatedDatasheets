# Resource R07

| Resource                                          | Source                                                                          | Remark                                                   |
|---------------------------------------------------|---------------------------------------------------------------------------------|----------------------------------------------------------|
| [ITM2-M-scan.pdf](./resource/R07/ITM2-M-scan.pdf) | [ITM2Mdatasheet.PDF](https://www.industrialalchemy.org/pdf2/ITM2Mdatasheet.PDF) | [Industrial Alchemy](https://www.industrialalchemy.org/) | 
| [ITM2-M-ocr.txt](./resource/R07/ITM2-M-ocr.txt)   | [ABBYY OCR](https://www.abbyy.com/ocr-sdk/)                                     | See notes below                                          |
| [ITM2-M-ocr.pdf](./resource/R07/ITM2-M-ocr.pdf)   | [ABBYY OCR](https://www.abbyy.com/ocr-sdk/)                                     | See notes below                                          |

## Notes

Command to convert the scanned document to plain text:

```shell
abbyyocr11 -rl Russian -f TextUnicodeDefaults --txtUsePageBreaks --txtRetainLayout -if ITM2-M-scan.pdf -of ITM2-M-ocr.txt
```

Command to convert the scanned document to PDF with selectable text:

```shell
abbyyocr11 -rl Russian --outputFileFormat PDF --pdfFontEmbeddingMode Embed --pdfaComplianceMode Pdfa_2a --pdfTextExportMode ImageOnText --pdfScenario MaxQuality -if ITM2-M-scan.pdf -of ITM2-M-ocr.pdf
```