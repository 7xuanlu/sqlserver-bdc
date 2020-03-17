![](graphics/microsoftlogo.png)

# Lab: SQL Server Big Data Clusters

> Contributor: Martin  
> Purpose: Demo/Workshop  
> Updated date: 2020/02/24

<p style="border-bottom: 1px solid lightgrey;"></p>

<img style="float: left; margin: 0px 15px 15px 0px;" src="https://github.com/Microsoft/sqlworkshops/blob/master/graphics/textbubble.png?raw=true"> <h2><a name="about">About this Lab</a></h2>

Welcome to this Microsoft solutions Lab  on the architecture on SQL Server Big Data Clusters. As part of <a href="https://github.com/Microsoft/sqlworkshops/tree/master/sqlserver2019bigdataclusters" target="_blank">a larger complete Workshop</a>, you'll experiment with SQL Server Big Data Clusters (BDC), and how you can use it to implement large-scale data processing and machine learning.

This Lab assumes you have a full understanding the concepts of big data analytics, the technologies (such as containers, Kubernetes, Spark and HDFS, machine learning, and other technologies) that you will use throughout the Lab, the architecture of a BDC. <a href="https://github.com/microsoft/sqlworkshops/tree/master/sqlserver2019bigdataclusters" target="_blank">If you are familiar with these topics, you can take a complete course here</a>.

In this Lab you'll learn how to create external tables over other data sources to unify your data, and how to use Spark to run big queries over your data in HDFS or do data preparation. You'll review a complete solution for an end-to-end scenario, with a focus on how to extrapolate what you have learned to create other solutions for your organization.

<p style="border-bottom: 1px solid lightgrey;"></p>

<img style="float: left; margin: 0px 15px 15px 0px;" src="https://github.com/Microsoft/sqlworkshops/blob/master/graphics/owl.png?raw=true"> <h2><a name="prereqs">Before Taking this Lab</a></h2>

This Lab expects that you understand data structures and working with SQL Server and computer networks. This Lab does not expect you to have any prior data science knowledge, but a basic knowledge of statistics and data science is helpful in the Data Science sections. Knowledge of SQL Server, Azure Data and AI services, Python, and Jupyter Notebooks is recommended. AI techniques are implemented in Python packages. Solution templates are implemented using Azure services, development tools, and SDKs. You should have a basic understanding of working with the Microsoft Azure Platform.

<b>▶</b> You need to have all of the <a href="https://github.com/microsoft/sqlworkshops/blob/master/sqlserver2019bigdataclusters/SQL2019BDC/00%20-%20Prerequisites.md" target="_blank">prerequisites completed</a> before taking this Lab. 

<b>▶</b> You need a full Big Data Cluster for SQL Server up and running, and have identified the connection endpoints, with all security parameters. <a href="https://docs.microsoft.com/en-us/sql/big-data-cluster/deployment-guidance?view=sqlallproducts-allversions" target="_blank">You find out how to do that here</a>.

<p style="border-bottom: 1px solid lightgrey;"></p>

<img style="float: left; margin: 0px 15px 15px 0px;" src="https://github.com/Microsoft/sqlworkshops/blob/master/graphics/bookpencil.png?raw=true"> <h2><a name="modules">Lab Notebooks</a></h2>

<p>You will work through six Jupyter Notebooks using the Azure Data Studio tool. Download them and open them in Azure Data Studio, running only one cell at a time.</p> 

<table>
  <tr><td><b>Notebook</b></td><td><b>Topics</b></td></tr>

  <tr><td><a href="bdc_tutorial_00.ipynb" target="_blank">bdc_tutorial_00.ipynb</a></td><td> Overview of the Lab and Setup of the source data, problem space, solution options and architectures</td></tr>

  <tr><td><a href="bdc_tutorial_01.ipynb" target="_blank">bdc_tutorial_01.ipynb</a></td><td> In-depth details of a pod or other Kubernetes artifacts that are located in a SQL Server big data cluster.</td></tr>

  <tr><td><a href="bdc_tutorial_02.ipynb" target="_blank">bdc_tutorial_02.ipynb</a></td><td> View service endpoints the status of a SQL Server big data cluster components.
  </td></tr>

  <tr><td><a href="bdc_tutorial_03.ipynb" target="_blank">bdc_tutorial_03.ipynb</a></td><td> Run standard SQL Server Queries against the Master Instance (MI) in a SQL Server big data cluster.</td></tr>

  <tr><td><a href="bdc_tutorial_04.ipynb" target="_blank">bdc_tutorial_04.ipynb</a></td><td> In this tutorial you will learn how to create and query Virtualized Data in a SQL Server big data cluster.</td></tr>

  <tr><td><a href="bdc_tutorial_05.ipynb" target="_blank">bdc_tutorial_05.ipynb</a></td><td> In this tutorial you will learn how to create and query a Data Mart using Virtualized Data in a SQL Server big data cluster.</td></tr>

  <tr><td><a href="bdc_tutorial_06.ipynb" target="_blank">bdc_tutorial_06.ipynb</a></td><td> In this tutorial you will learn how to work with Spark Jobs in a SQL Server big data cluster.</td></tr>

  <tr><td><a href="bdc_tutorial_07.ipynb" target="_blank">bdc_tutorial_07.ipynb</a></td><td> In this tutorial you will learn how to train Spark ML model in a SQL Server big data cluster and export is as a MLeap bundle</td></tr>

  <tr><td><a href="bdc_tutorial_08.ipynb" target="_blank">bdc_tutorial_08.ipynb</a></td><td> In this tutorial you will learn how to export and deploy MLeap bundle in a SQL Server big data cluster.</td></tr>

</table>

<p style="border-bottom: 1px solid lightgrey;"></p>

