---
title: 'Drupal 9.4.6'
slug: wiki/drupal/releases/9.4.6
core: 9
metatags:
  title: 'Drupal 9.4.6: Список изменений'
  description: 'Список изменений Drupal 9.4.6.'
authors:
  - Niklan
category:
  area: 'Drupal 9.4.x'
  title: Drupal 9.4.6
  order: 5
---

<Aside type="warning">

Данная версия находится в разработке и не предназначена для использования.

</Aside>

## CKEditor 5

- [#3222797](https://www.drupal.org/node/3222797) Добавлена поддержка миграции StyleCombo из CKEditor 4.
- [#3274937](https://www.drupal.org/node/3274937) Улучшена работа редактора в модальных и диалоговых окнах.

## JavaScript

- [#3301712](https://www.drupal.org/node/3301712) Команда `yarn build` в конце сборки теперь также обновляет 
  зависимости.

## Link

- [#3056652](https://www.drupal.org/node/3056652) (отменено) Исправлена неполадка из-за которой значения аттрибутов 
  не сохранялись в виджете.

## Migrate API

- [#3285637](https://www.drupal.org/node/3285637) Плагин-обработчик `get` теперь может обрабатывать множественные
  значения (`handle_multiple`).

## Render system

- [#2157567](https://www.drupal.org/node/2157567) Улучшена документация для свойства `path` в `hook_theme()`.

## Update system

- [#3294299](https://www.drupal.org/node/3294299) Исправлена регрессия в функциональных тестах с большим кол-вом 
  модулей.

## User

- [#3298923](https://www.drupal.org/node/3298923) Тест `ProtectedUserFieldConstraintValidatorTest` больше не выводит 
  сообщения об устаревшем коде на PHP 8.2.

## Прочие изменения

- [#3135933](https://www.drupal.org/node/3135933) Правила для `phpcs.xml` теперь сортируются в алфавитном порядке.