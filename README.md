# Spark Cluster on Yarn Hadoop Cluster with Jupyter Notebook Integration

This configuration allows you to seamlessly run Python code alongside Spark, enabling powerful data processing and analysis. It combines the distributed computing capabilities 
of Spark with the flexibility and interactivity of Jupyter Notebook, making it easier to work with big data and perform data transformations, analysis, and machine learning tasks efficiently.

## Running the Cluster

To start the Spark cluster on the Yarn Hadoop cluster with Jupyter Notebook integration, follow these steps:

1. Clone this repository to your local machine (if you haven't already):

    ```bash
    gh repo clone ClementineM12/spark_hadoop_jupyter-notebooks_
    ```

2. Navigate to the project directory:

3. Run the cluster:

    ```bash
    ./run-cluster.sh
    ```

   This script will initiate the cluster and configure it according to your settings.

4. Once the cluster is running, you can access the following components:

   - Spark Master: [http://localhost:9090](http://localhost:9090)
   - Namenode: [http://localhost:9870](http://localhost:9870)
   - Jupyter Notebook: [http://localhost:8888](http://localhost:8888)

5. Use Jupyter Notebook to create and run notebooks for your data processing and analysis tasks, utilizing the power of the integrated Spark cluster.

6. Stop the cluster / Remove containers:

    ```bash
    ./stop-cluster.sh
    ```

   This script will give you two options, either stop the containers created, or remove all the containers alongside with the volumes created.





