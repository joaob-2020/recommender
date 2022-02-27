# The goal of this project is to create a recommendation system for books.
# "The datasets were collected in late 2017 from goodreads.com, where we only scraped users' public shelves, i.e. everyone can see it on web without login. User IDs and review IDs are anonymized. "
    source: https://sites.google.com/eng.ucsd.edu/ucsdbookgraph
    We will need three datasets to create search_engine.ipynb and recommendation.ipynb files:
#### 1) goodreads_interactions.csv with 4GB and the following columns:
            - user id;
            - book id;
            - rating (can go from 0 to 5).
#### 2) goodreads_books.json.gz with 2GB and each line is a metadata from a specific book, for example:
            - title;
            - book id;
            - ratings count.
#### 3) Book id map that connects both datasets with the following columns:
            - book_id_csv;
            - book_id.
