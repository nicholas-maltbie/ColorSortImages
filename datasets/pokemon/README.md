# Pokemon Dataset

To download the pokemon dataset, use the `get_pokemon.py`script with the following command:

```bash
python get_pokemon.py data/imgs list.csv
```

It will open a multi threaded connection to pokemondb.net to
download all images in batches quickly. It will also
ignore files that have already been downloaded.
