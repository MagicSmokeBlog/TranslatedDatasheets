# Translated Datasheets

This repository contains datasheets translated into English, mostly of Ukraine sourced components.

## Datasheets

| Image                                                     | Datasheet                                                                                 |
|-----------------------------------------------------------|-------------------------------------------------------------------------------------------|
| ![8LO39](datasheet/8LO39V-(8ЛО39В)-CRT/thumbnail.png)     | [8LO39V-(8ЛО39В) CRT](./datasheet/8LO39V-(8ЛО39В)-CRT/8L039V-(8ЛО39В)-Datasheet.md)       | 
| ![ITS1A](datasheet/ITS1A-(ИТС1А)-Thyratron/thumbnail.png) | [ITS1A (ИТС1А) Thyratron](./datasheet/ITS1A-(ИТС1А)-Thyratron/ITS1A-(ИТС1А)-Datasheet.md) | 
| ![IV-6](datasheet/IV-6-(ИВ-6)-Indicator/thumbnail.png)    | [IV-6 (ИВ-6) Indicator](datasheet/IV-6-(ИВ-6)-Indicator/IV-6-(ИВ-6)-Datasheet.md)         | 
| ![IV-19](datasheet/IV-19-Indicator/thumbnail.png)         | [IV-19 (ИВ-19) Indicator](./datasheet/IV-19-Indicator/IV-19-(ИВ-19)-Datasheet.md)         | 

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

### Resource R02

| Resource   | Source | Remark |
|------------|--------|--------|
| 8LO39V.pdf |        |        |


## License

This project is licensed under the [Attribution-ShareAlike 4.0 International (CC BY-SA 4.0) ](https://creativecommons.org/licenses/by-sa/4.0/) license.
