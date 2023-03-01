# NLA digitised finding aids in Trove

[![Frictionless](https://github.com/GLAM-Workbench/nla-finding-aids-data/actions/workflows/frictionless.yaml/badge.svg)](https://repository.frictionlessdata.io/pages/dashboard.html?user=frictionlessdata&repo=repository-demo&flow=frictionless)

This repository contains data about the National Library of Australia's digitised manuscript finding aids, harvested from Trove.

See the [Trove unpublished works section](https://glam-workbench.net/trove-unpublished/) of the GLAM Workbench for information on how these datasets were created.

## `finding-aids.csv`

This is just a list of urls to digitised finding aids. Columns:

- `url`

## `finding-aids-totals.csv`

This dataset includes summary information describing each finding aid. Columns include:

- `url`
- `collection_number`
- `title`
- `creator`
- `date_range`
- `extent`
- `language_of_materials`
- `repository`
- `sponsor`
- `abstract`
- `physical_description`
- `total_elements` – number of headings or sections within the finding aid, this includes both containers (like series and boxes) and individual items (like letters and diaries)
- `total_items` – number of elements at the bottom of the hierarchy (so they have no children), they include things like documents and diaries
- `total_digitised_items` – number of items that have been digitised
- `total_searchable` – number of elements that can be found by a search in Trove's 'Diaries, Letters, and Archives' category