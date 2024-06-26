![497751562394501](https://github.com/vnaumq/pet_projects/assets/147442501/97d1617b-c456-4ffe-87f5-4da273ef83a4)

<div id="badges" align="center">
  
[![GitHub last commit](https://img.shields.io/github/last-commit/vnaumq/pet_projects.svg)](https://github.com/vnaumq/pet_projects) 
![ViewCount](https://views.whatilearened.today/views/github/vnaumq/pet_projects.svg?cache=remove)

</div>

<h1 align="center" style="color:White">Introduction</h1>







Hi, this is a repository of work I do in my spare time to pump up my skills.

All data was taken from public sources, so I added CSV files to each project folder.

The projects are done based on my current skills. So if I learn something new and can apply it to previously learned data, I will add to the projects.

<h1 align="center" style="color:White">Pet projects</h1>

Name|Description | Stack
-----------|:-------:|:--------:
[Proxy ETL]()|This project implements the process of parsing proxies from https://free-proxy-list.net/ and loading the resulting data into a BigQuery table in Google Cloud. It uses Apache Airflow to schedule and execute tasks as a Directed Acyclic Graph (DAG).| python, pandas, requests, BeatifulSoup, Apache Airflow, ping3, BigQuery, Docker
[Supermarket sales](https://github.com/vnaumq/supermarket_sales)|In this study I have analyzed the sales of three supermarkets. I analyzed each product line individually. I also analyzed sales by month, by day of the week and by week. In this study I did a lot of work with time. I converted date as in weeks, months, days, days of the week and time as in hours. Also built a lot of graphs: pie, barplot, lineplot, histplot, relplot. Figured out the percentages of different payment methods. The jupyter notebook describes everything, what which part of the code does what.| python, pandas, matplotlib, seaborn, Tableau
[Bookings](https://github.com/vnaumq/bookings/tree/main) | All data analysis is stored in a jupyter notebook. Only used pandas. I practiced writing code to change columns and calculate other metrics. In some places an alternative solution to the problem is presented.   | python, pandas
[Exam Scores](https://github.com/vnaumq/EXAM-SCORES)| The dataset Students Performance in Exams is taken from the platform Kaggle. This data set consists of the marks secured by the students in various subjects. Purpose: To understand how students' academic performance is affected by their parents, test preparation, etc. | SQL, python, pandas, matplotlib
[Fake News](https://github.com/vnaumq/FAKE-NEWS)| The purpose of this study is to see the percentage of fake and true news on a sample of news. And also to find out the names of the most famous liars and the most honest people. Only applied SQL here.| SQL
[Dashboard Germany](https://github.com/vnaumq/Dashboard-Germany-)|his dashboard is made in Excel with the help of pivot tables. The data is taken from the internet for 8 cities in Germany. The dashboard presents data: revenue by month, shares of regions, categories, top 10 products, customers. There are also slices by year, region and city. Each chart is on a separate pivot table and on a separate sheet . This is for convenience and for quick changes to the dashboard.| Excel


<h1 align="center" style="color:White">Requirements</h1>

Basic development tools:

* Python3 programming language and its libraries:

    + analytical library [Pandas](https://pandas.pydata.org/);

    + libraries for performing scientific and engineering calculations [NumPy](https://numpy.org/), [math](https://docs.python.org/3/library/math.html), [SciPy](https://scipy.org/);

    + libraries for data visualization [Matplotlib](https://matplotlib.org/), [seaborn](https://seaborn.pydata.org/), [plotly](https://plotly.com/python/);

    + auxiliary libraries [datetime](https://docs.python.org/3/library/datetime.html), [display](https://ipython.org/ipython-doc/3/api/generated/IPython.display.html), [warnings](https://docs.python.org/3/library/warnings.html), [requests](https://pythonru.com/biblioteki/kratkoe-rukovodstvo-po-biblioteke-python-requests);

* programming environment [Jupyter Notebook](https://jupyter.org/);

* query language (SQL).

* Docker
