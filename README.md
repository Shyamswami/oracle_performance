oracle_performance
==================
Scripts in this repository

* sql_sql_id.sql - Retrieves a lot of information about a SQL statement, based on SQL_ID.
* sql_old_hash.sql - Similar to sql_sql_id.sql, to use if you don't have the sql_id, but do have the old hash values found in Statspack.
* sql_plan_baselines.sql - Retrieves information concerning the use of SQL plan baselines.
* trace_column.sql - If you quickly need to trace one or more sessions based on username, program or whatever in v$session.
