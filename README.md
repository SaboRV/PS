# Работать с процессами;

## Задание на выбор:


    ### Написать свою реализацию lsof. Результат ДЗ - рабочий скрипт который можно запустить.

## Решение:

Простой аналог команды lsof. Программа показывает PID, USER, открытые файлы, и каким процессом они открыты. Данные извлекаются из псевдофайловой системы proc.

PID        USER                 NAME                                      COMM
2520       sabo                 /usr/lib/systemd/systemd               systemd
2520       sabo                 /usr/lib/systemd/systemd               systemd
2520       sabo                 /usr/lib/systemd/systemd               systemd
2520       sabo                 /usr/lib/systemd/systemd               systemd
2520       sabo                 /usr/lib/systemd/systemd               systemd
2520       sabo                 /usr/lib/x86_64-linux-gnu/libgpg-error.so.0.32.1         systemd
2520       sabo                 /usr/lib/x86_64-linux-gnu/libgpg-error.so.0.32.1         systemd
2520       sabo                 /usr/lib/x86_64-linux-gnu/libgpg-error.so.0.32.1         systemd
2520       sabo                 /usr/lib/x86_64-linux-gnu/libgpg-error.so.0.32.1         systemd
2520       sabo                 /usr/lib/x86_64-linux-gnu/libgpg-error.so.0.32.1         systemd
2520       sabo                 /usr/lib/x86_64-linux-gnu/libcrypto.so.3         systemd
2520       sabo                 /usr/lib/x86_64-linux-gnu/libcrypto.so.3         systemd
2520       sabo                 /usr/lib/x86_64-linux-gnu/libcrypto.so.3         systemd
2520       sabo                 /usr/lib/x86_64-linux-gnu/libcrypto.so.3         systemd
2520       sabo                 /usr/lib/x86_64-linux-gnu/libcrypto.so.3         systemd
2520       sabo                 /usr/lib/x86_64-linux-gnu/libpcre2-8.so.0.10.4         systemd
2520       sabo                 /usr/lib/x86_64-linux-gnu/libpcre2-8.so.0.10.4         systemd
2520       sabo                 /usr/lib/x86_64-linux-gnu/libpcre2-8.so.0.10.4         systemd
2520       sabo                 /usr/lib/x86_64-linux-gnu/libpcre2-8.so.0.10.4         systemd
2520       sabo                 /usr/lib/x86_64-linux-gnu/libpcre2-8.so.0.10.4         systemd
2520       sabo                 /usr/lib/x86_64-linux-gnu/liblzma.so.5.2.5         systemd
2520       sabo                 /usr/lib/x86_64-linux-gnu/liblzma.so.5.2.5         systemd
2520       sabo                 /usr/lib/x86_64-linux-gnu/liblzma.so.5.2.5         systemd
2520       sabo                 /usr/lib/x86_64-linux-gnu/liblzma.so.5.2.5         systemd
2520       sabo                 /usr/lib/x86_64-linux-gnu/liblzma.so.5.2.5         systemd
2520       sabo                 /usr/lib/x86_64-linux-gnu/libzstd.so.1.4.8         systemd
2520       sabo                 /usr/lib/x86_64-linux-gnu/libzstd.so.1.4.8         systemd
