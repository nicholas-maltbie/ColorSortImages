# Color Sort Images

This project contains python code to sort images by color into a
rainbow or other pattern.

Example of sorting avatar screenshots by color.

![Mosaic of Avatar Screenshots](https://bl6pap003files.storage.live.com/y4mhHJXRhOyoj7SEDINgBtsDrWK-wxVvyyqFGZGMpIbB0x6ELqI1kQtKORwsfvNHG3lj8mySVMLFiSBVqEECZWPa25i_f8rX4AciOFCG-CIvtk9GguOlx5EyN701BuJjKjwd9mrEpXpDmOskHqZ-jiVtLZ-oLSY9pRn78r0rMrwTa3OqZkBPLZ5N8cWLv30QULw?width=644&height=660&cropmode=none)

Example of sorting pokemon by color.

![Pokemon Sorted by Color](https://bl6pap003files.storage.live.com/y4mflf4STp1iGCPW6LcznIxMf1aanzSMmSCNQH8bDd1dMqnNl_e0l8o3PYNk209CbgC6wV8mpFO8_Yqsc5H5j-EmA1CWkK5ZaCJZsYLEkRqU6o7efxQzzSrhD7VQM6gS7VNottURBI9p3NRhDRE5JxJSqeOmsG2MxX-aOErxvFMgUrtopBYdTpEJQgQe6HVX7wC?width=660&height=368&cropmode=none)

## Datasets

Example image datasets can be downloaded from the datasets folder

* `datasets/pokemon` - Downloading all pokemon images.

## Source

A huge inspiration from this project comes from the great article
[The incredibly challenging task of sorting colours](https://www.alanzucconi.com/2015/09/30/colour-sorting/)
by Alan Zucconi about colors and image processing.

## Overview

This algorithm takes a few steps

1. Gather and prepare data
1. Identify main colors of images
1. Sort colors of images
1. Combine images into mosaic using sorting

## Usage

To use this project, setup a python environment
with the following commands:

```PowerShell
conda create -n colorsort --file packages.txt
conda activate colorsort
```

### Package List

To update list of packages with current environment, use the following command:

```PowerShell
conda list --export > .\packages.txt
```
