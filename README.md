# SalesRecord_GoogleBigQuery


## Description

This is a practice sales dataset of accessories having about 5 million records of data.

### Dependencies

* I have used Google Big Query for the execution of queries by signing up for FREE TIER GCP (Google Cloud Platform).

## Getting Started

* 1) This is how you can create a database which is called as a dataset in Google BigQuery

![U1](https://user-images.githubusercontent.com/72039550/149824725-7593b028-a193-404e-b19b-16da8741597e.png)

<hr>

* 2) This is how you can create tables
![U2](https://user-images.githubusercontent.com/72039550/149824922-b33593d5-cede-42b3-96fe-b971c7c208a1.png)

<hr>

* 3) An example of how to create **items_table**. 
![U3](https://user-images.githubusercontent.com/72039550/149825407-04f85b70-8937-444d-a260-d7fb8debad98.png)

* 4)  The following scrrenshot shows all the created tables

![U4](https://user-images.githubusercontent.com/72039550/149825639-9c515d32-4698-43c2-8817-2359a855a233.png)


<hr>
<hr>
<hr>


## Executing program

* The following query joins all the tables i.e. **region_table**, **items_table**, **order_table**, **total_table** and **items_table** (a total of 5 tables)

![Untitled1_query](https://user-images.githubusercontent.com/72039550/149822131-14191a12-8f65-4b7a-bee0-ed62a33fe5bb.png)

![Untitled1_output](https://user-images.githubusercontent.com/72039550/149822139-b799e5d6-6764-49db-9ff4-7a9ad1040529.png)


<hr>


* The following query joins both **sales_table** and **region_table**, with an aggregate function COUNT  on **sales_channel**

![Untitled2](https://user-images.githubusercontent.com/72039550/149822824-72d1b654-93d5-4cc7-94af-12dac1374a07.png)


<hr>


* The following query shows the country **"Rwanda"** has higher total_revenue and the data is sorted in descending order by **total_revenue** with an alias **TotalRevenue**

![Untitled3](https://user-images.githubusercontent.com/72039550/149823424-385d8b31-a996-4aee-986d-6cc55bbbdea3.png)


<hr>

* The following query shows **sales channel preference** between **"online"** and **"offline"**. It shows that although there is no much difference between the total profit, but **offline** channel seems to be a little higher. 
![Untitled4](https://user-images.githubusercontent.com/72039550/149823932-066ef6c0-1891-4b8a-b03b-dfa9aeeb70ae.png)

<hr>

* The following query gives the Average total cost of units that come across the regions (continent / division of continent).

![Untitled5](https://user-images.githubusercontent.com/72039550/149824349-9ecccabd-d2f1-4f70-82bd-1f21cab2c9d0.png)


<hr>


## Help

Any advise for common problems or issues.
```
command to run if program contains helper info
```

## Authors

Contributors names and contact info

ex. Dominique Pizzie  
ex. [@DomPizzie](https://twitter.com/dompizzie)

## Version History

* 0.2
    * Various bug fixes and optimizations
    * See [commit change]() or See [release history]()
* 0.1
    * Initial Release

## License

This project is licensed under the [NAME HERE] License - see the LICENSE.md file for details

## Acknowledgments
