# SNAP Curation

## Purpose
A repo for accumulating the pre-processing of datasets that will be served throughvarious levels of the SNAP infrastructure. Code here will likely include things like changing file formats, decomposing/repackaging data, QA/QC, and metadata extraction (i.e., querying data for metadata-relevant info). The key theme is, well, **curation**: identifying and harvesting the "pots-of-gold" from a large and complex dataset.

## Related repos

### `ua-snap/rasdaman-ingest`
code in that repo (beyond the ingest) might touch the outputs from this repo, but if the code is just reshaping or reformattting for the exclusive purpose of Rasdaman interopability, put in that repo and consider executing it via a pre-ingest hook.


### `ua-snap/prefect`
code in the prefect repo may clone this repo, but if the code is going to be "prefect native" or there is going to be a recurring prefect flow dealing with the data, it probably is a better fit in the prefect repo.


