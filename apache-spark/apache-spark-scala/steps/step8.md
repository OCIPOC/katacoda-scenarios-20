Step 2: There might be scenarios where you would want to modify a variable. For that you can create a variable using var keyword instead of the val keyword as shown below.

var newName: String = "Opswerks"

newName = newName + " Academy"

println(newName)

![](https://github.com/dynbn/katacoda-scenarios/blob/main/apache-spark/apache-spark-scala/screenshots/spark-scala-var.png?raw=true)

As you can see in the screenshot, we have concatenated a new string to the same variable and printed out the new string to the console using mutability. Mutability should be only used when it is absolutely required for your application.

Step 3: We can apply a workaround to use transformations on immutable objects to create new immutable objects and achieve the same result as we got using the mutable objects.

val name: String = "Opswerks"

val newName: String = name + " Academy"

println(newName)

![](https://github.com/dynbn/katacoda-scenarios/blob/main/apache-spark/apache-spark-scala/screenshots/spark-scala-val2.png?raw=true)

As you can see from the screenshot above, we have applied the transformations on the immutable objects and achieve the same result as using the mutable objects.