# SalesRecord_GoogleBigQuery


## Description

This is a practice sales dataset of accessories having about 5 million records of data.

### Dependencies

* I have used Google Big Query for the execution of queries by signing up for FREE TIER GCP (Google Cloud Platform).

## Getting Started


### Executing program

* The following query joins all the tables i.e. **region_table**, **items_table**, **order_table**, **total_table** and **items_table** (a total of 5 tables)

![Untitled1_query](https://user-images.githubusercontent.com/72039550/149822131-14191a12-8f65-4b7a-bee0-ed62a33fe5bb.png)

![Untitled1_output](https://user-images.githubusercontent.com/72039550/149822139-b799e5d6-6764-49db-9ff4-7a9ad1040529.png)


* The following query joins both **sales_table** and **region_table**, with an aggregate function COUNT  on **sales_channel**

![Untitled2](https://user-images.githubusercontent.com/72039550/149822824-72d1b654-93d5-4cc7-94af-12dac1374a07.png)


* The following query shows the country **"Rwanda"** has higher total_revenue and the data is sorted in descending order by **total_revenue** with an alias **TotalRevenue**

![Untitled3](https://user-images.githubusercontent.com/72039550/149823424-385d8b31-a996-4aee-986d-6cc55bbbdea3.png)



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
