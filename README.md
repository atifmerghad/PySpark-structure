## PySpark code structure for production

<p>
 In addition to pyspark, Scala is also widely used for data processing on Spark.

  We need to strucutre our project !
</p>

Folder Structure:

<pre>
pyspark
  | requirements.txt
  | Makefile
  | spark_submit.sh
  | src
  |  | jobs 
  |  |   | JobName
  |  |   | init.py
  |  |   |    | Jobname.py
  |  |   |    | init.py
  |  |   |    | resources
  |  |   |         | JobConfig.json
  |  |   | Shared
  |  |   |    | init.py
  |  |   |    | context.py
  |  |   | config.json
  |  |   | log4j.properties
  |  |   | logging.json
  |  |   | main.py
  | tests 
     | jobs 
         | JobName
             | JObTest.py
</pre>
