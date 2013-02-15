oracle_performance
==================
Scripts in this repository

* sql_sql_id.sql - Retrieves a lot of information about a SQL statement, based on SQL_ID.
* sql_old_hash.sql - Similar to sql_sql_id.sql, to use if you don't have the sql_id, but do have the old hash values found in Statspack.
* sql_plan_baselines.sql - Retrieves information concerning the use of SQL plan baselines.
* trace_column.sql - If you quickly need to trace one or more sessions based on username, program or whatever in v$session.
* ora1555.sql - Use this to find out information about SQL's mentioned in ORA-1555 messages.
* top10sql_plan.sql - Show the 10 SQL statements in the shared pool
* top10sql_plan9i.sql - Still had this somewhere. You'll never know when it comes in handy, although hopefully not ;)
