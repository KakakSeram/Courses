# Alibaba Cloud Associate Big Data Exam

## Single Answer

1. In Dataworks, the Data Quality tool can _____

	A. Provide you whit high quality sample data for testing your Data  
	B. Run automated quality checks when DataWorks workflows are executed  
	C. Pre-check DataWorks workflows for coding errors  
	D. Prevent you from publishing DataService Data APIs if you data quality is too low

	**Answer : B**

2. The key steps in a data processing workflow are ____

	A. Data Import, data storage, data processing, and data analysis / visualization.  
	B. Data Import, data compession, data encryption, and data export.  
	C. Data processiong, machine learning, and data evaluation.  
	D. Data governance, data security, and data transport.
	
	**Answer : A**

3. Which DataWorks tool can help you discover and organize data sources?

	A. DataWorks Data Integration.  
	B. DataWorks DataOS.  
	C. DataWorks DataMap.  
	D. DataWorks DataService Studio.

	**Answer : C**

4. The recommended tool for creating and managing MaxCompute projects is.

	A. IntelliJ IDEA  
	B. DataWorks  
	C. odpscmd (MaxCompute CLI)  
	D. aliyun (Alibaba Cloud CLI)

	**Answer : B**

5. When using Data Works, Alibaba Cloud recommends users access the DataWorks console using the web browser.
	
	A. Internet Explorer  
	B. Safari  
	C. Firefox  
	D. Google Chrome.

	**Answer : D**

6. You have a heavily customized Machine Learning workflow running on Hadoop. Which Alibaba Cloud Big Data service will be the easiest for you to migrate to, requiring the fewest changes to your environment?
	
	A. MaxCompute  
	B. AnalyticDB  
	C. E-MapReduce (EMR)  
	D. Function Compute

	**Answer : C**

7. You have imported some data into a DataWorks Workspace and are ready to start analyzing the imported data. Which tool in DataWorks is best suited to this task? Score 2
	
	A. Data Integration  
	B. Data Studio  
	C. Data Quality  
	D. DataService Studio

	**Answer : B**

8. One of the key features of DataWorks is the ability to schedule workflows to run according to a schedule. Which of these statements about DataWorks scheduling capabilities is NOT correct? Score 2
	
	A. Nodes (tasks) in a DataWorks Workflow can be configured to depend on one another: if an upstream node fails to run, downstream nodes which depend on the failed node will not be run.  
	B. DataWorks Workflows can contain a maximum of 10 nodes (tasks).  
	C. Workflows can be configured to run as frequently as once every 5 minutes.  
	D. After configuring a Workflow's schedule, the Workflow must be submitted to the scheduler, before it can be run.

	**Answer : B**

9. Which of these is NOT a built-in widget that you can add to an Alibaba Cloud DataV dashboard? Score 2 Mark
	
	A. Charts and graphs  
	B. Text  
	C. 2D and 3D maps  
	D. Textboxes (for text input)

	**Answer : D**

10. You have created a PAI DSW instance and have started developing a new TensorFlow project. Now, Score 2 you want to shut the instance down temporarily, while you focus on other tasks. Which of these is the best way to preserve the state of your DSW environment so you can resume work easily?
	
	A. Connect PAI DSW to an Alibaba Cloud NAS instance: files created in the PAI DSW environment will be saved there  
	B. You don't need to do anything: the environment will be saved automatically  
	C. You must download files locally, then re-upload when you resume your work  
	D. Save files from DSW to OSS, then re-load from OSS manually when you resume your work

	**Answer : A**

11. Which billing modes does Machine Learning Platform for Al (PAI) support? Score 2 Mark
	
	A. Pay-As-You-Go and Subscription  
	B. Subscription  
	C. Pay-As-You-Go  
	D. Fixed mode (Based on Elastic Compute Service (ECS) pricing)

	**Answer : C**

12. Which of these services allows you to deploy your completed machine learning models as RESTful APIs you can integrate into other services? Score 2 Mark
	
	A. PAI DSW (Data Science Workshop)  
	B. PAI Studio  
	C. Alibaba Cloud AIACC  
	D. PAI EAS (Elastic Algorithm Service)

	**Answer : D**

13. You want to train a machine learning model using data located in MaxCompute tables. Which of these Score 2 Alibaba Cloud is best suited to this task?
	
	A. Platform for Al (PAI)  
	B. Alibaba Cloud Function Compute  
	C. Alibaba Cloud API Gateway  
	D. DataWorks DataStudio

	**Answer : A**

14. Quick Bl is designed for. ______ while DataV is primarily used for. _________
	
	A. 1. Data cleaning 2. Making data-driven 3D maps  
	B. 1. Small projects 2. Big projects  
	C. 1. Business Intelligence (BI) 2. Realtime Data Display  
	D. 1. Machine Learning 2. Data Analysis

	**Answer : C**

15. When a local excel or CSV file is uploaded to Quick BI for presentation and analysis, the data is stored
	
	A. MaxCompute  
	B. AnalyticDB  
	C. Tablestore  
	D. The user's Quick Bi Workspace

	**Answer : D**

16. Alibaba Cloud's Quick Bl visualization and data analysis tool supports a variety of data sources, allowing users to analyze and present data from multiple different data sources. However, currently supported as a data source for Quick Bl.
	
	Α. ΗΤΤΡ Apis  
	B. MaxCompute  
	C. Local CSV files  
	D. ApsaraDB for RDS (MySQL)

	**Answer : A**

17. E-MapReduce (EMR) allows you to launch "Task nodes" that are used only for computing and do not store any data. Which Hadoop process is NOT run on Task nodes?
	
	A. DataNode  
	B. Storage Node  
	C. HDFSNode  
	D. CapacityNode

	**Answer : D**

18. Which of these CANNOT be used as a "compute engine in DataWorks?
	
	A. MaxCompute  
	B. AnalyticDB  
	C. E-MapReduce  
	D. Function Compute

	**Answer : B**

19. Which of these is NOT a good reason to choose E-MapReduce (EMR) over MaxCompute
	
	A. EMR will allow you to reuse all of your existing Hadoop code and workflows  
	B. EMR is cheaper than MaxCompute  
	C. EMR allows you to use all of the open source tools that are part of the Hadoop ecosystem  
	D. EMR allows you to use existing expertise that you or your team has in using Hadoop

	**Answer : B**

20. A company is about to start work on a data warehouse project using MaxCompute. There will be thousands of tables, terabytes of data, and more than 40 users needing access to the project. Which of these options is the best way to manage this project?
	
	A. Use DataWorks for managing users and developing workflows. Scheduling of tasks and editing of code should be done within the DataWorks web Ul  
	B. Give each user an Alibaba Cloud access key, and have them set up the MaxCompute CLI on their computer. Do all development through the CLI and a local editor.  
	C. Have each user install an IDE like IntelliJ IDEA, and connect to MaxCompute through the MaxCompute IDE plugin package.  
	D. Develop a customized tool to manage MaxCompute, with cess to MaxCompute managed via the MaxCompute SDK

	**Answer : A**

21. There are multiple ways to interact with MaxCompute: DataWorks, the "odpscmd CLI tool, and plugins for popular IDEs like IntelliJ IDEA. In most cases, which method does Alibaba Cloud recommend?
	
	A. DataWorks  
	B. Intelij IDEA  
	C. MaxCompute CLI (odpscmd)  
	D. MaxCompute SDK

	**Answer : A**

22. To ensure the reliability and availability of data, MaxCompute's storage layer stores multiple copies of each table. At present, how many copies does MaxCompute keep?
	
	A. Two  
	B. Three  
	C. Four  
	D. Five

	**Answer : B**

23. Which of the following descriptions of MaxCompute security is NOT correct:
	
	A. MaxCompute allows two types of users to operate on resources within MaxCompute projects: Alibaba Cloud primary (root) accounts, and Alibaba Cloud RAM users  
	B. The permissions of a RAM user within MaxCompute are NOT set by RAM itself, but rather by the owner of the MaxCompute project  
	C. MaxCompute allows you to assign "roles" to users, which allows you to assign the same set of permissions to multiple users more easily  
	D. MaxCompute projects only allow you to add up to two RAM users
	
	**Answer : C**

24. Which of these is a general "best practice" when creating a data warehouse?
	
	A. Try to separate data into as many different tables as possible  
	B. Import data into a central location, and do most of your data cleaning and processing on this centralized dataset  
	C. To make things easier for multiple teams within your organization, set up separate data storage and processing systems for each team  
	D. Avoid storing old data: it isn't useful in most cases

	**Answer : B**

25. One of the biggest challenges enterprises face when starting to utilize machine learning is
	
	A. Finding good machine learning tools and libraries  
	B. Maintaining supporting infrastructure (data processiong, cleaning, tagging deploying training model, etc  
	C. Finding enough compute resources to train a model  
	D. Figuring out how to label training data.

	**Answer : B**

26. ________ instances in Alibaba Cloud E-MapReduce are compute-only nodes that can used to scale EMR clusters in and out on-demand.
	
	A. Task  
	B. Gateway  
	C. Master  
	D. Core

	**Answer : A**

27. Like many Alibaba Cloud products, MaxCompute has a Pay-As-You-Go mode, in which you are charged only for resources you actually use. Which of these is NOT something MaxCompute charges you for?
	
	A. Data upload  
	B. Data download  
	C. Computing  
	D. Storage

	**Answer : A**

28. MaxCompute is a general purpose, fully managed, multi-tenancy data processing platform for large- scale data warehousing, and it is mainly used for storage and computing of batch structured data. Which of the following is NOT a use case for MaxCompute?
	
	A. Online transactions  
	B. Date Warehousing  
	C. Social networking analysis  
	D. User profiling
	
	**Answer : A**

29. Alibaba Cloud DataWorks includes tools for developing data processing workflows, scheduling and maintaining workflows, importing and exporting data, and publishing data-based APIs.
	
	A. True  
	B. False

	**Answer : A**

30. In DataWorks, there is no way to manually re-run failed tasks that are part of a scheduled Workflow.
	
	A. True  
	B. False

	**Answer : B**

31. The owner of a DataWorks Workspace can control which RAM accounts are added to the workspace, and which permissions are granted to them.
	
	A. True  
	B. False

	**Answer : A**

32. Quick BI dashboards do not support maps as a chart type, only graphs such as pie and line graphs.
	
	A. True  
	B. False

	**Answer : B**

33. Alibaba Cloud Platform for AI (PAI) allows users to train and test machine learning models easily using a drag-and-drop (low code) interface
	
	A. True  
	B. False
	
	**Answer : A**

34. DataV dashboards can display data pulled from third-party HTTP APIs.
	
	A. True  
	B. False

	**Answer : B**

35. Mechine Learning Platform for AI (PAI) includes a *Templates* feature that lets you start with an existing machine learning model and dataset, which can help you quickly understand how to use PAI.
	 
	A. True  
	B. False

	**Answer : A**

36. PAI allows you to directly use Alibaba Cloud FPGA Instances to train machine learning models on FPGA hardware
	
	A. True  
	B. False

	**Answer : A**

37. You cannot change the coler of charts in Quick BI
	
	A. True  
	B. False

	**Answer : B**

38. If you delete a node from a workflow in DataWorks, it is gone forever there in no “Recycle Bin”
	
	A. True  
	B. False

	**Answer : B**

39. The only way to use MaxCompute is through the DataWorks console
	
	A. True  
	B. False

	**Answer : B**

40. MaxCompute stores all data in the form of tables (Two dimensional sets of rows and columns) MaxCompute users whit the appropriate permessions can create, delete, query, and update tables.
	
	A. True  
	B. False
	
	**Answer : A**

41. Alibaba Cloud uses MaxCompute and DataWorks internally for business intelligence and for processing the petabytes of data generated by Alibaba Group.
	
	A. True  
	B. False
	
	**Answer : A**

42. MaxCompute can directly run ordinary Hadoop MapReduce (MR) jobs, in many cases, this can be done with no changes to the MapReduce code for the job.
	
	A. True  
	B. False

	**Answer : A**

43. Alibaba Cloud E-MapReduce (EMR) is a data warehousing and data processing solution for dealing with larhe volumes of data. An EMR cluster is a managed Hadoop cluster on which you can run standard open source tools like Hive, Spark, and Flink
	
	A. True  
	B. False
	
	**Answer : A**

44. There is no difference between “Core” and “Task” nodes in E-MapReduce (EMR) clusters
	
	A. True  
	B. False

	**Answer : B**

45. There are two methods for creating data synchronization tasks in DataWorks : Script mode and Wizard
	
	A. True  
	B. False

	**Answer : A**

46. If you create a User Defined Function (UDF) from the MaxCompute command line, that UDF will not be visible from the DataWorks console
	
	A. True  
	B. False

	**Answer : B**

47. DataWorks Data integration can read and write data to traditional database systems, as well as FTP server or OSS buckets
	
	A. True  
	B. False

	**Answer : A**

48. You have created a DataWorks Workspace (and associated MaxCompute project) to store user data. Some of the data is sensitive while some is not. In order to isolate the sensitive data from the non-sensitive data, you will need to create multiple Alibaba Cloud accounts
	
	A. True  
	B. False

	**Answer : A**

## Multiple Answer

1. Alhorithms trained in Machine Learning Platform for AI can make use of both ______ and __ hardware. (Number of correct answer 2)
	
	A. CPU  
	B. FPGA  
	C. GPU  
	D. Custume ASIIC

	**Answer : A & C**

2. You own a shopping mall, and are planning to collect hundreds of terabytes of video data from inside the mall, which you want to use to predict foot traffic. You want to store this data at low cost, and you want to be able to quickly experiment with multiple machine learning models using this data, while writing minimal code. Which Alibaba Cloud products can best help you achieve this? (Number of correct answer : 2)
	
	A. MaxCompute  
	B. Machine Learning Platform for AI (PAI)  
	C. Object Storage Service (OSS)  
	D. Cloud Disk

	**Answer : B & C**

3. Which of these are advantages of E-MapReduce over building you own Hadoop Cluster? (Number of Correct answers : 2)

	A. EMR is a managed service: Hadoop and related tools are installed and maintained for you  
	B. EMR include additional features like Auto Scaling which can be difficult to imolement on self-build Hadoop cluster  
	C. EMR is cheaper that a self-build Hadoop cluster  
	D. EMR processes data faster than a self-build Hadoop cluster

	**Answer : A & B**

4. In DataWorks, which of these are likely causes of errors during data import? (Number of correct answer : 2)
	
	A. The source table has been deleted  
	B. The destination table has been deleted  
	C. There are NULL values in the source table  
	D. The source table has new fields added

	**Answer : A & C**

5. Alibaba Cloud E-MapReduce (EMR) has an Auto Scaling feature that allows you to add and remove computing capacity based on EMR cluster metrics like CPU and memory usage. Which of these statements about Auto Scalling are Correct? (Number of correct answers : 2)
	
	A. EMR Auto Scaling only supports scaling a cluster by adding and removing Task nodes.  
	B. You can scale by both time (scale at affixed time) or scale based on cluster metrics (CPU and memory use).  
	C. EMR clusters cannot be scaled to Include more then 10 nodes.  
	D. Once added to an EMR cluster, Task nodes cannot be removed.

	**Answer : A & B**

6. If some node (task) in a DataWorks fails to run, an alert can be sent to one or more of the users in the DataWorks Workspace. Which alert methods are supported? (Number of correct answers: 3)
	
	A. Email  
	B. Text Message (SMS)  
	C. Slack Chat Massage  
	D. Webhook

	**Answer : A, B & C**

7. Which of these are reasonable use cases for MaxCompute? (Number of correct answer: 3)
	
	A. Collect and analyze logs from a web application  
	B. Build a data warehouse, for storing and processing a company’s historical data  
	C. Store and processing customer data, which will be used to train a machine learning model  
	D. Respond to request for individual database records in real time  
	E. Drive a realtime data display board which must be updated every few seconds.

	**Answer : B, D & E**

8. Which of these ar features of Quick BI? (Number of correct answers : 3)
	
	A. Join and filter datasets  
	B. Create dashboards featuring graphs and charts  
	C. Create excel-style workbooks  
	D. Create mobile-phone friendly realtime data displays

	**Answer : A, B & D**

9. Which types of tasks can be added to a DataWorks Workflow? (Number of correct answers : 3)
	
	A. Data Import and export tasks (data synchronization)  
	B. Data processing tasks ( Python code, Spark code, MaxCompute SQL code)  
	C. Function Compute tasks (tasks that run inside fuction compute)  
	D. PAI (Platform Fro AI) Machine Learning tasks
	
	**Answer : A, B & D**

10. DataV allows you restrict access to your published DataV dashboard via ____ or __ (Number of correct answer : 2)
	A. Password  
	B. Token (URL signature)  
	C. SMS Message  
	D. QR Code

	**Answers : A & B**

11. Which of these are important components of the data processing lifecycle (Number of correct answer : 4 )
	
	A. Data ingestion (Import)  
	B. Data storage  
	C. Data processing and analysis  
	D. Data compression  
	E. Data visualization

	**Answers : A, B, C & E**

12. Which of these are advantages of Max Compute over building your own data wirehouse using Hadoop? ( Number of correct answers : 2)
	
	A. With MaxCompute, you don’t have to worry about scaling storage or compute capacity as your needs grow  
	B. MaxCompute is always faster than Hadoop  
	C. With MaxCompute, computing and storage costs are decoupled, and you pay only for what you use  
	D. MaxCompute has more features than Hadoop.

	**Answer : A & C**