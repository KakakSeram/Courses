# Alibaba Cloud DataWorks Basic Knowledge Quiz Compilation

## Single Answer

1. Which of these DataWorks roles has permission to deploy Workflows but not to edit them?
	
	A. Developer  
	B. Deployer  
	C. Visitor  
	D. Project administrator

	**Answer : B ?**

2. Which of these functions is not provided by DataWorks?
	
	A. Visualization  
	B. Job Scheduling  
	C. Built-in Workflow Editor  
	D. Monitoring and Alarms

	**Answer : A ?**

3. Which of these permissions is NOT granted to the OAM role in DataWorks?
	
	A. Maintenance users are granted with permissions by the project administrator.  
	B. Maintenance users have release permissions.  
	C. Maintenance users can create workflows.  
	D. Maintenance users have online maintenance permissions.

	**Answer : B ?**

4. Which of these is NOT a type of object within a DataWorks project?
	
	A. Table Schema  
	B. Resource  
	C. Job  
	D. Workflow

	**Answer : B ?**

5. Alibaba Cloud DataWorks only works with MaxCompute.
	
	A. True  
	B. False

	**Answer : B ?**

6. Workflows in DataWorks have a type of node called a "Zero-load Node" which does no work but can be used to indicate the start of a Workflow or to connect other Nodes together.
	
	A. True  
	B. False

	**Answer : B ?**

7. The "Developer" role in DataWorks can add other users to a Workspace, as long as they are also assigned the "Developer" role.

	A. True  
	B. False

	**Answer : B ?**

8. Which of these is NOT a permission that DataWorks grants to the Developer role?
	
	A. Developers can create Workflows.  
	B. Developers can manage data sources within the DataWorks Workspace (i.e. can add/remove data sources).  
	C. Developers can create new script files and new UDF functions.  
	D. Developers can publish packages.

	**Answer : B ?**

9. When using MaxCompute with DataWorks, it is possible to create and run multiple types of jobs on top of MaxCompute, including MaxCompute SQL Jobs, MapReduce Jobs, and Spark jobs.
	
	A. True  
	B. False

	**Answer : A ?**

10. Which of these is NOT a time interval supported by DataWorks?
	
	A. Daily  
	B. Hourly  
	C. Quarterly  
	D. Monthly

	**Answer : C ?**

11. Which of these statements about the Project administrator role in DataWorks is correct?
	
	A. When adding users to a DataWorks Workspace, the Project administrator can only add RAM users under the current account  
	B. When adding users to a DataWorks Workspace, the Project administrator can add other Alibaba Cloud accounts as users, but not RAM users under the current account  
	C. The Project administrator does not have permission to edit Workflows  
	D. The Project administrator can add users to a Workspace, but not remove them

	**Answer : B ?**

## Multiple Answer

1. Which of these are techniques you can use to debug DataWorks Workflows, if they fail to run? (Number of correct answers: 2)
	
	A. Look at the logs for the failed node(s) in the workflow: they usually contain helpful information  
	B. Step through your Workflow one node at a time, and use an Ad-hoc MaxCompute SQL node to check the table(s) output by each step to ensure there are no data quality issues  
	C. Buy a third party debugging tool  
	D. Use the MaxCompute command-line tool to run your code instead of DataWorks

	**Answer : A & B ?**

2. Which of these are good reasons to choose Standard Mode over Basic Mode, when setting up a new DataWorks Workspace? (Number of correct answers: 2)
	
	A. DataWorks Workspaces in Standard Mode can provide more fine-grained user permissions because it is possible to separate Development from Production  
	B. DataWorks Workspaces in Standard Mode cost less  
	C. Workspaces in Standard Mode allow developers to test code first before deploying it into production  
	D. Code runs faster in Standard Mode

	**Answer : A & C ?**

3. Which of these statements about MaxCompute is true? (Number of correct answers: 2)
	
	A. MaxCompute charges an up-front monthly fee for data storage  
	B. MaxCompute tables are designed to be appended to, but existing records cannot be updated (SQL UPDATE and DELETE are not supported)  
	C. MaxCompute has its own SQL language dialect, called "ODPS SQL" or sometimes "MaxCompute SQL"  
	D. MaxCompute is the same thing as Hadoop Hive

	**Answer : B & C ?**

4. Which of these are "compute engines" that DataWorks can work with? (Number of correct answers: 3)
	
	A. MaxCompute  
	B. HBase  
	C. AnalyticDB  
	D. E-MapReduce (EMR)

	**Answer : A, C & D**