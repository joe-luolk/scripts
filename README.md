                                                         Tools Script
1.clickhouse-attrestore : Restore freeze part table backup from attached directory  
>example:clickhouse-attrestore.sh -h 127.0.0.1 -P 9000 -u default [-p]|[-p 123456] -d test -t test/var/lib/clickhouse/data/test/test/detached

2.clickhouse-import: Restore data to table from backup file or directory
>example:clickhouse-import -h 127.0.0.1 -P 9000 -u root -p|-p 123456 -d test backup_directory|table

3.clickhouse-dump:remote backup clickhouse database or tables to local,include metadata and data('TabSeparated' format)
>clickhouse-dump -h 127.0.0.1 -P 9000 -u  default [-p]|[-p 123456] -d test [-t table1,table2] [-n 2]
