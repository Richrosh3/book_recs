# Book Recommendations

---

## Descripion
Processing a goodreads dataset and utilizing machine learning to recommend books that I may like based on past
ratings. 

---

## Setup

1) Download the [dataset](https://www.kaggle.com/datasets/opalskies/large-books-metadata-dataset-50-mill-entries?resource=download) from Kaggle into the repo.
    - **WARNING:  The unzipped dataset is 90GB**
    - This is what your file tree should look like: 
        ```bash
        .
        └── book_recs/
            ├── book_database/
            │   ├── authors.json/
            │   │   └── authors.json
            │   ├── books.json/
            │   │   └── books.json
            │   ├── list.json/
            │   │   └── list.json
            │   └── series.json/
            │       └── series.json
            ├── .gitignore
            ├── LICENSE
            ├── README.md
            └── search.ipynb
        ```
    

---

### Acknowledgments
Thank you to Opal Skies for compiling the dataset!