---
title: 'Вопросы из разделов: Введение, Сервисы сетевой инфраструктуры'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin


date: '2024-11-27T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-11-27T00:00:00Z'


abstract: Данная статья посвещена прохождению двух первых разделов внешнего курса «Организация администрирования компьютерных сетей».


# Display this page in the Featured widget?
featured: true


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - kurs

---

# Выполнение внешнего курса

## Раздел Введение

**Задание 1.** Какие вы ещё знаете упрощения при работе в консоли Linux или в Windows?

В курсе было приведено много возможностей упростить работу в терминале, я вспомнила и добавила то, чем пользуют сама.

![Упрощение по работе в консоли](image/курс1.png)

## Раздел Сервисы сетевой инфраструктуры

**Задание 2.** В каком файле в Linux настраивается локальное разрешение имён?

Сразу после установки операционной системы создается файл hosts, местонахождение которого на Linux /etc/hosts.

![Местонахождение файла для локального разрешения имен для Linux](image/курс2.png)


**Задание 3.** Какие типы запросов к DNS существуют?

Существуют две подгруппы запросов: рекурсивный и нерекурсивный, прямой и обратный.

![Типы запросов к DNS](image/курс3.png)

**Задание 4.** В каком режиме может работать сервер DNS в корпоративной сети?

Существует четыре режима работы: кэширующий, перенаправляющий, авторитетный (первичный — master), авторитетный (вторичный — slave).

![Режимы работы сервера DNS](image/курс4.png)


**Задание 5.** Какие параметры сетевое устройство получает по DHCP?

Весь перечень параметров представлен в курсе, необходимо было посмотреть, какие из них приведены в задании.

![Параметры сетевого устройства по DHCP](image/курс5.png)


**Задание 6.** Какие сетевые устройства поддерживают протокол DHCP для получения настроек сети?

DHCP (Dynamic Host Configuration Protocol) — это протокол динамической конфигурации сетевых устройств, то есть все сетевые устройства поддерживают этот протокол.

![Поддерживаемые протокол DHCP сетевые устройства](image/курс6.png)

