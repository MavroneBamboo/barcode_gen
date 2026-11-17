# HERMA Barcode Label Maker

A small browser app for creating sequential barcode labels on A4 sticker sheets. The label design shows a horizontal barcode above its value.

## Run

Open `index.html` in a modern browser. The barcode library loads from jsDelivr, so an internet connection is needed.

## Use

1. Choose sticker paper. HERMA 4272 is the default; HERMA 4271 and AP 9010 are also available.
2. Enter the first value, ending in digits (for example, `SRP209911`).
3. Choose the barcode type. Code 39 is selected by default and shows start/stop asterisks around each printed value.
4. Generate the preview. The sequence fills each sheet down the columns and then across.
5. Print on A4 portrait at **Actual size / 100%**, with margins set to **None** and browser headers and footers off.

## Supported label sheets

- HERMA 4272: 48.26 × 25.4 mm, 44 labels (4 × 11), based on HERMA's official punch template.
- HERMA 4271: 48.26 × 16.93 mm, 64 labels (4 × 16), based on HERMA's official punch template.
- AP 9010: 105 × 48 mm, 12 labels (2 × 6), compatible with UniStat U4457.

For each layout, page boundaries are calculated from A4 dimensions and the selected label grid.
