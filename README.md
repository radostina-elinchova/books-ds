# Book Editions, Popularity and Reader Ratings

## Project goal

Explore associations between catalogued editions, Goodreads
rating counts and average reader ratings.

## Data sources

- Goodreads data distributed through Kaggle:
  https://www.kaggle.com/datasets/jealousleopard/goodreadsbooks
- Open Library:
  https://openlibrary.org/
- Open Library Search API:
  https://openlibrary.org/dev/docs/api/search

## Project structure

- books_project.ipynb: main analysis
- data/raw/: original input files
- data/raw/openlibrary_responses/: saved API responses
- data/processed/: generated datasets
- figures/: exported figures

## Current status

Project setup is complete.
The next step is a five-book data integration pilot.

The pilot will validate data handling and will not support
statistical conclusions.

## Planned workflow

1. Validate the integration process using five books.
2. Inspect and clean the full Goodreads dataset.
3. Retrieve and validate matching Open Library records.
4. Create a work-level analysis dataset.
5. Explore distributions and relationships.
6. Perform suitable statistical and sensitivity analyses.
7. Document findings, limitations and reproduction steps.

## Reproducibility

Detailed execution instructions and dependency versions
will be added as the workflow is implemented and tested.

## Limitations

- The pilot books were deliberately selected.
- Goodreads and Open Library may represent different dates.
- Rating count is a proxy for popularity.
- Open Library edition counts reflect catalogue coverage.
- Associations do not establish causation.

## References and acknowledgements

Data sources, adapted code and assistance used in the project
will be documented here and in the notebook.