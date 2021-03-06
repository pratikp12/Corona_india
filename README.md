# Corona_india
Tabular and graphical representation of data related to corona
I am Using 2 python packages 
 Pandas
 Matplotlib

# Pandas 
pandas aims to be the fundamental high-level building block for doing practical, real world data analysis in Python. Additionally, it has the broader goal of becoming the most powerful and flexible open source data analysis / manipulation tool available in any language.

Library Highlights
A fast and efficient DataFrame object for data manipulation with integrated indexing;

Tools for reading and writing data between in-memory data structures and different formats: CSV and text files, Microsoft Excel, SQL databases, and the fast HDF5 format;

Intelligent data alignment and integrated handling of missing data: gain automatic label-based alignment in computations and easily manipulate messy data into an orderly form;

Flexible reshaping and pivoting of data sets;

# Matplotlib
![](images/matplotlib.PNG)
Matplotlib is a comprehensive library for creating static, animated, and interactive visualizations in Python.

## Installation
You can find the installation documentation for the
[Jupyter platform, on ReadTheDocs](https://jupyter.readthedocs.io/en/latest/install.html).
The documentation for advanced usage of Jupyter notebook can be found
[here](https://jupyter-notebook.readthedocs.io/en/latest/).

For a local installation, make sure you have
[pip installed](https://pip.readthedocs.io/en/stable/installing/) and run:

    $ pip install notebook
# dataset 
i used corona dataset which is available on Kaggle website 
download link here
https://www.kaggle.com/sudalairajkumar/covid19-in-india
# Coron story of india 

 The first case of the corona in India was found in Kerala on 30 January 2013
 
![](images/1st_case.PNG)
In Januaray and Februry corona crisis was not severe 

we only want to work on data realted to 2nd May 2012 so i use following commands to limit the rows 
covid_latest=covid1[covid1['Date']=='02/05/20']

sort data based on Confirm case

![](images/sort1.PNG)




now sort data in descending order and find state having highet no. of case(Top 10 states)

![](images/sort2.PNG)

Maharashtra state have highest death of corona 
 
![](images/death.PNG)

Grapgh showing top 10 states in India with confirmed cases

![](images/graph.PNG)

Lets c Maharashtra state Graph
![](images/maharashtra.PNG)

<b>Mahrashtra state Corona cases are increasing with time <b>
    
<i>Goa state graph shows today there is no new case of corona<i>
![](images/goa.PNG)

<i>Manipur state with only 2 cases also maintain good grapgh<i>
![](images/manipur.PNG)

# conclusion
![](images/conclusion.PNG)

<b>North-eastern states and goa did best perfomance against corona<b>
 ## Read my medium blog 
 https://medium.com/@pratikmpatil12/corona-story-of-india-6b09e303e6b3?sk=3c8a9725c8dfadba0839c8fdd7910bb3
