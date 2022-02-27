**Step 3:** Let us now use filter function using the contains method and filter out an RDD which satisfies the filter criteria. Create a new list as shown below and then filter out a string.

`val office = List("Michael", "Jim", "Pam", "Dwight", "Angela")` 

`val officeRDD = sc.parallelize(office)` 

`val jim = officeRDD.filter(name=> name.contains("Jim"))` 

`jim.collect` 


The filter function we used above is a higher order function which takes another function as parameter and returns an RDD of type String. The name => name.contains("jim") is similar to a function in Scala as shown below.

```def find(name: List[String]): Boolean = {
	name.contains("Jim")
	}```

Let's call the function with the parameter office which is a List of type String.

`find(office)` 