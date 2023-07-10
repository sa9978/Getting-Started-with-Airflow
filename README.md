# Getting-Started-with-Airflow
The notebook provides an introduction to Apache Airflow, a popular workflow management platform. 
It covers the basic concepts of Airflow, including workflows, tasks, operators, and execution dates. It also demonstrates how to define DAGs (Directed Acyclic Graphs) and schedule them using cron syntax. 
The notebook explains various types of operators, such as BashOperator and PythonOperator, and how to define dependencies between tasks. Additionally, it showcases how to pass data between tasks using op_kwargs and XComs. Finally, the notebook provides examples of interacting with Microsoft SQL Server, including creating connections and performing SELECT and INSERT operations.

## Table of Contents

- [Airflow Basic Concepts](https://github.com/sa9978/Getting-Started-with-Airflow/blob/main/airflow.ipynb#airflow-basic-concepts)
  - [What is Airflow?](https://github.com/sa9978/Getting-Started-with-Airflow/blob/main/airflow.ipynb#what-is-airflow)
  - [What is a Workflow?](#what-is-a-workflow)
  - [Task](#task)
  - [Operator](#operator)
  - [Difference between Task and Operator](#difference-between-task-and-operator)
  - [Execution Date](#execution-date)
  - [Defining a DAG](#defining-a-dag)
- [Python Operator](#python-operator)
- [Sharing Data Between Tasks](#sharing-data-between-tasks)
  - [op_kwargs](#op_kwargs)
  - [X_Coms](#x_coms)
- [Selecting or Inserting Data from SQL Server](#selecting-or-inserting-data-from-sql-server)
  - [Creating a Connection](#creating-a-connection)
  - [MsSqlHook](#mssqlhook)
  - [SQL Server Operator](#sql-server-operator)

## Sources

- [Apache Airflow Documentation](https://airflow.apache.org/docs/apache-airflow/stable/core-concepts/dags.html)
- [Code2J YouTube Channel](https://www.youtube.com/@coder2j)
- [Data Pipelines with Apache Airflow Book](https://livebook.manning.com/book/data-pipelines-with-apache-airflow/welcome/v-6/7)
- [ETL and Data Pipelines with Shell, Airflow, and Kafka Course](https://www.coursera.org/learn/etl-and-data-pipelines-shell-airflow-kafka)

