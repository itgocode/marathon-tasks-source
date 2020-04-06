# 1 - Скиллы (текст и цвет)

Добавьте стили цвета и текста

## Стартовый код

```html
<aside class="left-side">
  <!-- Разметка секции контактов -->

  <section class="skills">
    <h2 class="skills-title">Tech skills</h2>

    <ul>
      <li class="skills-item">HTML</li>
      <li class="skills-item">CSS</li>
      <li class="skills-item">Git</li>
      <li class="skills-item">JavaScript</li>
      <li class="skills-item">React</li>
      <li class="skills-item">Node.js</li>
    </ul>
  </section>

  <section class="skills">
    <h2 class="skills-title">Soft skills</h2>

    <ul>
      <li class="skills-item">Scrum</li>
      <li class="skills-item">Agile</li>
      <li class="skills-item">GTD</li>
      <li class="skills-item">Teamwork</li>
    </ul>
  </section>
</aside>
```

## Код результата

```css
.left-side {
  width: 370px;
  background-color: #1e2939;
}

.skills-title {
  font-size: 22px;
  line-height: 24px;
  color: #ffffff;
}

.skills-item {
  font-size: 14px;
  line-height: 24px;
  color: #ffffff;
}
```

## Критерии

Будет

# 2 - Псевдоэлементы и мнемоники (before, after)

<!-- TODO: подставить код мнемоники в content -->
<!--
TODO: подумать над примером мнемоники не только в псевдо
<p>Copyright &copy; GoIT 2020</p>
-->

```html
<h1 class="title">Lorem ipsum dolor sit amet</h1>
```

```css
.title {
  font-size: 48px;
  color: #2a2a2a;
}
```

## Код результата

```css
.title {
  font-size: 48px;
  color: #2a2a2a;
}

.title::before {
  content: '«';
  color: green;
}

.title::after {
  content: '»';
  color: orange;
}
```

# 3 - Скиллы (рисочка)

Добавьте оформление рисочки

<!-- https://www.lockedownseo.com/change-the-bullet-color-of-a-list-item-with-css/ -->

## Стартовый код

```html
<aside class="left-side">
  <!-- Разметка секции контактов -->

  <section class="skills">
    <h2 class="skills-title">Tech skills</h2>

    <ul class="skills-list">
      <li class="skills-item">HTML</li>
      <li class="skills-item">CSS</li>
      <li class="skills-item">Git</li>
      <li class="skills-item">JavaScript</li>
      <li class="skills-item">React</li>
      <li class="skills-item">Node.js</li>
    </ul>
  </section>

  <section class="skills">
    <h2 class="skills-title">Soft skills</h2>

    <ul class="skills-list">
      <li class="skills-item">Scrum</li>
      <li class="skills-item">Agile</li>
      <li class="skills-item">GTD</li>
      <li class="skills-item">Teamwork</li>
    </ul>
  </section>
</aside>
```

```css
.left-side {
  width: 370px;
  background-color: #1e2939;
}

.skills-title {
  font-size: 22px;
  line-height: 24px;
  color: #ffffff;
}

.skills-item {
  font-size: 14px;
  line-height: 24px;
  color: #ffffff;
}

.skills-list {
  list-style: none;
  padding: 0;
}
```

## Код результата

```css
.left-side {
  width: 370px;
  background-color: #1e2939;
}

.skills-title {
  font-size: 22px;
  line-height: 24px;
  color: #ffffff;
}

.skills-item {
  font-size: 14px;
  line-height: 24px;
  color: #ffffff;
}

.skills-list {
  list-style: none;
  padding: 0;
}

.skills-item::before {
  content: '\2022';
  margin-right: 8px;
  color: #ff6b08;
}
```
