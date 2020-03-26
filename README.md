![](graphics/microsoftlogo.png)

# Workshop: SQL Server Big Data Clusters

> Contributor: Martin  
> Purpose: Demo/Workshop  
> Updated date: 2020/03/26

<p style="border-bottom: 1px solid lightgrey;"></p>

<img style="float: left; margin: 0px 15px 15px 0px;" src="https://github.com/Microsoft/sqlworkshops/blob/master/graphics/textbubble.png?raw=true"> <h2><a name="about">About this Workshop</a></h2>

Welcome to this Microsoft solutions workshop on the architecture on SQL Server Big Data Clusters. You'll experiment with SQL Server Big Data Clusters (BDC), and how you can use it to implement large-scale data processing and machine learning.

This Workshop assumes you have a full understanding the concepts of big data analytics, the technologies (such as containers, Kubernetes, Spark and HDFS, machine learning, and other technologies) that you will use throughout the Workshop, the architecture of a BDC. <a href="https://github.com/microsoft/sqlworkshops/tree/master/sqlserver2019bigdataclusters" target="_blank">If you are familiar with these topics, you can take a complete course here</a>.

In this Workshop you'll learn how to create external tables over other data sources to unify your data, and how to use Spark to run big queries over your data in HDFS or do data preparation. You'll review a complete solution for an end-to-end scenario, with a focus on how to extrapolate what you have learned to create other solutions for your organization.

<p style="border-bottom: 1px solid lightgrey;"></p>

<img style="float: left; margin: 0px 15px 15px 0px;" src="https://github.com/Microsoft/sqlworkshops/blob/master/graphics/owl.png?raw=true"> <h2><a name="prereqs">Before Taking this Workshop</a></h2>

This Workshop expects that you understand data structures and working with SQL Server and computer networks. This Workshop does not expect you to have any prior data science knowledge, but a basic knowledge of statistics and data science is helpful in the Data Science sections. Knowledge of SQL Server, Azure Data and AI services, Python, and Jupyter Notebooks is recommended. AI techniques are implemented in Python packages. Solution templates are implemented using Azure services, development tools, and SDKs. You should have a basic understanding of working with the Microsoft Azure Platform.

<b>▶</b> You need to have all of the <a href="https://github.com/microsoft/sqlworkshops/blob/master/sqlserver2019bigdataclusters/SQL2019BDC/00%20-%20Prerequisites.md" target="_blank">prerequisites completed</a> before taking this Workshop. 

<b>▶</b> You need a full Big Data Cluster for SQL Server up and running, and have identified the connection endpoints, with all security parameters. <a href="https://docs.microsoft.com/en-us/sql/big-data-cluster/deployment-guidance?view=sqlallproducts-allversions" target="_blank">You find out how to do that here</a>.

<p style="border-bottom: 1px solid lightgrey;"></p>

<img style="float: left; margin: 0px 15px 15px 0px;" src="https://github.com/Microsoft/sqlworkshops/blob/master/graphics/bookpencil.png?raw=true"> <h2><a name="modules">Workshop Notebooks</a></h2>

<p>You will work through six Jupyter Notebooks using the Azure Data Studio tool. Download them and open them in Azure Data Studio, running only one cell at a time.</p> 

<table>
  <tr><td><b>Notebook</b></td><td><b>Topics</b></td></tr>

  <tr><td><a href="bdc-00-overview.ipynb" target="_blank">bdc-00-overview.ipynb</a></td><td> Overview of the Workshop and setup of the source data, problem space, solution options and architectures</td></tr>

  <tr><td><a href="bdc-01-k8s.ipynb" target="_blank">bdc-01-k8s.ipynb</a></td><td> In-depth details of a pod or other Kubernetes artifacts that are located in a SQL Server big data cluster.</td></tr>

  <tr><td><a href="bdc-02-adstudio.ipynb" target="_blank">bdc-02-adstudio.ipynb</a></td><td> View service endpoints and status of a SQL Server big data cluster components.
  </td></tr>

  <tr><td><a href="bdc-03-sqlserver-master.ipynb" target="_blank">bdc-03-sqlserver-master.ipynb</a></td><td> Run standard SQL Server Queries against the Master Instance (MI) in a SQL Server big data cluster.</td></tr>

  <tr><td><a href="bdc-04-data-virtualization.ipynb" target="_blank">bdc-04-data-virtualization.ipynb</a></td><td> Learn how to create and query Virtualized Data in a SQL Server big data cluster.</td></tr>

  <tr><td><a href="bdc-05-data-mart.ipynb" target="_blank">bdc-05-data-mart.ipynb</a></td><td> Create and query a Data Mart using Virtualized Data in a SQL Server big data cluster.</td></tr>

  <tr><td><a href="bdc-06-spark-etl.ipynb" target="_blank">bdc-06-spark-etl.ipynb</a></td><td> Learn how to work with Spark Jobs in a SQL Server big data cluster.</td></tr>

  <tr><td><a href="bdc-07-spark-ml.ipynb" target="_blank">bdc-07-spark-ml.ipynb</a></td><td> Train Spark ML model in a SQL Server big data cluster and export is as a MLeap bundle</td></tr>

  <tr><td><a href="bdc-08-model-deployment.ipynb" target="_blank">bdc-08-model-deployment.ipynb</a></td><td> Learn how to export and deploy MLeap bundle in a SQL Server big data cluster.</td></tr>

</table>

<p style="border-bottom: 1px solid lightgrey;"></p>

