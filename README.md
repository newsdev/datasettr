# Datasettr

A Python library for wrangling CSVs into SQLite databases for serving with Datasette.

## Usage

### Getting started

```
mkvirtualenv datasettr && git clone <GITREMOTE> && cd datasettr
pip install -r requirements.txt
```

### Creating a new database

**STATUS**: Not working yet

Creating a new database means loading a CSV file into SQL lite locally

```
datasettr create <filename.csv>
```

### Sending your database to the cloud for others

**STATUS**: Not working yet

If you want others to be able to see / download your database, you can send it to Google Cloud.

```
datasettr send <dbname>
```

### Serving a local database

**STATUS**: Not working yet

```
datasetter serve <dbname>
```

### Listing available databases in the cloud

**STATUS**: Not working yet

```
datasettr list
```

### Getting a database from the cloud

**STATUS**: Not working yet

```
datasettr get <dbname>
```