---
title: "`<h1>`...`<h6>`"
description: "Заголовки на странице для оформления структуры."
cover:
  author: kirakusto
  desktop: 'images/covers/desktop.svg'
  mobile: 'images/covers/mobile.svg'
  alt: 'Стена с картинами разных размеров, наверху самая большая, дальше меньше и ещё меньше'
authors:
  - doka-dog
contributors:
  - solarrust
  - skorobaeus
  - furtivite
  - rrramble
keywords:
  - заголовок
  - h1
  - h2
  - h3
  - h4
  - h5
  - h6
related:
  - a11y/screenreaders
  - css/tag-selector
  - html/main
tags:
  - doka
---

## Кратко

Используйте теги от `<h1>` до `<h6>`, чтобы размечать заголовки на странице.

## Пример

```html
<h1>Самый важный заголовок</h1>
<h2>Заголовок уровня 2</h2>
<h3>Заголовок уровня 3</h3>
<h4>Заголовок уровня 4</h4>
<h5>Заголовок уровня 5</h5>
<h6>Заголовок уровня 6</h6>
```

<iframe title="Заголовки 6 уровней" src="demos/headers/" height="480"></iframe>

## Как понять

Цифра в теге означает уровень заголовка в иерархии: от самого общего или главного `<h1>` до самого второстепенного `<h6>`. По умолчанию `<h1>` — самый крупный заголовок на странице, а `<h6>` — самый мелкий.

## Как пишется

Заголовки `<h1>`...`<h6>` всегда отображаются с новой строки. Перед заголовками и после них добавляется расстояние, которое можно регулировать с помощью CSS-стилей.

## Подсказки

💡 Основной заголовок `<h1>` может быть только один на странице.

💡 Не пропускайте заголовки разных уровней: после `<h1>` может быть только `<h2>`, но не `<h3>`.

💡 Уровень заголовка выбирайте по иерархии, а не по внешнему виду. Для уменьшения или увеличения шрифта используйте CSS-свойство `font-size`, а не уровень заголовка.

💡 С помощью тегов `<h1>`...`<h6>` можно автоматически создавать оглавления для документов.

💡 Для создания заголовка используют и обычные текстовые блок. Но информация из `<h1>`...`<h6>` легче попадает в поисковики, поэтому для заголовков лучше использовать именно эти теги.


## Ещё примеры

```html
<h1>Каталог тортов</h1>
<p>
  У нас вы можете заказать самые вкусные десерты от свадебных тортов до сочных
  тартов.
</p>

<h2>Свадебные торты</h2>
<p>Выберите начинку и внешний вид для торта своей мечты.</p>
<p>Мы выполним торт любой сложности и любой тематики по вашему эскизу или по фотографии.</p>
```

<iframe title="Заголовки" src="demos/cakes/" height="480"></iframe>
