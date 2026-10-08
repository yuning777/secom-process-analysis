# SECOM process analysis

A practice project on the UCI SECOM semiconductor dataset. I'm trying to find out which process
sensors are linked to failed products, and whether a simple model can flag failures early.

Status: work in progress. So far I've loaded the data and cleaned it (see `notebooks/01_load_and_inspect.ipynb`).

## Data
UCI SECOM dataset, 1,567 samples with 590 sensors, labeled pass or fail.
Source: https://archive.ics.uci.edu/dataset/179/secom (CC BY 4.0)

## Questions
1. Which sensors look different when a sample fails?
2. Does the failure rate change over time?
3. Can a simple model catch failures early, and how reliable is it?
