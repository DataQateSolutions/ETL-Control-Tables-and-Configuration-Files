# ETL-Control-Tables-and-Configuration-Files
This Repository Shows DDL SQL for a Control Table and JSON for a Configuration File, as well as Python Code to show how these can be leveraged in a batch ETL/ELT Script. 

The rationale behind the use of these in ETL scripts is simple - it helps organize the code and ensures easier maintainability and scalability, when compared with those ETL/ELTs that are done without them. 


### The following assumptions were made:

1. A full refresh was assumed for both the config file and control table scenarios
2. A Relational Database source was assumed in both scenarios
3. A stored Procedure would be leveraged to handle transformations in the target DB
