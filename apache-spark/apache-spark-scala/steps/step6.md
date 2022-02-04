Let us now get familiar and start writing some Scala code to get acquainted with Scala syntax and basic programming constructs.

**Step 1:** Go into the Scala console by running `scala`. 

Once you see the scala prompt, enter the following piece of code.

`val name: String = "Opswerks Academy"` 

The above line of code is used to declare an immutable variable named name of type String which has a value of Opswerks Academy. The keyword val is used to declare a variable which is immutable. When val is used, the created variable can no longer be changed or modified. Scala encourages to use immutability whenever possible. This will help you track your code easily and the values do not get modified accidentally when referring them programmatically. Unlike other languages, the name of the variable is declared first and then the data type is declared separated by a colon (:) in Scala. 

![](https://github.com/dynbn/katacoda-scenarios/blob/main/apache-spark/apache-spark-scala/screenshots/spark-scala-val.png?raw=true)

You can now use the variable name and use it inside the println function as shown below. This will print the value (String) associated with the variable (which is Opswerks Academy in this case) to the console.

`println(name)` 