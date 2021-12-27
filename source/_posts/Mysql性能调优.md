---
title: Mysql性能调优
date: 2021-10-22 15:18:14
tags: [Mysql]
category: [数据库]
---

max_connections=1000
character-set-server = utf8mb4
innodb_write_io_threads = 8
innodb_read_io_threads = 12

open_files_limit = 65535
innodb_buffer_pool_size = 10G
innodb_thread_concurrency = 32
tmp_table_size = 1024M
max_heap_table_size = 384M
read_buffer_size = 8M
read_rnd_buffer_size = 32M

sort_buffer_size = 256M
join_buffer_size = 32M
key_buffer_size = 2048M





innodb_buffer_pool_size能够极大的提升innodb的速度



