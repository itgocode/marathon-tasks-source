# 1 - Проекты (базовое оформление: цвет и текст)

## Термины для теории

- hover

## Стартовый код

```html
<section class="projects">
  <h2 class="projects-title">Projects</h2>

  <ol>
    <li>
      <a href="https://lovecamp.allinsol.com/" class="projects-link">
        https://lovecamp.allinsol.com
      </a>
    </li>
    <li>
      <a href="https://cryptohub.goit.ua/" class="projects-link">
        https://cryptohub.goit.ua
      </a>
    </li>
    <li>
      <a href="https://kidslike.goit.co.ua/" class="projects-link">
        https://kidslike.goit.co.ua
      </a>
    </li>
  </ol>
</section>
```

```css
.projects-title {
}

.projects-link {
}
```

## Ожидаемый код

```css
.projects-title {
  margin-bottom: 14px;
  color: #2a2a2a;
  font-size: 22px;
  line-height: 24px;
}

.projects-link {
  color: #220fdc;
  font-size: 14px;
  line-height: 24px;
}
```

# 2 - Псевдокласс в качестве селектора

Для события `курсор над ссылкой` задано новое CSS правило со свойством `color` и
значением `#fff`.

Добавьте новому CSS правилу селектор состоящий из имени класса `contacts-link` и
псевдокласса `hover`.

## Стартовый код

```css
 {
  color: #fff;
}
```

```html
<a class="contacts-link" href="tel:380951138598">
  +38 095 113 85 98
</a>
```

## Код результата

```css
.contacts-link:hover {
  color: #fff;
}
```

## Критерии

- В качестве селектора должно быть имя класса `contacts-link`.
- Селектор класса должен начинаться с точки.
- Между точкой и именем класса не должно быть пробела.
- Перед псевдоклассом должно быть двоеточие.
- Перед или после двоеточие псевдокласса не должно быть пробела.
- CSS правило должно быть синтаксически верным.
- Значения CSS правил должны совпадать с заданными.
- Других селекторов, свойств или значений быть не должно.

# 3 - Проекты (ховер)

## Термины для теории

- один селектор много тегов

## Стартовый код

```html
<section class="projects">
  <h2 class="projects-title">Projects</h2>

  <ol>
    <li>
      <a href="https://lovecamp.allinsol.com/" class="projects-link">
        https://lovecamp.allinsol.com
      </a>
    </li>
    <li>
      <a href="https://cryptohub.goit.ua/" class="projects-link">
        https://cryptohub.goit.ua
      </a>
    </li>
    <li>
      <a href="https://kidslike.goit.co.ua/" class="projects-link">
        https://kidslike.goit.co.ua
      </a>
    </li>
  </ol>
</section>
```

```css
.projects-title {
  margin-bottom: 14px;
  color: #2a2a2a;
  font-size: 22px;
  line-height: 24px;
}

.projects-link {
  color: #220fdc;
  font-size: 14px;
  line-height: 24px;
}
```

## Ожидаемый код

```css
.projects-title {
  margin-bottom: 14px;
  color: #2a2a2a;
  font-size: 22px;
  line-height: 24px;
}

.projects-link {
  color: #220fdc;
  font-size: 14px;
  line-height: 24px;
}

.projects-link:hover {
  color: #ff6b08;
}
```
