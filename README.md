Openark Kit - common utilities for MySQL
==========

Fork of https://code.google.com/p/openarkkit/

==========

#### The openark kit provides common utilities to administer, diagnose and audit MySQL databases.

Please refer to the openark kit documentation for details.

The available tools are:

- oak-apply-ri: apply referential integrity on two columns with parent-child relationship.
- oak-block-account: block or release MySQL users accounts, disabling them or enabling them to login.
- oak-chunk-update: perform long, non-blocking UPDATE/DELETE operation in auto managed small chunks.
- oak-get-slave-lag: print slave replication lag and terminate with respective exit code.
- oak-hook-general-log: hook up and filter general log entries based on entry type or execution plan criteria.
- oak-kill-slow-queries: terminate long running queries.
- oak-modify-charset: change the character set (and collation) of a textual column.
- oak-online-alter-table: perform a non-blocking ALTER TABLE operation.
- oak-prepare-shutdown: make for a fast and safe MySQL shutdown.
- oak-purge-master-logs: purge master logs, depending on the state of replicating slaves.
- oak-repeat-query: repeat query execution until some condition holds.
- oak-security-audit: audit accounts, passwords, privileges and other security settings.
- oak-show-limits: show AUTO_INCREMENT “free space”.
- oak-show-replication-status: show how far behind are replicating slaves on a given master.

All tools are coded in Python, require Python 2.3 or newer, and the python-mysqldb driver. Some tools require MySQL 5.0 or higher; see the docs for each tool.
