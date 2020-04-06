# 1 - Контакты (размер шрифта и интерлиньяж)

## Стартовый код

```html
<aside class="left-side">
  <section class="contacts">
    <h2 class="contacts-title">Contacts</h2>

    <ul>
      <li class="contacts-item">
        Phone: <a href="tel:+38077121212">+38077121212</a>
      </li>
      <li class="contacts-item">
        Email:
        <a href="mailto:some@mail.com">some@mail.com</a>
      </li>
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

.contacts-title {
  font-size: 22px;
  line-height: 24px;
}

.contacts-item {
  font-size: 14px;
  line-height: 24px;
}
```

## Критерии

Будет

# 2 - Контакты (цвет)

## Стартовый код

```html
<aside class="left-side">
  <section class="contacts">
    <h2 class="contacts-title">Contacts</h2>

    <ul>
      <li class="contacts-item">
        Phone: <a href="tel:+38077121212" class="contacts-link">+38077121212</a>
      </li>
      <li class="contacts-item">
        Email:
        <a href="mailto:some@mail.com" class="contacts-link">some@mail.com</a>
      </li>
    </ul>
  </section>
</aside>
```

```css
.left-side {
  width: 370px;
  background-color: #1e2939;
}

.contacts-title {
  font-size: 22px;
  line-height: 24px;
}

.contacts-item {
  font-size: 14px;
  line-height: 24px;
}

.contacts-link {
}
```

## Код результата

```css
.contacts-title {
  font-size: 22px;
  line-height: 24px;

  color: #ffffff;
}

.contacts-item {
  font-size: 14px;
  line-height: 24px;

  color: #ffffff;
}

.contacts-link {
  color: rgba(255, 255, 255, 0.6);
}
```

## Критерии

Будет

# 3 - Контакты (ховер)

## Стартовый код

```html
<aside class="left-side">
  <section class="contacts">
    <h2 class="contacts-title">Contacts</h2>

    <ul>
      <li class="contacts-item">
        Phone: <a href="tel:+38077121212" class="contacts-link">+38077121212</a>
      </li>
      <li class="contacts-item">
        Email:
        <a href="mailto:some@mail.com" class="contacts-link">some@mail.com</a>
      </li>
    </ul>
  </section>
</aside>
```

```css
.left-side {
  width: 370px;
  background-color: #1e2939;
}

.contacts-title {
  font-size: 22px;
  line-height: 24px;

  color: #ffffff;
}

.contacts-item {
  font-size: 14px;
  line-height: 24px;

  color: #ffffff;
}

.contacts-link {
  color: rgba(255, 255, 255, 0.6);
}
```

## Код результата

```css
.contacts-title {
  font-size: 22px;
  line-height: 24px;

  color: #ffffff;
}

.contacts-item {
  font-size: 14px;
  line-height: 24px;

  color: #ffffff;
}

.contacts-link {
  color: rgba(255, 255, 255, 0.6);
}

.contacts-link:hover {
  color: #ff6b08;
}
```

## Критерии

Будет
