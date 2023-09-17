---
weight: 1
bookFlatSection: true
title: "3. Install PostgreSQL"
---

# PostgreSQL Database 

PostgreSQL is an open-source relational database. 

We will be using PostgreSQL for the first few weeks of the course as we learn how to load data into databases and perform advanced transformations using SQL. 

To install PostgreSQL, go to https://www.postgresql.org/download/ and select the installer for your Operating System. Download the latest version of PostgreSQL (Version 14).

After downloading the installer, run the installer on your computer. 

Select all options for when promoted for the components you wish to install. 

![postgres-component.png](https://github.com/Data-Engineer-Camp/getting-started/blob/main/static/postgres-component.png?raw=true)

Please use the master password "postgres" when prompted to enter a password. Because you are installing PostgreSQL on your computer, no one will have access to it other than yourself. Setting the master password to "postgres" will minimise the risk of forgetting your password for your local development PostgreSQL database. 

![postgres-password.png](https://github.com/Data-Engineer-Camp/getting-started/blob/main/static/postgres-password.png?raw=true)

When promoted for a port number, please provide `5432` as the port number. This is the default port number that should be provided when using PostgreSQL. 

When installed successfully, you should be able to find `pgAdmin 4` in your applications. 

![postgres-success.png](https://github.com/Data-Engineer-Camp/getting-started/blob/main/static/postgres-success.png?raw=true)
