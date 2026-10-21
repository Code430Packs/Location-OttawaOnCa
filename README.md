# Ottawa, Ontario, Canada

The city of Ottawa for [Code 430](https://github.com/Code430Game/Code430Game), one map pack per
district, built from OpenStreetMap.

| District | Pack | Area | Version |
|---|---|---|---|
| Centretown | `packs/centretown` (`code430.ottawa-centretown`) | about 3.3 × 3.1 km, around Parliament Hill, the Rideau Canal and the 417 | 0.2.0 |

More districts (the Glebe, the ByWard Market, ...) join as their own packs beside Centretown,
using Ottawa's pinned origin (lat 45.4200027, lon -75.6950007) and a border on its 256 m chunk
grid; see `regions/README.md`. Centretown still uses its original bbox, and moves onto the grid
at its next re-export (a breaking change, 0.3.0).

## Rebuild a district
From a checkout of the game at the commit in `code430.json`:

```
cd <game>/tools
uv run python -m osm_import --region <this repo>/regions/centretown.json \
  --pack-out <this repo>/packs/centretown --pack-version <next version> --build-stamp
```

The importer refuses a re-export that would move the origin. Bump the version as the template
says (`python -m pack_tools version check` tells you which bump a change needs), then open a
pull request.

## Releases
Tag `<district>-v<version>` (for example `centretown-v0.2.0`); CI validates the pack and
publishes a zip and its sha256. The game pins a release in its `packs.lock.json`.

## History
This repository's history was split out of the game repository, where the pack was built
until October 2026; `Code430Game/Code430Game#N` in commit messages are that repository's pull
requests.

## Licence
The map data is © OpenStreetMap contributors and available under the
[Open Database License 1.0](https://opendatacommons.org/licenses/odbl/1-0/) (see `LICENSE.md`).
Elevation: High Resolution Digital Elevation Model (HRDEM), Natural Resources Canada, under the
[Open Government Licence - Canada](https://open.canada.ca/en/open-government-licence-canada).
