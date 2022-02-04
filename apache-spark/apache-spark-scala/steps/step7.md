You can check if the declared variable is immutable by trying to append a new String to the name variable which we created previously as shown below.
 

`name = name + " 2022"` 

![](https://github.com/dynbn/katacoda-scenarios/blob/main/apache-spark/apache-spark-scala/screenshots/spark-scala-val-error.png?raw=true)

As you can see from the screenshot above, it throws an error saying reassignment to val, which means you cannot reassign or modify an immutable variable.