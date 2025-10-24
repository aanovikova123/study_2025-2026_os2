---
## Front matter
lang: ru-RU
title: Лабораторная работа №8
subtitle: Планировщики событий
author:
  - Анастасия Новикова
institute:
  - Российский университет дружбы народов, Москва, Россия
date: 11 октября 2025

## i18n babel
babel-lang: russian
babel-otherlangs: english

## Formatting pdf
toc: false
slide_level: 2
aspectratio: 169
section-titles: true
theme: metropolis
header-includes:
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
---

# Цель работы

## Основная цель

Освоить работу с планировщиками событий cron и at в Linux, научиться создавать, редактировать и контролировать задания по расписанию.

# Планирование задач с помощью cron

## Проверка службы crond

![Статус службы crond](Screenshot_1.png){ #fig:001 width=70% }

## Настройка расписания cron

![Создание задания cron](Screenshot_2.png){ #fig:002 width=70% }

## Изменение расписания

![Редактирование расписания root cron](Screenshot_3.png){ #fig:003 width=70% }

## Скрипты в /etc/cron.hourly

![Создание скрипта eachhour](Screenshot_4.png){ #fig:004 width=70% }

## Задания в /etc/cron.d

![Создание задания в /etc/cron.d](Screenshot_5.png){ #fig:005 width=70% }

## Использование atd

![Проверка статуса службы atd](Screenshot_6.png){ #fig:006 width=70% }

# Итоги работы

## Вывод

- Изучены планировщики cron и at.  
- Настроены периодические и однократные задания.  
- Освоена работа с /etc/cron.hourly и /etc/cron.d.  
- Получены навыки автоматизации системных процессов.  
