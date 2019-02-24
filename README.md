# pyspark_db_connect
Tutorial on how to connect to an external database with PySpark

## Overview
In this example we will be connecting a postgresql and mysql server but you can connect to any sql server type you like.

All you need to do is:

1. Find the jdbc driver jar for that sql server type that you are trying to read from.
2. Locate the **spark** folder you installed.
3. Locate the **jars** folder in the root of the **spark** folder.
4. Move the jar file into the **jars** folder.

Once you have done this you will be able to follow the notebook example with ease. Just rememeber to change the server type in the _url_ parameter.
