# k8s_mssql
MS SQL server on Kubernetes

----------------

####* Local databases for local development and project.

* namespace.yaml
* secret.yaml
* pvc.yaml
* loadbalancer.yaml / ingress.yaml
* deployment.yaml

----------------

MSSQL server container 'mcr.microsoft.com/mssql/server:2019-latest' does not support ARM architecture. 

The alternative is to use Azure SQL container 'mcr.microsoft.com/azure-sql-edge:latest' that supports ARM and can be run on M1.

