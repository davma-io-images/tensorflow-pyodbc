## 1. Introduction

TensorFlow image with pyodbc == 4.0.30

## 2. Requirements

1. [Docker](https://docs.docker.com/get-docker/)

## 3. Docker pull

You can download the full image from [Docker Hub](https://hub.docker.com/) with the following command.

````
docker pull davma/tensorflow-pyodbc
````

## 4. Image build

You can run the image build with the following commands

````
git clone https://github.com/davma-io-images/tensorflow-pyodbc.git
cd tensorflow-pyodbc
docker build -t tensorflow-pyodbc .
````

## 5.Documentation and guides

[Microsoft ODBC 17](https://docs.microsoft.com/en-us/sql/connect/odbc/linux-mac/installing-the-microsoft-odbc-driver-for-sql-server?view=sql-server-2017)
