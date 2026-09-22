# Population

A Java command-line tool for exploring U.S. city population data. Rank cities by population or name, filter by state, or search by name, all backed by sorting algorithms implemented from scratch.

## Features

Selection sort for the least populous cities.

Recursive merge sort for the most populous cities and reverse-alphabetical listings.

Insertion sort for alphabetical listings.

State-filtered search for the top cities within a specific state.

Name search across all cities, sorted by population.

Runtime benchmarking printed after every operation.

## Project structure

City.java handles the data model for a single city, with layered comparison logic for sorting.

Population.java is the main program: it loads the dataset, shows a menu, and runs the selected sort or search.

FileUtils.java is a file I/O helper for reading the dataset.

Prompt.java is an input utility that validates and retries on invalid user input.

## Running it

Compile with javac followed by all java files, then run java Population.

Requires usPopData2017.txt in the same directory, tab-delimited as state, city, designation, population.

## Why I built it

Originally an AP Computer Science A assignment. I used it to implement and compare three classic sorting algorithms, selection, insertion, and merge, against a real dataset instead of toy examples, and to practice structuring a multi-class Java program around a clear data model.
