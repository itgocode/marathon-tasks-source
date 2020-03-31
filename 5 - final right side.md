# 1 - Зазоры между секциями

## Стартовый код

```html
<section class="bio">
  <h1 class="bio-title">Anton Chornyi</h1>
  <!-- Плейсхолдер разметки этой секции -->
</section>

<section class="projects">
  <h2 class="projects-title">Projects</h2>

  <!-- Плейсхолдер разметки этой секции -->
</section>

<section class="jobs">
  <h2 class="jobs-title">Employment history</h2>

  <!-- Плейсхолдер разметки этой секции -->
</section>

<section class="education">
  <h2 class="education-title">Education</h2>

  <!-- Плейсхолдер разметки этой секции -->
</section>
```

```css
.bio,
.projects,
.jobs,
.education {
}
```

## Код результата

```css
.bio,
.projects,
.jobs,
.education {
  margin-bottom: 60px;
}
```

## Критерии

Будут

# 2 - Обёртка и падинги

## Термины для теории

- падинг

## Стартовый код

```html
<div class="right-side">
  <section class="bio">
    <h1 class="bio-title">Anton Chornyi</h1>
    <!-- Плейсхолдер разметки этой секции -->
  </section>

  <section class="projects">
    <h2 class="projects-title">Projects</h2>

    <!-- Плейсхолдер разметки этой секции -->
  </section>

  <section class="jobs">
    <h2 class="jobs-title">Employment history</h2>

    <!-- Плейсхолдер разметки этой секции -->
  </section>

  <section class="education">
    <h2 class="education-title">Education</h2>

    <!-- Плейсхолдер разметки этой секции -->
  </section>
</div>
```

```css
.bio,
.projects,
.jobs,
.education {
  margin-bottom: 60px;
}
```

## Код результата

```css
.bio,
.projects,
.jobs,
.education {
  margin-bottom: 60px;
}

.right-side {
  padding-left: 80px;
  paddding-right: 200px;
  padding-top: 68px;
  padding-bottom: 68px;
}
```

## Критерии

Будут
