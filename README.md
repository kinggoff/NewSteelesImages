# NewSteelesImages

Recovered Steeles Paint product images for the 62 rows marked `Image Added` in
`products_categories_descriptions_02.csv`.

- `originals/` contains untouched downloads from the URLs recorded in the CSV.
- `corrected/` contains transparent-background corrections. Originals are never overwritten.
- `manifest.json` records each product, SKU, CSV source URL, resolved URL, and local filename.

Image 42 (`ProDec Titan Roller Frame`) remains under manual review because its
white field is part of an instruction diagram; automatic removal would destroy
meaningful product information.
