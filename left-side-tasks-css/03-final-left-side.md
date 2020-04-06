# 1 - Секции (маржин)

```html
<aside class="left-side">
  <img
    class="photo"
    src="https://cdn.pixabay.com/photo/2014/04/13/20/49/cat-323262_1280.jpg"
    alt="Моя фотография"
    width="370"
  />

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
```

## Код результата

```css
.photo,
.contacts,
.skills {
  margin-bottom: 60px;
}
```

# 2 - Левая сторона (падинг)

```html
<aside class="left-side">
  <img
    class="photo"
    src="https://cdn.pixabay.com/photo/2014/04/13/20/49/cat-323262_1280.jpg"
    alt="Моя фотография"
    width="370"
  />

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
.photo,
.contacts,
.skills {
  margin-bottom: 60px;
}
```

## Код результата

```css
.photo,
.contacts,
.skills {
  margin-bottom: 60px;
}

.left-side {
  padding-left: 40px;
}
```

# 3 - Левая сторона (падинг контента)

```html
<aside class="left-side">
  <img
    class="photo"
    src="https://cdn.pixabay.com/photo/2014/04/13/20/49/cat-323262_1280.jpg"
    alt="Моя фотография"
    width="370"
  />

  <div class="content">
    <section class="contacts">
      <h2 class="contacts-title">Contacts</h2>

      <!-- Плейсхолдер разметки этой секции -->
    </section>

    <section class="skills">
      <h2 class="skills-title">Tech skills</h2>

      <!-- Плейсхолдер разметки этой секции -->
    </section>

    <section class="skills">
      <h2 class="skills-title">Soft skills</h2>

      <!-- Плейсхолдер разметки этой секции -->
    </section>
  </div>
</aside>
```

```css
.photo,
.contacts,
.skills {
  margin-bottom: 60px;
}

.left-side .content {
}
```

## Код результата

```css
.photo,
.contacts,
.skills {
  margin-bottom: 60px;
}

.left-side .content {
  padding-left: 40px;
}
```
