# Geographical data
This folder contains the following files:
 - Two `.json` files containing the geographic boundaries of UK Local Authority Districts (LDAs) and Parliamentary Constituencies respectively
 - An `.ipynb` notebook that calculates the overlaps between each of these two area types
 - A `.csv` file containing the output of this notebook

The `uk_LADs.json` file was created by merging the following two `.geojson` files:
 - [Great Britain](https://www.data.gov.uk/dataset/1938cd26-64f4-4a72-b73f-729cfedd1ca8/local-authority-districts-december-2021-boundaries-gb-bfc)
 - [Northern Ireland](https://admin.opendatani.gov.uk/dataset/osni-open-data-largescale-boundaries-local-government-districts-1993/resource/e67c0839-6d24-43d6-994a-94459082ed7b)

 The `uk_constituencies.json` file was obtained from a single file available [here](https://www.data.gov.uk/dataset/7165b3a0-a1f2-40ff-a8e0-cfc2a573be30/westminster-parliamentary-constituencies-july-2024-boundaries-uk-bgc).

 Finally, both `.geojson` files were simplified at the ~1% level using the free [mapshaper](https://mapshaper.org/) tool and downloaded as the `.json` files contained in this folder.
