# HERMA Barcode Label Maker

A small browser app for creating a full sheet of 44 barcode stickers. The printed label design follows the supplied example: a horizontal barcode on top with its value centered underneath.

## Run

Open `index.html` in a modern browser. The barcode library loads from jsDelivr, so an internet connection is needed.

## Use

1. Enter the first value, ending in digits (for example, `SRP209911`).
2. Choose the barcode type. Code 39 is selected by default and shows the start/stop asterisks around each printed value.
3. Generate the preview. The remaining 43 labels increment automatically, down each column and then across.
4. Print on A4 at **Actual size / 100%**. Turn off “Fit to page.”

The print sheet is set for HERMA 4272: 44 labels (4 × 11), each 48.26 × 25.4 mm, with calculated equal page boundaries of 8.48 mm left/right and 8.8 mm top/bottom, based on HERMA's official punch template.

## Note

Printer feed can shift output slightly. Print a plain-paper alignment sheet first and compare it against a label sheet before printing stickers.


