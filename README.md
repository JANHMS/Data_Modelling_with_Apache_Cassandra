# <u>Data Engineer nanodegree / Udacity project : data modelling with Cassandra</u>
## Table of Contents
1. [Project info](#project-info)
2. [Files info](#files-info)
3. [How to scripts run](#pre-requisite)


***

### Project info

Sparkify, a startup, wants its analytics team to analyse the data collected on songs and user activity from its music streaming app.
The data are stored in a folder of csv files.
The purpose of this project is to model the data by creating tables in Apache Cassandra to run queries in order to answer 3 questions.
Jupyter notebook is the selected solution here to perform some data science realted tasks to answer the desired questions.

The steps of the process are :
- load the csv files stored in `event_data` folder,
- produce a single file `event_datafile_new.csv` containing all the data from the csv files with the columns described in `/images/image_event_datafile_new.jpg"`

***
### Files info

* `event_data` folder contains the csv files
* `/images/image_event.jpg"` contains the columns expected in the output file `event_datafile_new.csv`.
* `event_datafile_new.csv` is the csv file containing all the data collected from csv files in folder `/event_data` .
* `Project_cassandra_modelling.ipynb` is the jupyter notebook that loads the csv data  into Cassandra database and runs the queries to answer the 3 questions raised.

***
### How to scripts run

* Create a [Cassandra database](https://medium.com/@manishyadavv/how-to-install-cassandra-on-mac-os-d9338fcfcba4)
* Install cassandra driver for python.
* Run through the scriptL `Project_cassandra_modelling.ipynb`.

***
