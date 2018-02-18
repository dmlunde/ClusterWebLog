ClusterWebLog - Web Log Clustering and Visualization
====================================================

This repository was created for a short demo for the [Austin Web Python meetup]( https://www.meetup.com/austinwebpythonusergroup/).

This repository visualizes and Analyzes MSNBC Web log data located in [UCI, Machine Learning Repository](http://archive.ics.uci.edu/ml/datasets/msnbc.com+anonymous+web+data). This data is available thanks to msnbc.com.

This application Handles: 

* Data Import – including reorganization 
* Data Visualization – with the intent of understanding how the data was handled 
* Detecting outliers – the system uses very basic k-means clustering to detect clusters and then locate outliers 



USAGE:
------

Download all files from this repository to a directory of choice and open a command prompt and enter that directory

Execute the command:
python AnalyzeWebLogMSNBC.py

The system will output the html file PairMatches.html

Open the file PairMatches.html in a web browser to view the map of the data correlations. Please make sure you are connected to the Internet to view the graphics.

The system will also output multiple Cluster*.csv files viewable in a spreadsheet. The spreadsheet will show the cluster center followed by all records that belong to that cluster sorted by distance from center.


DEPENDENCIES:
-------------

Dependant libraries are: pandas version 0.20.3, bokeh version 0.12.10, sklearn version 0.19.1. numpy version 1.13.3.

This code was tested on Windows 10 with python 2.7.14 on Anaconda 64 bit version 5.0.1

It is recommended you use Anaconda, yet other python environments and library versions may work as well.



FILES:
------

### Application file:
* README.md: the file you are reading now
* AnalyzeWebLogMSNBC.py: the Python code


### Data Files extracted from [UCI, Machine Learning Repository](http://archive.ics.uci.edu/ml/datasets/msnbc.com+anonymous+web+data):
* msnbc990928.seq: The main data file as extracted from the msnbc990928.seq.gz file that exists. This data is available thanks to msnbc.com
* description.txt: The description of the dataset

### Output files are archived in OutputOfAnalyzeWebLogMSNBC.zip
* PairMatches.html - the visualization of the correlation map generated by bokeh - opened using a web browser
* Cluster*.csv - several files representing the significant clusters of users located by the system - open using a spreadsheet application


VERSION HISTORY:
----------------
Development started on 3-Feb-2018.
Uploaded to Github on 18-Feb-2018 - no version number assigned


DEVELOPER CONTACT INFO:
-----------------------

Please pass questions to:

Jacob Barhak Ph.D.

Email: jacob.barhak@gmail.com

http://sites.google.com/site/jacobbarhak/



ACKNOWLEDGEMENTS:
-----------------

This data is available thanks to msnbc.com

Data availability attributed to: 
Lichman, M. (2013). UCI Machine Learning Repository [http://archive.ics.uci.edu/ml]. Irvine, CA: University of California, School of Information and Computer Science.


LICENSE
-------

The Data Files were extracted from the [UCI, Machine Learning Repository](http://archive.ics.uci.edu/ml/datasets/msnbc.com+anonymous+web+data) the only requirement stated for this data was attribution according to this [citation policy](https://archive.ics.uci.edu/ml/citation_policy.html). This data is available thanks to msnbc.com

The jupyter notebook python code is under the GPL License.

Copyright (C) 2018 Jacob Barhak
 
This file is part of the ClusterWebLog . ClusterWebLog is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

ClusterWebLog is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.

See the GNU General Public License for more details.


