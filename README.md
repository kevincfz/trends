trends
======

This project is a geographic visualization of Twitter data across the USA, analyzing the sentiments of the tweets based on certain key words. It is a project of the CS61A course at UC Berkeley.

Use:
```bash
python3 trends.py -m "keyword"
```

e.g.

```bash
python3 trends.py -m texas
```

```bash
python3 trends.py -m sandwich
```

```bash
python3 trends.py -m obama
```

```bash
python3 trends.py -m "my life"
```

As described on the CS61A instructional page, this project works like this:
> 1.Collecting public Twitter posts (tweets) that have been tagged with geographic locations and filtering for those that contain the "texas" query term,
2. Assigning a sentiment (positive or negative) to each tweet, based on all of the words it contains,
3. Aggregating tweets by the state with the closest geographic center, and finally
4. Coloring each state according to the aggregate sentiment of its tweets. Red means positive sentiment; blue means negative.
