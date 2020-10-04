Save the full serialized form of data.raw
[from here](https://wiki.factorio.com/Data.raw) to raw.txt

Edit the first line of raw.txt so that it reads `raw = {`

run `./raw-to-dict.py`

Copy the graphics folders from Factorio:

- `<factorio>/data/base/graphics` -> `originals/base/graphics`
- `<factorio>/data/core/graphics` -> `originals/core/graphics`

run `./run-conversion.py`
