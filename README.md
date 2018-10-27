# sqoop2
Workouts with Sqoop2

## Import Data to HDFS from MySQL  
Using Sqoop2 for importing data to HDFS is actually pretty simple. All you need is connector, links and a job -and the shell too :) -.  
When creating links, pay attention to link names since sqoop2 shell will guide you for setting different parameters based on link name
  
* Connect to the sqoop2 shell  
![](https://github.com/emirkorkmaz/sqoop2/blob/master/misc/images/sqoop2-1.png)  

* Check the connectors, we need built-in generic jdbc and hdfs connectors  
![](https://github.com/emirkorkmaz/sqoop2/blob/master/misc/images/sqoop2-2.png)  

* Create a link to HDFS specifying the address of our HDFS cluster  
![](https://github.com/emirkorkmaz/sqoop2/blob/master/misc/images/sqoop2-3.png)  

* Create a link to relational database -mysql for our case- specifying the data to be fetched  
![](https://github.com/emirkorkmaz/sqoop2/blob/master/misc/images/sqoop2-4.png)  
![](https://github.com/emirkorkmaz/sqoop2/blob/master/misc/images/sqoop2-5.png)  

* Create a job, remember jobs are based on links. that's why we are pointing from and to  
![](https://github.com/emirkorkmaz/sqoop2/blob/master/misc/images/sqoop2-6.png)  
![](https://github.com/emirkorkmaz/sqoop2/blob/master/misc/images/sqoop2-7.png)  

* Submit the job  
![](https://github.com/emirkorkmaz/sqoop2/blob/master/misc/images/sqoop2-8.png)  

* Check the job status  
![](https://github.com/emirkorkmaz/sqoop2/blob/master/misc/images/sqoop2-9.png)  

* Check HDFS  
![](https://github.com/emirkorkmaz/sqoop2/blob/master/misc/images/sqoop2-10.png)  



