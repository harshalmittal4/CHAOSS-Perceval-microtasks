# CHAOSS-Perceval-microtasks
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/harshalmittal4/CHAOSS-Perceval-microtasks/master)

This repository contains microtasks to achieved for CHAOSS GSoC Idea #2 :<br/> **Implementing CHAOSS metrics with Perceval [Details](https://github.com/chaoss/wg-gmd/issues/81)**.<br/>
([Launch with Binder](https://mybinder.org/v2/gh/harshalmittal4/CHAOSS-Perceval-microtasks/master))

***

### #Microtask 0
>Using [](https://github.com/chaoss/wg-gmd/blob/master/implementations/Code_Changes-Git.ipynb) ([See in MyBinder](https://mybinder.org/v2/gh/chaoss/wg-gmd/master?filepath=implementations/Code_Changes-Git.ipynb)) as an example, produce one notebook per data source (git, GitHub/GitLab issues, GitHub pull requests / GitLab merge requests) showing a summary of the contents of that file (number of items in it, and number of different identities in it counting authors/committers for git, submitters for issues and pull/merge requests). This microtask is mandatory, to show that you can retrieve data and produde a notebook showing it. In each notebook, include also the list of repositories retrieved, and the date of retrieval, using data available in the JSON file.

The task is completed [here](./microtask0).

***

### #Microtask 1
>Produce a notebook showing (and producing) a list with the activity per quarter: number of new committers, submitters of issues, and submitters of pull/merge requests, number of items (commits, issues, pull/merge requests), number of repositories with new items (all of this per quarter) as a table and as a CSV file. Use plain Python3 (eg, no Pandas) for this.

The task is completed [here](./microtask1).

***

### #Microtask 2
>Like Microtask 1, but now using [Pandas](http://pandas.pydata.org/).

The task is completed [here](./microtask2).

***

### #Microtask 3
>Produce a notebook with charts showing the distribution of time-to-close for issues already closed, and opened during the last year, for each of the repositories analyzed, and for all of them together. Use Pandas for this, and the Python charting library of your choice (as long as it is a FOSS module).

The task is completed [here](./microtask3).

***

### #Microtask 4
>Produce a listing of repositories, as a table and as CSV file, with the number of commits authored, issues opened, and pull/merge requests opened, during the last three months, ordered by the total number (commits plus issues plus pull requests). Use plain Python3 (eg, no Pandas) for this.

The task is completed [here](./microtask4).

***

### #Microtask 5
>Like Microtask 4, but now using [Pandas](http://pandas.pydata.org/).

The task is completed [here](./microtask5).

***

### #Microtask 6
>Perform any other analysis you may find interesting, based on the Perceval data you collected.

To be updated.

### To produce the results : 
1) Clone the repo. In the root of the directory, create a virtualenv and set   it to use python3 (in case default is python2):
```
$ python3 -m virtualenv venv
$ virtualenv --python=/path/to/yourpython3 venv
```

2) Activate the virtualenv.
```
source ./venv/bin/activate
```
3) Install the required packages.
```
$ pip install -r requirements.txt
```
4) Launch the jupyter kernel.
```
$ jupyter-notebook
```

The `readme.md` in each folder contains further information for that microtask.
