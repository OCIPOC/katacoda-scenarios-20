**Step 3:** Let us run a job. Create a List of few numbers and create an RDD from that list as shown below.

**Note:** You might need to get back to prompt by pressing `Enter`.

```
19/10/05 16:25:21 WARN HttpParser: bad HTTP parsed: 400 Illegal character 0x16 for HttpChannelOverHttp@3006dd4d{r=0,c=false,a=IDLE,uri=null}
scala>
```
`val num = List(1, 2, 3, 4)` 

`val numRDD = sc.parallelize(num)` 

Now let us write a map function which takes the numRDD and gives a squaredRDD as shown below.

`val squaredRDD = numRDD.map(x => x * x)` 

`squaredRDD.foreach(println)` 

After you see the output in the console, navigate back to the browser and refresh the Spark web interface. You should see a completed job as shown in the screenshot below.
