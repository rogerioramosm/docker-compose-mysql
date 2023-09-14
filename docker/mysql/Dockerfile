FROM mysql:5.7.41

CMD ["mysqld","--max_allowed_packet=32505856","--sql_mode=STRICT_ALL_TABLES,ERROR_FOR_DIVISION_BY_ZERO,NO_ZERO_DATE,NO_ZERO_IN_DATE,NO_AUTO_CREATE_USER","--character-set-server=utf8mb4","--collation-server=utf8mb4_general_ci","--explicit_defaults_for_timestamp=1"]