**Step 2:** Let us install Spark in Standalone mode. Navigate to the download URL below, select the latest stable version for Spark (i.e. Spark 3.2.0) and select the package type which is pre-built for Apache Hadoop 3.2 and later. After selecting click the link as shown in the screenshot below to download Spark.

Download URL : http://spark.apache.org/downloads.html

**Note:** Run the following command to install `wget`

`apt-get install wget`

Download the latest version of Spark

`wget https://www.apache.org/dist/spark/spark-3.2.1/spark-3.2.1-bin-hadoop3.2.tgz`

After running the above command, your download should start. The download may take a while depending upon your internet connection.

**Step 3:** The download will be saved in the current directory by default. You may optionally check if Spark has been downloaded using the ls command.

`ls`