# Machine Learning Project: SpeedDating

## Table of Contents
* [Authors](#Authors)
* [Metadata](#Metadata)
* [Folder Structure](#Folder-Structure)
* [List of libraries used](#List-of-libraries-used)
* [Source](#Source)
* [Relevant Paper](#Relevant-Paper)

## Authors
1. [Aaron Kong Kah Lun](https://github.com/TheAEROn)
2. [Wong Jiun Lin](https://github.com/WongJiunLin)
3. [Yap Jheng Khin](https://github.com/polarBearYap)

## Metadata

* This data was gathered from participants in experimental speed dating events from 2002-2004.

* During the events, the attendees would have a four-minute "first date" with every other participant of the opposite sex. At the end of their four minutes, participants were asked if they would like to see their date again. They were also asked to rate their date on six attributes: Attractiveness, Sincerity, Intelligence, Fun, Ambition, and Shared Interests.

* The dataset also includes questionnaire data gathered from participants at different points in the process. These fields include: demographics, dating habits, self-perception across key attributes, beliefs on what others find valuable in a mate, and lifestyle information.

* The binary classification goal is to predict if they were matched or not.

## Folder Structure

1. Source code
   * Execution time: At most 5 minutes.
   * Available in [ipynb](source_code/python/source_code.ipynb) and [html](https://polarbearyap.github.io/speeddating_AI/source_code/html/source_code/source_code.html)

2. Report
   * Machine learning report in [PDF](report/report.pdf) format.

3. Pickle Maker
   * Pickle objects into the binary files.
   * Available in [ipynb](source_code/python/make_pickle.ipynb) and [html](https://polarbearyap.github.io/speeddating_AI/source_code/html/make_pickle.html)
   
4. [pickles](pickles)
   * Store objects into a binary file to reduce execution time.

## List of libraries used:
1. numpy
2. pandas
3. scikit-learn
4. matplotlib
5. seaborn
6. [pickle](https://docs.python.org/3/library/pickle.html)
7. python built-in libraries: re, time, itertools
8. [cleanipynb](https://pypi.org/project/cleanipynb)

> cleanipynb will cleanup your jupyter notebook by:
> - removing unused imports (globally)
> - moving all imports to the first cell and reordering them
> - reformatting your code with autopep8

## Source
* Published by: [Joaquin Vanschoren](https://www.openml.org/u/2) @ 2016 on https://www.openml.org/d/40536
   
* Available at:
  - [csv, arff](https://www.openml.org/data/get_csv/13153954/speeddating.arff)
  - [json](https://www.openml.org/d/40536/json)
  - [xml](https://www.openml.org/api/v1/data/40536)
  - [rdf](https://www.openml.org/d/40536/rdf)

## Relevant Paper
   * Raymond Fisman; Sheena S. Iyengar; Emir Kamenica; Itamar Simonson. Gender Differences in Mate Selection: Evidence From a Speed Dating Experiment.
   The Quarterly Journal of Economics, Volume 121, Issue 2, 1 May 2006, Pages 673–697, https://doi.org/10.1162/qjec.2006.121.2.673
