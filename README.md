# Databricks and Data Factory: Creating and Orchestrating Pipelines in the Cloud

In this project, an entire data engineering pipeline was developed following the workflow below:

![image](https://github.com/millenagena/pipeline-databricks-azure/assets/69437878/3cec661b-de43-4ea7-91bf-2f2bad541e95)

I started by creating and structuring a Data Lake in Azure. This Data Lake was organized into three layers:

* Inbound Layer;
* Bronze Layer;
* Silver Layer.

The Inbound Layer is the entry point, where I added the raw real estate database. With this data in the entry layer, I used Databricks to apply specific transformations to the data and pass it through the Bronze and Silver layers of the Data Lake.

Once the data flow was structured, I used Azure Data Factory to orchestrate and automate the execution of this pipeline based on a specific time interval.

This project was developed for a course I taught at Alura. You can access it by clicking on the link: [Course's link](https://cursos.alura.com.br/course/databricks-data-factory-pipelines-nuvem)

## Technologies used

* Azure Data Lake Storage Gen 2;
* Azure Databricks;
* Azure Data Factory;
* Scala.

## Contact

Email: millenagena@gmail.com
