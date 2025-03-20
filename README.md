# ADF-sanitation-pipeline

A simple project using medallion architechture where data is ingested from 3 sources stored using ADF storing them in ADL.
Performing ETL operations on bronze tier data from ADL using Databricks and loading them into ADL silver tier.
Using Synapse to perform further operations on Silver tier and storing them in ADL gold tier.
