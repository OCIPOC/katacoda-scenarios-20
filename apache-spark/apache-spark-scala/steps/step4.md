Now that we have installed Java, we are ready to install Scala and start writing some Scala code!

**Note:** Run the following command to install `wget` (in case you encounter "command not found" error)

`apt-get install wget`

**Step 1:** Run the following commands from the terminal to install Scala.

`wget www.scala-lang.org/files/archive/scala-2.13.8.deb`

`dpkg -i scala-2.13.8.deb`


**Step 2:** Verify your Scala installation version by running the following command.
 
`scala -version`

You will get following output.

```
Scala code runner version 2.13.8 -- Copyright 2002-2021, LAMP/EPFL and Lightbend, Inc.
```