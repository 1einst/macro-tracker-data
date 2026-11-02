# macro-tracker-data

Public data files downloaded by the Macro Tracker app. The app's source code is not here.

## Branded Foods

Each release holds:

- `branded-foods-<date>.sqlite.gz`: a trimmed, gzipped SQLite database of USDA Branded Foods (name, brand, UPC, serving size, calories, protein, carbs, fat).
- `branded-foods.json`: a manifest giving the file name, size, SHA-256 checksum and food count.

The app reads `https://github.com/1einst/macro-tracker-data/releases/latest/download/branded-foods.json`, so publishing a new release with both files updates what new installs download.

## Source and licence

Built from the USDA FoodData Central Branded Foods dataset (https://fdc.nal.usda.gov/). FoodData Central data is in the public domain under CC0 1.0. Credit: U.S. Department of Agriculture, Agricultural Research Service. FoodData Central.
