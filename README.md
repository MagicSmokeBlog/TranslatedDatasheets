# Translated Datasheets

This repository contains datasheets translated into English, mostly of Ukraine sourced components.

## Datasheets

## Resources

### Resource R01

| Resource                                 | Source                                                                                           | Remark                                                                                     |
|------------------------------------------|--------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------|
| Знакосинтезирующие Индикаторы.djvu       | [russian-book-0001.djvu](http://www.tube-tester.com/sites/nixie/dat_arch/russian-book-0001.djvu) | [Dieter’s Nixie Tube Data Archive](http://www.tube-tester.com/sites/nixie/nixie-tubes.htm) |
| Знакосинтезирующие Индикаторы (scan).pdf | [DjVu to  PDF](https://djvu2pdf.com)                                                             | Free online DjVu to PDF converter                                                          |
| Знакосинтезирующие Индикаторы (ocr).txt  | [ABBYY OCR](https://www.abbyy.com/ocr-sdk/)                                                      | See notes below                                                                            |
| Знакосинтезирующие Индикаторы (ocr).pdf  | [ABBYY OCR](https://www.abbyy.com/ocr-sdk/)                                                      | See notes below                                                                            |

#### Notes

Command to convert the scanned document to plain text:

```shell
abbyyocr11 -rl Russian -f TextUnicodeDefaults --txtUsePageBreaks --txtRetainLayout -if 'Знакосинтезирующие Индикаторы (scan).pdf' -of 'Знакосинтезирующие Индикаторы (ocr).txt'
```

Command to convert the scanned document to PDF with selectable text:

```shell
abbyyocr11 -rl Russian --outputFileFormat PDF --pdfFontEmbeddingMode Embed --pdfaComplianceMode Pdfa_2a --pdfTextExportMode ImageOnText --pdfScenario MaxQuality -if 'Знакосинтезирующие Индикаторы (scan).pdf' -of 'Знакосинтезирующие Индикаторы (ocr).pdf'
```

Using option `--pdfTextExportMode TextWithPictures` resulted in a PDF document with selectable text, however the text
was not visible.

