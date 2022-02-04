**Step 1:** Let us create an RDD using the parallelize keyword. Fire up the spark-shell from the terminal and create a list as shown below.

`spark-shell`

`val office = List("Michael", "Jim", "Pam", "Dwight", "Angela")` 

Now, let us use the parallelize keyword and create an RDD for the list we have created above.

`val officeRDD = sc.parallelize(office)` 

You have created your first RDD successfully. Please note that we are using the sc which is the object of Spark Context. The sc object is automatically created when we launch the Spark Shell as shown in the screenshot below. This is the reason we are able to access sc and use Spark Context.