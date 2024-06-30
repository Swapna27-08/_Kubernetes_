# _Kubernetes_
Creating Kubernetes config to launch Clickhouse &amp; Superset pods in Minikube &amp; connect them
# Clickhouse and Superset on Minikube

This project sets up Clickhouse, an open-source data warehouse, and Apache Superset, a business intelligence tool, on Minikube. The setup includes deploying Clickhouse with persistent storage and deploying Superset, then connecting Superset to Clickhouse for data visualization and reporting.

## Prerequisites

- [Minikube](https://minikube.sigs.k8s.io/docs/start/)
- [kubectl](https://kubernetes.io/docs/tasks/tools/)
- [Docker](https://docs.docker.com/get-docker/)
- Basic knowledge of Kubernetes and Docker

## Setup Instructions
 Step 1: Create Project Directory

Open your terminal or command prompt and create a directory for your project:

```sh
mkdir kubernetes-clickhouse-superset
cd kubernetes-clickhouse-superset
step:2 create config yaml files..
step:3 Create deployment of superset superset ( keep this while doing it Doc)
Open superset url in the browser
Connect clickhouse to superset. 
step:4 Go to superset url
Go to Data > Databases > (+Database button) > Choose clickhouse from list > add clickhouse url like Doc )
step:5 Click connect

by these above instructions we are able to do the connection....

