# 1 - Тег

Имя в вашем резюме это самый главный заголовок страницы, поэтому используйте тег
`<h1>`. Текст тега должен содержать ваше имя.

## Стартовый код

```html

```

## Код результата

```html
<h1>Anton Chornyi</h1>
```

## Критерии

- Код должен содержать тег-заголовок с именем h1
- Текст заголовка не должен быть пустым
- Других тегов в тексте быть не должно

# 2 - Биография (абзацы)

Добавьте два тега абзацев. Один для названия профессии, а второй для биографии.

## Стартовый код

```html
<h1>Anton Chornyi</h1>

Front-end developer
<!--  -->
Lorem ipsum dolor sit amet consectetur adipisicing elit. Amet odio adipisci
illo, earum atque quae, sequi magni consectetur sit perferendis sunt laborum
ipsum quas. A incidunt temporibus aut harum ad.
```

## Код результата

```html
<h1>Anton Chornyi</h1>
<p>Front-end developer</p>
<p>
  Lorem ipsum dolor sit amet consectetur adipisicing elit. Amet odio adipisci
  illo, earum atque quae, sequi magni consectetur sit perferendis sunt laborum
  ipsum quas. A incidunt temporibus aut harum ad.
</p>
```

## Критерии

Будут

# 3 - Проекты (заголовок)

Добавьте тег заголовка второго уровня для секции проектов.

## Стартовый код

```html
Projects
```

## Код результата

```html
<h2>Projects</h2>
```

## Критерии

Будут

# 4 - Проекты (список)

Используйте тег `<ol>` для разметки списка проектов.

## Стартовый код

```html
<h2>Projects</h2>

https://lovecamp.allinsol.com
<!--  -->
https://cryptohub.goit.ua
<!--  -->
https://kidslike.goit.co.ua
```

## Код результата

```html
<h2>Project</h2>

<ol>
  <li>https://lovecamp.allinsol.com</li>
  <li>https://cryptohub.goit.ua</li>
  <li>https://kidslike.goit.co.ua</li>
</ol>
```

## Критерии

Будут

# 5 - Проекты (список ссылок)

Оберните текст внутри каждого `<li>` ссылкой. Значение атрибута `href` и текст
ссылки должны быть одинаковыми.

## Стартовый код

```html
<h2>Project</h2>

<ol>
  <li>https://lovecamp.allinsol.com</li>
  <li>https://cryptohub.goit.ua</li>
  <li>https://kidslike.goit.co.ua</li>
</ol>
```

## Код результата

```html
<h2>Project</h2>

<ol>
  <li>
    <a href="https://lovecamp.allinsol.com">https://lovecamp.allinsol.com</a>
  </li>
  <li>
    <a href="https://cryptohub.goit.ua">https://cryptohub.goit.ua</a>
  </li>
  <li>
    <a href="https://kidslike.goit.co.ua">https://kidslike.goit.co.ua</a>
  </li>
</ol>
```

## Критерии

Будут

# 6 - Work experience (место работы)

Добавьте разметку для должности (заголовок третьего уровня) и периода работы
(абзац).

## Стартовый код

```html
<h2>Work experience</h2>

<!--  -->
Front-end developer at Freelance
<!--  -->
September 2019 - up to now
```

## Код результата

```html
<h2>Work experience</h2>

<h3>Front-end developer at Freelance</h3>
<p>September 2019 - up to now</p>
```

## Критерии

Будут

# 7 - Work experience (список обязанностей)

Добавьте разметку списка обязанностей используя маркированный список `<ul>`.

## Стартовый код

```html
<h2>Work experience</h2>

<h3>Front-end developer at Freelance</h3>
<p>September 2019 - up to now</p>

<!--  -->
Lorem ipsum dolor sit amet.
<!--  -->
Quaerat corrupti eum harum eveniet
<!--  -->
Sit quasi libero facilis ea
```

## Код результата

```html
<h2>Employment history</h2>

<h3>Front-end developer at Freelance</h3>
<p>September 2019 - up to now</p>

<ul>
  <li>Lorem ipsum dolor sit amet.</li>
  <li>Quaerat corrupti eum harum eveniet?</li>
  <li>Sit quasi libero facilis ea?</li>
</ul>
```

## Критерии

Будут

# 8 - Work experience (полный список)

Добавьте разметку еще двух мест работы из макета.

## Стартовый код

```html
<h2>Employment history</h2>

<h3>Front-end developer at Freelance</h3>
<p>September 2019 - up to now</p>

<ul>
  <li>Lorem ipsum dolor sit amet.</li>
  <li>Quaerat corrupti eum harum eveniet?</li>
  <li>Sit quasi libero facilis ea?</li>
</ul>

<!-- Разметка второго места работы -->

<!-- Разметка третьего места работы -->
```

## Код результата

```html
<h2>Employment history</h2>

<h3>Front-end developer at Freelance</h3>
<p>September 2019 - up to now</p>
<ul>
  <li>Lorem ipsum dolor sit amet.</li>
  <li>Quaerat corrupti eum harum eveniet?</li>
  <li>Sit quasi libero facilis ea?</li>
</ul>

<h3>Front-end developer at Freelance</h3>
<p>September 2019 - up to now</p>
<ul>
  <li>Lorem ipsum dolor sit amet.</li>
  <li>Quaerat corrupti eum harum eveniet?</li>
  <li>Sit quasi libero facilis ea?</li>
</ul>

<h3>Front-end developer at Freelance</h3>
<p>September 2019 - up to now</p>
<ul>
  <li>Lorem ipsum dolor sit amet.</li>
  <li>Quaerat corrupti eum harum eveniet?</li>
  <li>Sit quasi libero facilis ea?</li>
</ul>
```

## Критерии

Будут

# 9 - Education (всё)

Напишите разметку блока образования по аналогии с тем как вы делали разметку
мест работы (8 - Work experience).

## Стартовый код

```html
<h2>Education</h2>

<!--  -->
Manager, Kharkiv
<!--  -->
September 2019 - up to now

<!--  -->
Manager, Kharkiv
<!--  -->
September 2019 - up to now
```

## Код результата

```html
<h2>Education</h2>

<h3>Manager, Kharkiv</h3>
<p>September 2019 - up to now</p>

<h3>Manager, Kharkiv</h3>
<p>September 2019 - up to now</p>
```

## Критерии

Будут

# 10 - Секции

Оберните логические блоки (секции): биография, проекты, опыт работы и
образование тегами `<section>`, как на изображении.

## Стартовый код

```html
<h1>Anton Chornyi</h1>
<p>Front-end developer</p>
<p>
  Lorem ipsum dolor sit amet consectetur adipisicing elit. Amet odio adipisci
  illo, earum atque quae, sequi magni consectetur sit perferendis sunt laborum
  ipsum quas. A incidunt temporibus aut harum ad.
</p>

<h2>Projects</h2>

<ol>
  <li>
    <a href="https://lovecamp.allinsol.com">https://lovecamp.allinsol.com</a>
  </li>
  <li>
    <a href="https://cryptohub.goit.ua">https://cryptohub.goit.ua</a>
  </li>
  <li>
    <a href="https://kidslike.goit.co.ua">https://kidslike.goit.co.ua</a>
  </li>
</ol>

<h2>Employment history</h2>

<h3>Front-end developer at Freelance</h3>
<p>September 2019 - up to now</p>
<ul>
  <li>Lorem ipsum dolor sit amet.</li>
  <li>Quaerat corrupti eum harum eveniet?</li>
  <li>Sit quasi libero facilis ea?</li>
</ul>

<h3>Front-end developer at Freelance</h3>
<p>September 2019 - up to now</p>
<ul>
  <li>Lorem ipsum dolor sit amet.</li>
  <li>Quaerat corrupti eum harum eveniet?</li>
  <li>Sit quasi libero facilis ea?</li>
</ul>

<h3>Front-end developer at Freelance</h3>
<p>September 2019 - up to now</p>
<ul>
  <li>Lorem ipsum dolor sit amet.</li>
  <li>Quaerat corrupti eum harum eveniet?</li>
  <li>Sit quasi libero facilis ea?</li>
</ul>

<h2>Education</h2>

<h3>Manager, Kharkiv</h3>
<p>September 2019 - up to now</p>

<h3>Manager, Kharkiv</h3>
<p>September 2019 - up to now</p>
```

## Код результата

```html
<section>
  <h1>Anton Chornyi</h1>
  <p>Front-end developer</p>
  <p>
    Lorem ipsum dolor sit amet consectetur adipisicing elit. Amet odio adipisci
    illo, earum atque quae, sequi magni consectetur sit perferendis sunt laborum
    ipsum quas. A incidunt temporibus aut harum ad.
  </p>
</section>

<section>
  <h2>Projects</h2>

  <ol>
    <li>
      <a href="https://lovecamp.allinsol.com/">https://lovecamp.allinsol.com</a>
    </li>
    <li>
      <a href="https://cryptohub.goit.ua/">https://cryptohub.goit.ua</a>
    </li>
    <li>
      <a href="https://kidslike.goit.co.ua/">https://kidslike.goit.co.ua</a>
    </li>
  </ol>
</section>

<section>
  <h2>Employment history</h2>

  <h3>Front-end developer at Freelance</h3>
  <p>September 2019 - up to now</p>
  <ul>
    <li>Lorem ipsum dolor sit amet.</li>
    <li>Quaerat corrupti eum harum eveniet?</li>
    <li>Sit quasi libero facilis ea?</li>
  </ul>

  <h3>Front-end developer at Freelance</h3>
  <p>September 2019 - up to now</p>
  <ul>
    <li>Lorem ipsum dolor sit amet.</li>
    <li>Quaerat corrupti eum harum eveniet?</li>
    <li>Sit quasi libero facilis ea?</li>
  </ul>

  <h3>Front-end developer at Freelance</h3>
  <p>September 2019 - up to now</p>
  <ul>
    <li>Lorem ipsum dolor sit amet.</li>
    <li>Quaerat corrupti eum harum eveniet?</li>
    <li>Sit quasi libero facilis ea?</li>
  </ul>
</section>

<section>
  <h2>Education</h2>

  <h3>Manager, Kharkiv</h3>
  <p>September 2019 - up to now</p>

  <h3>Manager, Kharkiv</h3>
  <p>September 2019 - up to now</p>
</section>
```

## Критерии

Будут
