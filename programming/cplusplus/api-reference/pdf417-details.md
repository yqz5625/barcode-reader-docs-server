---
layout: default-layout
title: CPDF417Details Class - Dynamsoft Barcode Reader C++ Edition API Reference
description: This page shows CPDF417Details class definition of Dynamsoft Barcode Reader SDK C++ Edition.
keywords: rows, columns, errorCorrectionLevel, CPDF417Details, api reference
---
# CPDF417Details

The `CPDF417Details` class represents a barcode in PDF417 format. It inherits from the `CBarcodeDetails` class and contains information about the row count, column count, and error correction level of the barcode.

## Definition

*Namespace:* dynamsoft::dbr

*Assembly:* DynamsoftBarcodeReader

*Inheritance:* [CBarcodeDetails]({{ site.dbr_cpp_api }}barcode-details.html) -> CPDF417Details

```cpp
class CPDF417Details : public CBarcodeDetails
```

## Attributes

| Attribute | Type |
|---------- | ---- |
| [`rows`](#rows) | *int* |
| [`columns`](#columns) | *int* |
| [`errorCorrectionLevel`](#errorcorrectionlevel) | *int* |
| [`hasLeftRowIndicator`](#hasleftrowindicator) | *int* |
| [`hasRightRowIndicator`](#hasrightrowindicator) | *int* |
| [`codewords`](#codewords) | *unsigned int\** |
| [`codewordsCount`](#codewordscount) | *int* |

### rows

The number of rows in the PDF417 barcode.

```cpp
int rows
```

### columns

The number of columns in the PDF417 barcode.

```cpp
int columns
```

### errorCorrectionLevel

Specifies the error correction level of PDF417 code.

```cpp
int errorCorrectionLevel
```

### hasLeftRowIndicator

Specifies whether the left row indicator of the PDF417 code exists.

```cpp
int hasLeftRowIndicator
```

### hasRightRowIndicator

Specifies whether the right row indicator of the PDF417 code exists.

```cpp
int hasRightRowIndicator
```

### codewords

The codewords of the PDF417 barcode.

```cpp
unsigned int* codewords
```

### codewordsCount

The count of the codewords.

```cpp
int codewordsCount
```
