# Translated Datasheets

This repository contains datasheets translated into English, mostly of Ukraine sourced components.

## Datasheets

|                           Image                           | Datasheet                                                                                 | Resource             |
|:---------------------------------------------------------:|-------------------------------------------------------------------------------------------|----------------------|
|   ![8LO39](datasheet/8LO39V-(8ЛО39В)-CRT/thumbnail.png)   | [8LO39V (8ЛО39В) CRT](./datasheet/8LO39V-(8ЛО39В)-CRT/8LO39V-(8ЛО39В)-Datasheet.md)       | [R02](#resource-r02) |
|     ![ILD3](datasheet/ILD3-(ИЛД3)-CRT/thumbnail.png)      | [ILD3 (ИЛД3) CRT](./datasheet/ILD3-(ИЛД3)-CRT/ILD3-(илдз)-Datasheet.md)                   | [R03](#resource-r03) |
| ![ITS1A](datasheet/ITS1A-(ИТС1А)-Thyratron/thumbnail.png) | [ITS1A (ИТС1А) Thyratron](./datasheet/ITS1A-(ИТС1А)-Thyratron/ITS1A-(ИТС1А)-Datasheet.md) | [R01](#resource-r01) |
|  ![IV-6](datasheet/IV-6-(ИВ-6)-Indicator/thumbnail.png)   | [IV-6 (ИВ-6) Indicator](datasheet/IV-6-(ИВ-6)-Indicator/IV-6-(ИВ-6)-Datasheet.md)         | [R01](#resource-r01) |
| ![IV-19](datasheet/IV-19-(ИВ-19)-Indicator/thumbnail.png) | [IV-19 (ИВ-19) Indicator](datasheet/IV-19-(ИВ-19)-Indicator/IV-19-(ИВ-19)-Datasheet.md)   | [R01](#resource-r01) |

## Resources

### Resource R01

| Resource                                                                                       | Source                                                                                           | Remark                                                                                     |
|------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------|
| [Знакосинтезирующие-Индикаторы.djvu](./resource/R01/Знакосинтезирующие-Индикаторы.djvu)        | [russian-book-0001.djvu](http://www.tube-tester.com/sites/nixie/dat_arch/russian-book-0001.djvu) | [Dieter’s Nixie Tube Data Archive](http://www.tube-tester.com/sites/nixie/nixie-tubes.htm) |
| [Знакосинтезирующие-Индикаторы-scan.pdf](./resource/R01/Знакосинтезирующие-Индикаторы-ocr.pdf) | [DjVu to  PDF](https://djvu2pdf.com)                                                             | Free online DjVu to PDF converter                                                          |
| [Знакосинтезирующие-Индикаторы-ocr.txt](./resource/R01/Знакосинтезирующие-Индикаторы-ocr.txt)  | [ABBYY OCR](https://www.abbyy.com/ocr-sdk/)                                                      | See notes below                                                                            |
| [Знакосинтезирующие-Индикаторы-ocr.pdf](./resource/R01/Знакосинтезирующие-Индикаторы-scan.pdf) | [ABBYY OCR](https://www.abbyy.com/ocr-sdk/)                                                      | See notes below                                                                            |

#### Notes

Command to convert the scanned document to plain text:

```shell
abbyyocr11 -rl Russian -f TextUnicodeDefaults --txtUsePageBreaks --txtRetainLayout -if Знакосинтезирующие-Индикаторы-scan.pdf -of Знакосинтезирующие-Индикаторы-ocr.txt
```

Command to convert the scanned document to PDF with selectable text:

```shell
abbyyocr11 -rl Russian --outputFileFormat PDF --pdfFontEmbeddingMode Embed --pdfaComplianceMode Pdfa_2a --pdfTextExportMode ImageOnText --pdfScenario MaxQuality -if Знакосинтезирующие-Индикаторы-scan.pdf -of Знакосинтезирующие-Индикаторы-ocr.pdf
```

Using option `--pdfTextExportMode TextWithPictures` resulted in a PDF document with selectable text, however the text
was not visible.

### Resource R02

| Resource                                        | Source                                      | Remark          |
|-------------------------------------------------|---------------------------------------------|-----------------|
| [8LO39V-scan.pdf](resource/R02/8LO39V-scan.pdf) |                                             |                 |
| [8LO39V-ocr.txt](./resource/R02/8LO39V-ocr.txt) | [ABBYY OCR](https://www.abbyy.com/ocr-sdk/) | See notes below |
| [8LO39V-ocr.pdf](./resource/R02/8LO39V-ocr.pdf) | [ABBYY OCR](https://www.abbyy.com/ocr-sdk/) | See notes below |

#### Notes

Command to convert the scanned document to plain text:

```shell
abbyyocr11 -rl Russian -f TextUnicodeDefaults --txtUsePageBreaks --txtRetainLayout -if 8LO39V-scan.pdf -of 8LO39V-ocr.txt
```

Command to convert the scanned document to PDF with selectable text:

```shell
abbyyocr11 -rl Russian --outputFileFormat PDF --pdfFontEmbeddingMode Embed --pdfaComplianceMode Pdfa_2a --pdfTextExportMode ImageOnText --pdfScenario MaxQuality -if 8LO39V-scan.pdf -of 8LO39V-ocr.pdf
```

### Resource R03

| Resource                                      | Source                                          | Remark          |
|-----------------------------------------------|-------------------------------------------------|-----------------|
| [ILD3-scan.pdf](./resource/R03/ILD3-scan.pdf) | eBay image of an item of a Ukraine based seller |                 |
| [ILD3-ocr.txt](./resource/R03/ILD3-ocr.txt)   | [ABBYY OCR](https://www.abbyy.com/ocr-sdk/)     | See notes below |
| [ILD3-ocr.pdf](./resource/R03/ILD3-ocr.pdf)   | [ABBYY OCR](https://www.abbyy.com/ocr-sdk/)     | See notes below |

#### Notes

Command to convert the scanned document to plain text:

```shell
abbyyocr11 -rl Russian -f TextUnicodeDefaults --txtUsePageBreaks --txtRetainLayout -if ILD3-scan.pdf -of ILD3-ocr.txt
```

Command to convert the scanned document to PDF with selectable text:

```shell
abbyyocr11 -rl Russian --outputFileFormat PDF --pdfFontEmbeddingMode Embed --pdfaComplianceMode Pdfa_2a --pdfTextExportMode ImageOnText --pdfScenario MaxQuality -if ILD3-scan.pdf -of ILD3-ocr.pdf
```

## Contributing

Contributions are very appreciated. Contributing to this project a fantastic  way of sharing your work and effort of
translating a datasheet from Russian or any other language into English with other electronic enthusiasts.
Either make a pull request with an original datasheet and a translation
in English, or mail the documents to [Magic Smoke Blog](mailto:magicsmokeblog@gmail.com), and we will add your
translation to this project.

## License

This project is licensed under
the [Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0)](https://creativecommons.org/licenses/by-nc-sa/4.0/) license.
