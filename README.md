# IKEA place names data

Data behind [IKEA place names](https://karaman.is/ikea-place-names): every
sofa and armchair on ikea.com in 50 countries on 28 September 2026, and the
places in Sweden that share their names.

- `ikea_seating.csv`: products, prices and `price_usd`
- `ikea_places.csv`: matching Swedish places
- `cleaning.R`: download and cleaning code

Sources: product listings from ikea.com; places from OpenStreetMap via
Nominatim, © OpenStreetMap contributors (ODbL); exchange rates from the
fawazahmed0 currency API (CC0). Also submitted to
[TidyTuesday](https://github.com/rfordatascience/tidytuesday/pull/1092).
