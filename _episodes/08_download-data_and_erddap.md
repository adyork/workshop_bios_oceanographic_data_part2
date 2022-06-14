---
title: "Downloading data using ERDDAP"
teaching: 25
exercises: 10
questions:
- "How do I search for data in ERDDAP?"
- "What information does a dataset hold?"
- "How can I subset a dataset?"
- "How do I make a graph in ERDDAP?"
objectives:
- "Understand all the different factors for reusing online data with ERDDAP"
keypoints:
- "Searching an ERDDAP data catalog can be done using a web page"
- "Data can be downloaded in different file formats"
- "Constraints can be added to a dataset search"
---
# Exploring an ERDDAP data catalog

### What is ERDDAP?

When scientists make their data available online for people to re-use  it, there can often still be barriers that stand in the way of easily  doing so. Reusing data from another source is difficult:

- different way of requesting data
- different formats: you work with R while colleague is working with Matlab and the other one with python
- Need for standardised metadata

**This is where ERDDAP comes in.** It gives data  providers the ability to, in a consistent way, download  subsets of  gridded and tabular scientific datasets in common file formats and make  graphs and maps.

<img src="../fig/erddap.png" alt="erddap" style="zoom:20%;" />



There is no “1 ERDDAP server”, instead organisations and repositories  have their own erddap server to distribute data to end users. These  users can request data and get data out in various file formats.  Many  institutes, repo’s and organizations (including [NOAA](https://coastwatch.pfeg.noaa.gov/erddap/index.html), [NASA](https://podaac-uat.jpl.nasa.gov/erddap/index.html), and [USGS](https://geoport.usgs.esipfed.org/erddap/index.html)) run ERDDAP servers  to serve their data.

BCO-DMO has its own erddap server that is continuously being updated. We added ERDDAP badges to make it easy for new users to grab the dataset in the format they need.

<img src="../fig/erddap-bats.png" alt="erddap-bcodmo" style="zoom:30%;" />

## Downloading Data

For this exercise we will try to download the data from the BATS that serve at BCO-DMO.

[https://www.bco-dmo.org/dataset/3918](https://www.bco-dmo.org/dataset/3918)



## Dataset information

Within the search results you have access to information about each dataset to help you decide with which dataset is useful for your application.  

![image-20211026190530727](../assets/img/image-20211026190530727.png)



The listing (pictured above) gives access to a lot of information about the dataset. In a browser, try the following:
* Mouse over the question mark `?` under **Summary** to get an overview of the dataset.
* Click **"Background info"** to get more complete information from the data provider about the dataset. Now go back to the search results page.
* Click the `"M"` under **"ISO,Metadata"** to see all of the dataset metadata. A lot of information is displayed. Some important fields are:
  * Global attributes (general metadata) vs variable attributes (variable names & units)
  * `"geospatial_lat_min"`, `"geospatial_lat_max"`, `"geospatial_lon_min"`, and `"geospatial_lon_max"` for the spatial coverage
  * `"references"` for citing the dataset in publications
  * `"license"` for restrictions on using the data
  * `"acknowledgement"` often used to describe how to acknowledge use of the dataset
  * time: ERDDAP standardizes the dates+times in the results.  Data from other data servers is hard to compare    because the dates+times often are expressed in different formats    (for example, "Jan 2, 2018", 02-JAN-2018, 1/2/18, 2/1/18,    2018-01-02, "days since Jan 1, 1900").  For string times, ERDDAP always uses the ISO 8601:2004(E) standard format,    for example, 2018-01-02T00:00:00Z.  For numeric times, ERDDAP always uses "seconds since 1970-01-01T00:00:00Z".  ERDDAP always uses the Zulu (UTC, GMT) time zone to remove the difficulties    of working with different time zones and standard time versus daylight saving time.


These standardised variables are important for the dataset to be able to be "read" by other end-users and machines.

For example Google dataset search:

* open google dataset search: https://datasetsearch.research.google.com/

* search for the dataset id of the dataset above: bcodmo_dataset_783911

  ![image-20211026155703527](../assets/img/image-20211026155703527.png)



## Subsetting data



<img src="../fig/erddap-subsetdata.png" alt="erddap-subset" style="zoom:30%;" />



Click on the data button. Here is the link to the dataset in erddap: https://erddap.bco-dmo.org/erddap/tabledap/bcodmo_dataset_783911.html  

![image-20211026193729341](../assets/img/image-20211026193729341.png)

### Set the file type 

### Download the data "Submit"



