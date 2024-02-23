
## Databricks

The platform contains a distributed filesystem for storage, as well as integrating Azure data storage components, and provides a workspace for ingesting, processing, transforming, storing, and serving data to analytics and data science consumers.

Azure Databricks includes complete Apache Spark technologies and capabilities including core Spark API, Spark SQL, and Dataframes modules you can interact with via Python scripts, Jupyter notebooks, as well as few other programming languages.

Fully managed Spark clusters are provided for you in a collaborative, interactive workspace environment, where you can share notebooks with team members and explore data.

![image](https://github.com/arpit-mittal-ds/Data-Engineer-Udacity-NanoDegree/assets/68102477/5fcaa0ea-2966-4a48-9681-ea9bffcd7735)



### How databricks fit with Azure MDP

One possible solution involving Azure Databricks would utilize Databricks between a data lake and Azure Synapse or PowerBI.

In this scenario as an analytics platform, Azure data factory is used to ingest unstructured and structured data from business sources into Azure Data lake storage
Azure Databricks is used to prepare, train, process, and transform data for use in Azure Synapse Analytics or Microsoft Power BI.

![image](https://github.com/arpit-mittal-ds/Data-Engineer-Udacity-NanoDegree/assets/68102477/a536c210-b247-4313-9ed9-1e262211d790)

Another way to use Azure Databricks would be to utilize Databricks between data sources and a data lake. In this scenario,
Databricks provides data flows and processing, and can even be used to prepare data for machine learning solutions.
A variation of this use would pull the data lake back into Azure Databricks and use Delta Lake. This variation would implement the lakehouse architecture design.

![image](https://github.com/arpit-mittal-ds/Data-Engineer-Udacity-NanoDegree/assets/68102477/485dd5f5-7f8a-4e78-a3b5-d2e9998f8922)

### Spark and Jupyter Notebooks

If you install Apache Spark on your desktop computer, there is an interactive shell that you can use to write code. An even easier way of writing code for Spark is to connect Jupyter Notebooks to it. This process can be complex when working on your local desktop computer, but in Azure Databricks, Jupyter Notebooks are built right in, and all of your work is done in the cloud.

Apache Spark compute power is available on-demand from Azure, and you can use as little or as much of this compute power as you need. Within your Azure Databricks workspace, you can quickly and easily access Jupyter notebooks and begin writing code in Python, SQL, Scala, or R.

### Demo: Create Databricks Workspace
You can create an Azure Databricks Resource just like you do other resources in Azure. There are several items to configure that are common to other resources such as
subscription name
resource group name
region
In addition, Azure Databricks is organized into workspaces and you will provide a workspace name when you create the resource. There are several pricing tiers but the pricing in Azure Databricks is tied to access rather than processing power. You will see that processing power affects pricing when you add compute resources to your Azure Databricks resource.

![image](https://github.com/arpit-mittal-ds/Data-Engineer-Udacity-NanoDegree/assets/68102477/7e1d7c28-f0bb-4a3f-8d10-18765bebfc6a)

Adding Apache Spark Clusters to a Databricks workspace in Azure is simple using the Azure Portal UI. After choosing a name for your cluster, you choose the cluster mode based on the number of users and concurrency needs.

Next you will select a Databricks runtime version which determines which version of Scala and Spark are available.

You can also configure the autopilot options which allows you to turn off a cluster after a period of inactivity.

Next you configure the actual compute power to be used by configuring workers and driver type. The UI will provide an estimate of cost per hour so you can adjust according to your needs and budget.

Once configured, you create a cluster and after a period of time, it will be available to assign to Notebooks and Spark Jobs.

Azure Databricks provides a workspace where a data engineer can keep use Notebooks created in Jupyter and track data stored in Delta Lake.

![image](https://github.com/arpit-mittal-ds/Data-Engineer-Udacity-NanoDegree/assets/68102477/a6977c76-ad01-4f93-8a17-190c0e67cbb2)


The real power of Databricks comes from the Apache Spark compute power available on-demand from Azure.

To add and monitor the Apache Spark compute power associated with your workspace, you access the Computer node from the main Databricks workspace menu.

![image](https://github.com/arpit-mittal-ds/Data-Engineer-Udacity-NanoDegree/assets/68102477/ea71b27b-1e31-4dd9-a713-78b5d5d2a596)



