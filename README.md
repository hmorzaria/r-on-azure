# R-on-azure

Development of data science and AI becomes easier than ever before thanks to cloud computing. The Github repo site collects a set of R packages, tools, and tutorials for doing R data science on Azure cloud. 

These packages and tools are categoried into four groups, representing four typical tasks data scientists or AI developers may frequently work on. 

Category|Features
----------------------|-----------------------------------------------------------------------------------------------------
Cloud resource operation and administration|Simplify the way to interact with Azure cloud platform and operate resouces on Azure for various tasks.
Scalable and advanced analytics|Enable large-scale and parallel data analytics in R environment.
Remote interaction and access to Cloud instance|Enhance work efficiency on cloud for R based analytics.
Application and service deployment|Make operationalizing solution and deploying it as service easy.

## Cloud resource operation and administration
R packages and tools in this category are featured by offering a simplified way to interact with Azure cloud platform and operate resouces (e.g., blob storage, Data Science Virtual Machine, Azure Batch Service, etc.) on Azure for various tasks. 

* [AzureSMR](https://github.com/Microsoft/AzureSMR) - R package for managing a selection of Azure resources. Targeted at Data Scientists who need to control Azure Resources without needing to both Administrators. APIs include Storage Blobs, HDInsight(Nodes, Hive, Spark), ARM, VMs.
* [AzureDSVM](https://github.com/Azure/AzureDSVM) - R package that offers convenient harness of Azure DSVM, remote execution of scalable and elastic data science work, and monitoring of on-demand resource consumption.
* [doAzureParallel](https://github.com/Azure/doAzureParallel) - R package that allows users to submit parallel workloads in Azure.
* [rAzureBatch](https://github.com/Azure/rAzureBatch) - a HTTP proxy library written in R for Azure.
* [AzureML](https://github.com/RevolutionAnalytics/AzureML) - an R interface to [AzureML](https://studio.azureml.net/) experiments, datasets, and web services.

## Scalable and advanced analytics
R packages and tools in this category allow one to performan large-scale R-based analytics on cloud with the bleeding-edge frameworks such as Spark, Hadoop, Microsoft Cognitive Toolkit, Tensorflow, Keras, etc. 
**NOTE**: many of the tools are pre-installed and configured for direct use on Azure Data Science Virtual Machine.

### Scalable analytics
* [dplyrXdf](https://github.com/RevolutionAnalytics/dplyrXdf) - a dplyr backend for Revolution Analytics xdf files.
* [sparklyr](http://spark.rstudio.com/) - R interface for Apache Spark.
* [SparkR](https://spark.apache.org/docs/latest/sparkr.html) - SparkR is an R package that provides a light-weight frontend to use Apache Spark from R.

### Deep learning
* [CNTK-R](https://github.com/Microsoft/CNTK-R) - R bindings to the CNTK library.
* [tensorflow](https://tensorflow.rstudio.com/) - R interface to Tensorflow.
* [mxnet](https://mxnet.incubator.apache.org/api/r/index.html) - The MXNet R package brings flexible and efficient GPU computing and state-of-art deep learning to R.
* [keras](https://keras.rstudio.com/) - R interface to Keras.
* [darch](https://github.com/maddin79/darch) - Create deep architectures in R. 
* [deepnet](https://cran.r-project.org/web/packages/deepnet/index.html) - Implement some deep learning architectures and neural network algorithms, including BP,RBM,DBN,Deep autoencoder and so on.
* [gpuR](https://github.com/cdeterman/gpuR) - R interface to use GPU.

### Compositive
* [RevoScaleR](https://docs.microsoft.com/en-us/machine-learning-server/r-reference/revoscaler/revoscaler) - a collection of portable, scalable, and distributable R functions for importing, transforming, and analyzing data at scale. 
* [MicrosoftML](https://docs.microsoft.com/en-us/machine-learning-server/r-reference/microsoftml/microsoftml-package) - a package that provides state-of-the-art fast, scalable machine learning algorithms and transforms for R.
* [h2o](https://github.com/h2oai/h2o-3) - R interface to H2O.

## Interaction and remote access

## Application and service deployment 
