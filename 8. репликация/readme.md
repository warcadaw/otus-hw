## 8. Репликация


# Физическая

1. Настройка pg_hba хоста :


![](pg_hba_host.jpg)


2. Настройка задержки в 5 минут

![](recovery_min_applay_delay.jpg)



3. Выполнение на реплике pg_basebackup


![](recovery_min_applay_delay.jpg)



4. pg_is_recovery на реплике


![](pg_is_recovery.jpg)

5. pg_replication на хосте

![](pg_replication.jpg)

# Логическая

1. Действия на хосте :

![](host_publication.jpg)

2. Создание таблицы на реплике

![](create_table_repl.jpg)

3. Создание подписки на реплике

![](create_subscr.jpg)