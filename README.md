# store
take reference from [bilibili](https://www.bilibili.com/video/BV1np4y1C7Yf?p=14&amp;spm_id_from=pageDriver&amp;vd_source=63593771069c35f66fcc46108f09f670)

## 1. Introduction

This is a project for a retail store. It includes the following modules:

- `store`: the main module of the project, which contains the business logic of the store.
- `database`: the module for database operations, including database connection, table creation, and data insertion/retrieval.
- `api`: the module for external API integration, including external APIs for payment, shipping, and inventory management.
- `utils`: the module for utility functions, including common functions for data validation, date/time conversion, and encryption/decryption.


## 2. Usage

To use this project, you need to follow these steps:

1. Install the required dependencies:

```
pip install -r requirements.txt
```

2. Set up the database:

```
python database/create_tables.py
```

3. Run the main program:

```
python store/main.py
```
