# Getting-Started-with-Airflow
The notebook provides an introduction to Apache Airflow, a popular workflow management platform.</br>
It covers the basic concepts of Airflow, including workflows, tasks, operators, and execution dates. It also demonstrates how to define DAGs (Directed Acyclic Graphs) and schedule them using cron syntax. </br>
The notebook explains various types of operators, such as BashOperator and PythonOperator, and how to define dependencies between tasks. Additionally, it showcases how to pass data between tasks using op_kwargs and XComs. Finally, the notebook provides examples of interacting with Microsoft SQL Server, including creating connections and performing SELECT and INSERT operations.

## Table of Contents

- Airflow Basic Concepts
  - What is Airflow?
  - What is a Workflow?
  - Task
  - Operator
  - Difference between Task and Operator
  - Execution Date
  - Defining a DAG
- Python Operator
- Sharing Data Between Tasks
  - op_kwargs
  - X_Coms
- Selecting or Inserting Data from SQL Server
  - Creating a Connection
  - MsSqlHook
  - SQL Server Operator

## Sources

- [Apache Airflow Documentation](https://airflow.apache.org/docs/apache-airflow/stable/core-concepts/dags.html)
- [Code2J YouTube Channel](https://www.youtube.com/@coder2j)
- [Data Pipelines with Apache Airflow Book](https://livebook.manning.com/book/data-pipelines-with-apache-airflow/welcome/v-6/7)
- [ETL and Data Pipelines with Shell, Airflow, and Kafka Course](https://www.coursera.org/learn/etl-and-data-pipelines-shell-airflow-kafka)

