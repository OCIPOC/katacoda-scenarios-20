Create a List of few numbers and create an RDD from that list as shown below.

```val num = List(1, 2, 3, 4)
val numRDD = sc.parallelize(num)```
Now let us write a map function which takes the numRDD and gives a squaredRDD as shown below.
`val squaredRDD = numRDD.map(x => x * x)` 
`squaredRDD.foreach(println)` 
 
`numRDD.map(x => x * x)` 
is same as
```def square(x: Int): Int = {
	x * x
}
numRDD.map(square)``` 