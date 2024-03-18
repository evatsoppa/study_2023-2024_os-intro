---
## Front matter
lang: ru-RU
title: Структура научной презентации
subtitle: Простейший шаблон
author:
  - Цоппа Е. Э.
institute:
  - Российский университет дружбы народов, Москва, Россия
date: 26 февраля 2024

## i18n babel
babel-lang: russian
babel-otherlangs: english

## Formatting pdf
toc: false
toc-title: Содержание
slide_level: 2
aspectratio: 169
section-titles: true
theme: metropolis
header-includes:
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
 - '\makeatletter'
 - '\beamer@ignorenonframefalse'
 - '\makeatother'
---

# Информация

## Докладчик

  * Цоппа Ева Эдуардовна
  * студентка НКАбд-06-23
  * Российский университет дружбы народов

## Актуальность

Научному работнику полезно иметь сайт-портфолио про него и его проекты.

# Цель работы

Продолжить работы со своим сайтом. Редактировать его в соответствии с требованиями. Добавить данные о себе.

# Задание

1. Разместить фотографию владельца сайта.
2. Разместить краткое описание владельца сайта (Biography).
3. Добавить информацию об интересах (Interests).
4. Добавить информацию от образовании (Education).
5. Сделать пост по прошедшей неделе.
6. Добавить пост на тему управление версиями. Git.

# Теоретическое введение

Hugo — генератор статических страниц для интернета.

**Коротко: что такое статические сайты**
    1. Статические сайты состоят из уже готовых HTML-страниц.
    2. Эти страницы собираются заранее, а не готовятся для пользователя «на лету». Для этого используют генераторы статичных сайтов.
    3. Так как это почти чистый HTML, то такие сайты быстрее загружаются и их проще переносить с сервера на сервер.
    4. Минус: если нужно что-то обновить на странице, то сначала это правят в исходном файле, а потом запускают обновление в генераторе.
    5. Ещё минус: такие страницы не подходят для интернет-магазинов или сайтов с личным кабинетом, потому что в статике нельзя сформировать страницу для каждого отдельного пользователя.

# Выполнение лабораторной работы

Добавила свою фотографию в папку blog/content/authors/admin, удалила фотографию шаблона 

![Screenshot_147](https://github.com/evatsoppa/study_2023-2024_os-intro/assets/145338773/826d799f-0273-421e-848d-a66d83d385b8)

В файлу index.md в той же папке изменяю поля. Начинаю с библиографии 

![Screenshot_148](https://github.com/evatsoppa/study_2023-2024_os-intro/assets/145338773/57cb2bc4-b603-4cd0-8cd8-60d2e67626ff)

Изменила интересы на свои 

![Screenshot_149](https://github.com/evatsoppa/study_2023-2024_os-intro/assets/145338773/5f389e26-ea63-4bf5-88a9-7fbe86986ff0)

Добавила свое образование 

![Screenshot_164](https://github.com/evatsoppa/study_2023-2024_os-intro/assets/145338773/0b185462-fcef-4a34-8e2f-53d37d26953e)

Обновила личные данные, чтобы они были про меня 

![Screenshot_151](https://github.com/evatsoppa/study_2023-2024_os-intro/assets/145338773/8173195b-c41e-4c56-9aa3-3d6974dd6aeb)

Проверила, что на локальном сайте все есть. Локальный сайт запускается с помощью hugo server 

![Screenshot_165](https://github.com/evatsoppa/study_2023-2024_os-intro/assets/145338773/e3f0b3ac-cccf-454c-962f-2c50a800b399)

Создаю папки в директории post, которые обозначают посты и в которых будут тексты постов, картинки и доп. файлы 

![Screenshot_153](https://github.com/evatsoppa/study_2023-2024_os-intro/assets/145338773/61f77f4f-f9bd-4333-816b-754f27be8ffb)

Заполнила файл index.md в post1, это пост про прошедшую неделю 

![Screenshot_154](https://github.com/evatsoppa/study_2023-2024_os-intro/assets/145338773/c92d689c-0f0b-4d63-884a-06032aab5f42)

Заполнила файл index.md в post2, это пост про управление версиями Git 

![Screenshot_155](https://github.com/evatsoppa/study_2023-2024_os-intro/assets/145338773/78beba6c-cfc7-442a-bb0f-e30a6e317e7f)

Проверяю посты на локальном сервере 

![Screenshot_156](https://github.com/evatsoppa/study_2023-2024_os-intro/assets/145338773/2e2a5383-1d9e-4d65-9d3a-655acb367412)

Закрываю локальный сервер. Генерирую сайт с изменениями 

![Screenshot_157](https://github.com/evatsoppa/study_2023-2024_os-intro/assets/145338773/e5cd406e-ac99-4b55-9cf6-bf451164314e)

Сохраняю изменения на гите 

![Screenshot_158](https://github.com/evatsoppa/study_2023-2024_os-intro/assets/145338773/dbe2e7cb-051d-4e66-8544-401b1eeaf46c)

Сохраняю изменения в папке, изменения в которйо отправятся на репозиторий, где лежит сайт 

![Screenshot_159](https://github.com/evatsoppa/study_2023-2024_os-intro/assets/145338773/0be5be4d-68d7-469c-8f02-c5131ac6d339)

Проверила, как выглядит сайт в браузере 

![Screenshot_165](https://github.com/evatsoppa/study_2023-2024_os-intro/assets/145338773/9ff1303e-de99-40a4-aa8e-c6dc95f291eb)

# Выводы

В процессе выполнения второго этапа индивидуального проекта я научилась редактировать данные о себе, а также писать посты и добавлять их на сайт.
