# 1 - флексы

## Стартовый код

```html
<div class="container">
  <aside class="left-side">
    <!-- Весь HTML -->
  </aside>
  <div class="right-side">
    <!-- Весь HTML -->
  </div>
</div>
```

```css
/* Весь CSS */

.container {
}

.left-side {
}

.right-side {
}
```

## Код результата

```css
/* Весь CSS */

.container {
  display: flex;
  width: 1200px;
}

.left-side {
  width: 370px;
}

.right-side {
  width: 830px;
}
```

# 2 - Центрирование контейнера

## Стартовый код

```html
<div class="container">
  <aside class="left-side">
    <!-- Весь HTML -->
  </aside>
  <div class="right-side">
    <!-- Весь HTML -->
  </div>
</div>
```

```css
/* Весь CSS */

.container {
  display: flex;
  width: 1200px;

  /* Сюда стили */
}

.left-side {
  width: 370px;
}

.right-side {
  width: 830px;
}
```

## Код результата

```css
/* Весь CSS */

.container {
  display: flex;
  width: 1200px;

  margin-left: auto;
  margin-right: auto;
}

.left-side {
  width: 370px;
}

.right-side {
  width: 830px;
}
```
