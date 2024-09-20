# Alibaba Cloud Quiz - MaxCompute UDF

## Single Answer

1. Which statement is incorrect for UDF debug?

	A. It can be tested in two ways: unit test and local execution.  
	B. Need to specify the running data source when run UDF locally.  
	C. UDF/UDAF/UDTF typically works on some columns of the table in the SELECT clause, and needs to configure MaxCompute project, table, and column when run local test.  
	D. Warehouse is built locally to store tables (including meta and data) or resources for executing UDF locally.  
	E. The project name, tables, table name and sample data are under the warehouse directory in order.

	**Answer : ?**

2. Which statement is incorrect for user-defined function in MaxCompute?

	A. Like resource files, the same name function can only be registered once.  
	B. The Owner of the project space has the right to overwrite the system built-in function.  
	C. User-built function of ordinary user cannot overwrite the system built-in function.  
	D. Once the function is unregistered, the resources are deleted too.

	**Answer : ?**

3. The way UDF is used in MaxCompute is different from the common built-in functions in MaxCompute SQL.

	A. True  
	B. False

	**Answer : ?**

4. Which one is an incorrect method when Java UDF uses complex types?

	A. UDTF through @Resolve annotation to specify the signature.  
	B. UDAF through evaluate signature to map UDF input/output type.  
	C. UDF through evaluate signature to map UDF input/output type.  
	D. UDAF through @Resolve annotation to get the signature.

	**Answer : B**

5. Which one is an incorrect way to get signature from Java UDF?

	A. UDTF through @Resolve annotation to get the signature.  
	B. UDF through reflection analysis evaluate method to get signature.  
	C. UDF through @Resolve annotation to get the signature.  
	D. UDAF through @Resolve annotation to get the signature.

	**Answer : ?**

6. Which statement is incorrect when you use Java UDF?

	A. The code is added to the MaxCompute through the form of resources.  
	B. Java UDF must be packed as Jar format.  
	C. UDF framework can load Jar packets automatically.  
	D. After adding the Jar package, this UDF is ready for use.

	**Answer : C?**

7. Which limitation is not related to UDTF?

	A. No other expressions are allowed in the same SELECT clause.  
	B. No other expressions are allowed in the same SELECT clause.  
	C. It can be used in where filtering conditions.  
	D. No support use with distribute by together in same SELECT clause.

	**Answer : C ?**

8. UDTF (User Defined Table Valued Function) is used to solve scenarios which output multi-line data by a function call. It is also the only UDF which can return multiple fields.

	A. True  
	B. False

	**Answer : ?**

9. The NULL value in SQL is represented by a NULL reference in Java. Therefore, Java primitive types are not allowed because they cannot represent a NULL value in SQL.

	A. True  
	B. False

	**Answer : A**

10. Which one is not included in MaxCompute user-defined functions?

	A. UDF  
	B. UDAF  
	C. UDGF  
	D. UDTF

	**Answer : C**

11. When developing UDFs in MaxCompute, the corresponding data type and return data type in Java are objects, and the initial letter must be capitalized.

	A. True  
	B. False

	**Answer : A**

12. UDF outputs a return value at a time, while UDTF can output more than two records at one time.

	A. True  
	B. False

	**Answer : A?**

13. For UDAF (User Defined Aggregation Function), input and output have a many-for-one relationship.

	A. True  
	B. False

	**Answer : A**

## Multiple Answer

1. myudf_lower() is a UDF (user-defined function). The table is t_test (name string). Which of the following statements are correct?

	A. SELECT myudf_lower(name) FROM t_test;  
	B. SELECT * FROM t_test WHERE myudf_lower(Aaa) = name;  
	C. SELECT * FROM t_test WHERE myudf_lower(name) = 'bdps';  
	D. SELECT * FROM t_test WHERE myudf_lower(myudf_lower(name)) = 'zzzz';

	**Answer : A, C & D ?**

2. Which of the following UDF (user-defined function) statements in MaxCompute are correct?

	A. Function input and output are one-to-one.  
	B. Return a scalar value of a specified type.  
	C. Cannot be used with other functions.  
	D. It can be used in WHERE filtering conditions.

	**Answer : ?**

3. Which UDF implementation logic statements are correct?

	A. To implement UDF, the class com.aliyun.odps.udf.UDF must be inherited and the evaluate method must be applied.  
	B. The parameter type and return value type of the evaluate method are considered as UDF signature in SQL.  
	C. To call UDF, the framework must match the correct evaluate method according to the parameter type called by UDF.  
	D. The evaluate method must be a static public method.  
	E. User can implement multiple evaluate methods in UDF.

	**Answer : ?**

4. myudf_vertical is a UDTF. Which of the following usages are incorrect?

	A. SELECT myudf_vertical(name, score) AS (name, score) FROM t_udtf GROUP BY name, score;  
	B. SELECT myudf_vertical(name, score) AS (name, score) FROM t_udtf;  
	C. SELECT myudf_vertical(myudf_vertical(name, score)) AS (name, score) FROM t_udtf;  
	D. SELECT 1, myudf_vertical(name, score) AS (name, score) FROM t_udtf;

	**Answer : ?**

5. Which of the following UDAF statements in MaxCompute are correct?

	A. A plurality of input records can be aggregated into one output value, and then output it.  
	B. It does not support the use with group by together in the same select clause.  
	C. Can't use with group by together in SQL.  
	D. The syntax of UDAF in SQL is the same as that of common built-in aggregate function.

	**Answer : ?**

6. Which UDTF implementation logic statements are correct?

	A. To implement UDF, we need to inherit the com.aliyun.odps.udf.UDTF class.  
	B. To implement UDF, we need to inherit the com.aliyun.odps.udf.UDTF class.  
	C. @Resolve() defines the function input/output parameters data type.  
	D. When invoking UDTF, the input parameter can be not consistent with @Resolve definition.

	**Answer : C ?**

7. Which of the following UDTF statements are correct?

	A. It does not support the use with group by together in the same SELECT clause.  
	B. It supports the use with distribute by together in the same SELECT clause.  
	C. Supports other expressions in the same SELECT clause.  
	D. It does not support the use with sort by together in the same SELECT clause.

	**Answer : A, C & D?**

8. Which UDF implementation logic statements are correct?

	A. To implement UDF, the class com.aliyun.odps.udf.UDF must be inherited and the evaluate method must be applied.  
	B. The parameter type and return value type of the evaluate method is considered as UDF signature in SQL.  
	C. To call UDF, the framework must match the correct evaluate method according to the parameter type called by UDF.  
	D. The evaluate method must be a static public method.  
	E. User can implement multiple evaluate methods in UDF.

	**Answer : A, B, C & E ?**

9. Which UDAF implementation logic statements are correct?

	A. The main logic of UDAF relies on these three interfaces: iterate, merge, and terminate.  
	B. To implement UDAF we need to inherit the com.aliyun.odps.udf.Aggregator class.  
	C. Need to implement interfaces. Eg setup, newBuffer, iterate, terminate, merge, close, and so on.  
	D. Don't support user-defined Writable buffer

	**Answer : A, B & C ?**

10. Which of the following ways of UDTF usage in SQL are correct?

	A. SELECT user_udtf(col0, col1, col2) AS (co, c1) FROM my_table;  
	B. SELECT user_udtf(col0, col1, col2) AS (co, c1), col3 FROM my_table;  
	C. SELECT user_udtf(col0, col1, col2) AS (co, c1) FROM (SELECT * FROM my_table DISTRIBUTE BY key SORT BY key) t;  
	D. SELECT reduce_udtf(col0, col1, col2) AS (co, c1) FROM (SELECT col0, col1, col2 FROM (SELECT map_udtf(a0, a1, a2, a3) AS (col0, col1, col2) FROM my_table) t1 DISTRIBUTE BY col0 SORT BY col0, col1) t2;

	**Answer : A, B & C ?**

11. Which of the following UDF (user-defined function) statements in MaxCompute are correct?

	A. Function input and output are one to one.  
	B. Return a scalar value of a specified type.  
	C. Cannot be used with other functions.  
	D. It can be used in WHERE filtering conditions.

	**Answer : A, B & D ?**