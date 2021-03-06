---
layout: post
title: "<strong>Строчно</strong> - <strong>Блочные</strong> элементы HTML"
subtitle: "HTML имеет 2 основных <strong>типа</strong> элементов"
section: html
---

В HTML, Вам, в основном, будет попадаться 2 типа элементов:

* **блочные**,такие как:

    * параграф `<p>`
    * списки: неупорядоченные (с точками в начале) `<ul>` или упорядоченные списки (с номерами) `<ol>`
    * заголовки: от 1-го уровня `<h1>` до 6-го `<h6>`
    * содержание `<article>`
    * секции `<section>`
    * длинные цитаты `<blockquote>`

* **строчные**,такие как:

    * ссылки `<a>`
    * выделяемые слова `<em>`
    * важные (жирные) слова `<strong>`
    * короткие цитаты `<q>`
    * сокращения `<abbr>`

**Блочные** элементы предназначены для **структурирования** основных частей вашей страницы,  путем деления содержимого в _связанных между собой_ блоках.

**Строчные** элементы предназначены для дифференциации _части_ текста, чтобы дать ему определенную функцию или смысл. Строчные элементы, как правило, включают в себя одно или несколько слов.


{% highlight html %}
<p>Вы видели это <a href="http://www.youtube.com">изумительное видео</a> на YouTube?</p>
{% endhighlight %}

### Открывающиеся и закрывающиеся теги

**Все** блочные элементы имеют открывающиеся и закрывающиеся теги.

В результате, Самозакрывающиеся элементы являются **строчными** элементами, просто потому, что их синтаксис не позволяет им содержать любой другой HTML элемент.

<div class="table">
  <table>
    <tr>
      <th class="empty"></th>
      <th>Имеют открывающиеся и закрывающиеся теги</th>
      <th>Самозакрывающиеся</th>
    </tr>
    <tr>
      <th>Блочные элементы</th>
      <td>
        <code>&lt;p&gt;</code>
        <code>&lt;/p&gt;</code>
        <br>
        <code>&lt;ul&gt;</code>
        <code>&lt;/ul&gt;</code>
        <br>
        <code>&lt;ol&gt;</code>
        <code>&lt;/ol&gt;</code>
      </td>
      <td>
        <strong>Невозможно</strong>
      </td>
    </tr>
    <tr>
      <th>Строчные элементы</th>
      <td>
        <code>&lt;a&gt;</code>
        <code>&lt;/a&gt;</code>
        <br>
        <code>&lt;strong&gt;</code>
        <code>&lt;/strong&gt;</code>
        <br>
        <code>&lt;em&gt;</code>
        <code>&lt;/em&gt;</code>
      </td>
      <td>
        <code>&lt;input&gt;</code>
        <br>
        <code>&lt;br&gt;</code>
        <br>
        <code>&lt;img&gt;</code>
      </td>
    </tr>
  </table>
</div>

### Другие типы HTML элементов

Есть несколько исключений блочных / строчных элементов, но те, с которыми Вы чаще всего будете сталкиваться являются:

* **элементы списка** для `<li>`
* **таблица**, **строки таблиц**, **ячейки таблиц** для `<table>`, `<tr>` и `<td>` соответственно
