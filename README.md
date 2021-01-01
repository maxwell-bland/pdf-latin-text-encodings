# Latin Text Encodings Table

Columns: `CHAR NAME STD MAC WIN PDF`

TODO at some point: reformat into JSON.

## Encodings

(Transcribed from Adobe PDF Standard):

### StandardEncoding

Adobe standard Latin-text encoding. This is the built-in encoding defined in Type 1 Latin-text font programs (but generally not in TrueType font programs). PDF does not have a predefined encoding named StandardEncoding. However, it is useful to describe this encoding since a font's built-in encoding can be used as the base encoding from which differences are specified in an encoding dictionary.

### MacRomanEncoding

Mac OS standard encoding for Latin text in Western writing systems. PDF has a predefined encoding named MacRomanEncoding that can be used with both Type 1 and TrueType fonts.

### WinAnsiEncoding

Windows Code Page 1252, often called the "Windoes ANSI" encoding. This is the standard Windows encoding for Latin text in Western writing systems. PDF has a predefined encoding named WinAnsiEncoding that can be usd with both Type 1 and TrueType fonts.

### PDFDocEncoding

Encoding for text strings in a PDF document outside the document's content streams. This is one of two encodings (the other being Unicode) that can be used to represent text strings in PDF. PDF does not have a predefined encoding named PDFDocEncoding; it is not customary to use this encoding to show text from fonts.


