# 1 - Изображение

Используя тег `<img>` создайте разметку изображения.

## Стартовый код

```html

```

## Код результата

```html
<img
  src="https://cdn.pixabay.com/photo/2014/04/13/20/49/cat-323262_1280.jpg"
  alt="Моя фотография"
  width="370"
/>
```

## Критерии

<!-- TODO: дадим абсолютную ссылку -->

Не забудьте добавить обязательные атрибуты `src` и `alt`, а также атрибут `width`
для задания ширины картинки.

# 2 - Контакты

<!-- TODO: Теория - там список без маркеров, объяснить что это CSS -->

Добавьте разметку секции контактов с заголовком и маркированным списком из двух
элементов: телефон и мейл.

## Стартовый код

```html
Contacts

<!--  -->
Phone: +38077121212
<!--  -->
Email: some@mail.com
```

## Код результата

```html
<section>
  <h2>Contacts</h2>

  <ul>
    <li>Phone: +38077121212</li>
    <li>Email: some@mail.com</li>
  </ul>
</section>
```

## Критерии

Будет

# 3 - Контакты

Внутри элементов списка, оберните телефонный номер и мейл в ссылки.
Используйте правильные значения для атрибутов `href`.

## Стартовый код

```html
<section>
  <h2>Contacts</h2>

  <ul>
    <li>Phone: +38077121212</li>
    <li>Email: some@mail.com</li>
  </ul>
</section>
```

## Код результата

```html
<section>
  <h2>Contacts</h2>

  <ul>
    <li>Phone: <a href="tel:+38077121212">+38077121212</a></li>
    <li>Email: <a href="mailto:some@mail.com">some@mail.com</a></li>
  </ul>
</section>
```

## Критерии

Будет

# 4 - Скиллы

Добавьте разметку секции софт скиллов аналогично

## Стартовый код

```html
<section>
  <h2>Tech skills</h2>

  <ul>
    <li>HTML</li>
    <li>CSS</li>
    <li>Git</li>
    <li>JavaScript</li>
    <li>React</li>
    <li>Node.js</li>
  </ul>
</section>

<!-- Разметка секции софт скилз -->
```

## Код результата

```html
<section>
  <h2>Tech skills</h2>

  <ul>
    <li>HTML</li>
    <li>CSS</li>
    <li>Git</li>
    <li>JavaScript</li>
    <li>React</li>
    <li>Node.js</li>
  </ul>
</section>

<section>
  <h2>Soft skills</h2>

  <ul>
    <li>Scrum</li>
    <li>Agile</li>
    <li>GTD</li>
    <li>Teamwork</li>
  </ul>
</section>
```

## Критерии

Будет
