# 1 - Опыт работы (текст)

## Термины для теории

- Последовательность оформления: текст -> цвет -> размеры

## Стартовый код

```html
<section class="jobs">
  <h2 class="jobs-title">Employment history</h2>

  <h3 class="jobs-occupation">Front-end developer at Freelance</h3>
  <p class="jobs-time">September 2019 - up to now</p>
  <ul class="experience">
    <li class="experience-item">Lorem ipsum dolor sit amet.</li>
    <li class="experience-item">Quaerat corrupti eum harum eveniet?</li>
    <li class="experience-item">Sit quasi libero facilis ea?</li>
  </ul>
</section>
```

## Ожидаемый код

```css
.jobs-title {
  font-size: 22px;
  line-height: 24px;
}

.jobs-occupation {
  font-size: 16px;
  line-height: 24px;
}

.jobs-time {
  font-size: 12px;
  line-height: 24px;
}

.experience-item {
  font-size: 14px;
  line-height: 24px;
}
```

# 2 - Опыт работы (цвет)

## Термины для теории

- Про выделени в след задании будет

## Стартовый код

```html
<section class="jobs">
  <h2 class="jobs-title">Employment history</h2>

  <h3 class="jobs-occupation">Front-end developer at Freelance</h3>
  <p class="jobs-time">September 2019 - up to now</p>
  <ul class="experience">
    <li class="experience-item">Lorem ipsum dolor sit amet.</li>
    <li class="experience-item">Quaerat corrupti eum harum eveniet?</li>
    <li class="experience-item">Sit quasi libero facilis ea?</li>
  </ul>
</section>
```

```css
.jobs-title {
  font-size: 22px;
  line-height: 24px;
}

.jobs-occupation {
  font-size: 16px;
  line-height: 24px;
}

.jobs-time {
  font-size: 12px;
  line-height: 24px;
}

.experience-item {
  font-size: 14px;
  line-height: 24px;
}
```

## Ожидаемый код

```css
.jobs-title {
  color: #2a2a2a;
  font-size: 22px;
  line-height: 24px;
}

.jobs-occupation {
  color: #2a2a2a;
  font-size: 16px;
  line-height: 24px;
}

.jobs-time {
  color: #828282;
  font-size: 12px;
  line-height: 24px;
}

.experience-item {
  color: #595959;
  font-size: 14px;
  line-height: 24px;
}
```

# 3 - Опыт работы (акцент)

## Термины для теории

- span как контейнер для декоративных эффектов

## Стартовый код

```html
<section class="jobs">
  <h2 class="jobs-title">Employment history</h2>

  <h3 class="jobs-occupation">
    Front-end developer at <span class="accent">Freelance</span>
  </h3>
  <p class="jobs-time">September 2019 - up to now</p>
  <ul class="experience">
    <li class="experience-item">Lorem ipsum dolor sit amet.</li>
    <li class="experience-item">Quaerat corrupti eum harum eveniet?</li>
    <li class="experience-item">Sit quasi libero facilis ea?</li>
  </ul>
</section>
```

```css
.jobs-title {
  color: #2a2a2a;
  font-size: 22px;
  line-height: 24px;
}

.jobs-occupation {
  color: #2a2a2a;
  font-size: 16px;
  line-height: 24px;
}

.jobs-time {
  color: #828282;
  font-size: 12px;
  line-height: 24px;
}

.experience-item {
  color: #595959;
  font-size: 14px;
  line-height: 24px;
}
```

## Ожидаемый код

```css
.jobs-title {
  color: #2a2a2a;
  font-size: 22px;
  line-height: 24px;
}

.jobs-occupation {
  color: #2a2a2a;
  font-size: 16px;
  line-height: 24px;
}

.jobs-time {
  color: #828282;
  font-size: 12px;
  line-height: 24px;
}

.experience-item {
  color: #595959;
  font-size: 14px;
  line-height: 24px;
}

.accent {
  color: #ff6b08;
}
```

# 4 - Опыт работы (отступы)

## Термины для теории

## Стартовый код

```html
<section class="jobs">
  <h2 class="jobs-title">Employment history</h2>

  <h3 class="jobs-occupation">
    Front-end developer at <span class="accent">Freelance</span>
  </h3>
  <p class="jobs-time">September 2019 - up to now</p>
  <ul class="experience">
    <li class="experience-item">Lorem ipsum dolor sit amet.</li>
    <li class="experience-item">Quaerat corrupti eum harum eveniet?</li>
    <li class="experience-item">Sit quasi libero facilis ea?</li>
  </ul>
</section>
```

```css
.jobs-title {
  color: #2a2a2a;
  font-size: 22px;
  line-height: 24px;
}

.jobs-occupation {
  color: #2a2a2a;
  font-size: 16px;
  line-height: 24px;
}

.jobs-time {
  color: #828282;
  font-size: 12px;
  line-height: 24px;
}

.experience-item {
  color: #595959;
  font-size: 14px;
  line-height: 24px;
}

.accent {
  color: #ff6b08;
}
```

## Ожидаемый код

```css
.jobs-title {
  color: #2a2a2a;
  font-size: 22px;
  line-height: 24px;

  margin-bottom: 26px;
}

.jobs-occupation {
  color: #2a2a2a;
  font-size: 16px;
  line-height: 24px;

  margin-bottom: 16px;
}

.jobs-time {
  color: #828282;
  font-size: 12px;
  line-height: 24px;

  margin-bottom: 18px;
}

.experience-item {
  color: #595959;
  font-size: 14px;
  line-height: 24px;

  margin-bottom: 10px;
}

.accent {
  color: #ff6b08;
}
```

# 5 - Опыт работы (классы)

Добавьте готовые классы в разметку.

## Термины для теории

## Стартовый код

```html
<section class="jobs">
  <h2 class="jobs-title">Employment history</h2>

  <h3 class="jobs-occupation">
    Front-end developer at <span class="accent">Freelance</span>
  </h3>
  <p class="jobs-time">September 2019 - up to now</p>
  <ul class="experience">
    <li class="experience-item">Lorem ipsum dolor sit amet.</li>
    <li class="experience-item">Quaerat corrupti eum harum eveniet?</li>
    <li class="experience-item">Sit quasi libero facilis ea?</li>
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
```

```css
.jobs-title {
  color: #2a2a2a;
  font-size: 22px;
  line-height: 24px;

  margin-bottom: 26px;
}

.jobs-occupation {
  color: #2a2a2a;
  font-size: 16px;
  line-height: 24px;

  margin-bottom: 16px;
}

.jobs-time {
  color: #828282;
  font-size: 12px;
  line-height: 24px;

  margin-bottom: 18px;
}

.experience-item {
  color: #595959;
  font-size: 14px;
  line-height: 24px;

  margin-bottom: 10px;
}

.accent {
  color: #ff6b08;
}
```

## Ожидаемый код

```html
<section class="jobs">
  <h2 class="jobs-title">Employment history</h2>

  <h3 class="jobs-occupation">
    Front-end developer at <span class="accent">Freelance</span>
  </h3>
  <p class="jobs-time">September 2019 - up to now</p>
  <ul class="experience">
    <li class="experience-item">Lorem ipsum dolor sit amet.</li>
    <li class="experience-item">Quaerat corrupti eum harum eveniet?</li>
    <li class="experience-item">Sit quasi libero facilis ea?</li>
  </ul>

  <h3 class="jobs-occupation">
    Front-end developer at <span class="accent">Freelance</span>
  </h3>
  <p class="jobs-time">September 2019 - up to now</p>
  <ul class="experience">
    <li class="experience-item">Lorem ipsum dolor sit amet.</li>
    <li class="experience-item">Quaerat corrupti eum harum eveniet?</li>
    <li class="experience-item">Sit quasi libero facilis ea?</li>
  </ul>

  <h3 class="jobs-occupation">
    Front-end developer at <span class="accent">Freelance</span>
  </h3>
  <p class="jobs-time">September 2019 - up to now</p>
  <ul class="experience">
    <li class="experience-item">Lorem ipsum dolor sit amet.</li>
    <li class="experience-item">Quaerat corrupti eum harum eveniet?</li>
    <li class="experience-item">Sit quasi libero facilis ea?</li>
  </ul>
</section>
```

# 6 - Опыт работы (финал, отступы)

Добавьте отступы между местами работы.

## Термины для теории

## Стартовый код

```html
<section class="jobs">
  <h2 class="jobs-title">Employment history</h2>

  <h3 class="jobs-occupation">
    Front-end developer at <span class="accent">Freelance</span>
  </h3>
  <p class="jobs-time">September 2019 - up to now</p>
  <ul class="experience">
    <li class="experience-item">Lorem ipsum dolor sit amet.</li>
    <li class="experience-item">Quaerat corrupti eum harum eveniet?</li>
    <li class="experience-item">Sit quasi libero facilis ea?</li>
  </ul>

  <h3 class="jobs-occupation">
    Front-end developer at <span class="accent">Freelance</span>
  </h3>
  <p class="jobs-time">September 2019 - up to now</p>
  <ul class="experience">
    <li class="experience-item">Lorem ipsum dolor sit amet.</li>
    <li class="experience-item">Quaerat corrupti eum harum eveniet?</li>
    <li class="experience-item">Sit quasi libero facilis ea?</li>
  </ul>

  <h3 class="jobs-occupation">
    Front-end developer at <span class="accent">Freelance</span>
  </h3>
  <p class="jobs-time">September 2019 - up to now</p>
  <ul class="experience">
    <li class="experience-item">Lorem ipsum dolor sit amet.</li>
    <li class="experience-item">Quaerat corrupti eum harum eveniet?</li>
    <li class="experience-item">Sit quasi libero facilis ea?</li>
  </ul>
</section>
```

```css
.jobs-title {
  color: #2a2a2a;
  font-size: 22px;
  line-height: 24px;

  margin-bottom: 26px;
}

.jobs-occupation {
  color: #2a2a2a;
  font-size: 16px;
  line-height: 24px;

  margin-bottom: 16px;
}

.jobs-time {
  color: #828282;
  font-size: 12px;
  line-height: 24px;

  margin-bottom: 18px;
}

.experience-item {
  color: #595959;
  font-size: 14px;
  line-height: 24px;

  margin-bottom: 10px;
}

.accent {
  color: #ff6b08;
}
```

## Ожидаемый код

```css
.jobs-title {
  color: #2a2a2a;
  font-size: 22px;
  line-height: 24px;

  margin-bottom: 26px;
}

.jobs-occupation {
  color: #2a2a2a;
  font-size: 16px;
  line-height: 24px;

  margin-bottom: 16px;
}

.jobs-time {
  color: #828282;
  font-size: 12px;
  line-height: 24px;

  margin-bottom: 18px;
}

.experience-item {
  color: #595959;
  font-size: 14px;
  line-height: 24px;

  margin-bottom: 10px;
}

.accent {
  color: #ff6b08;
}

.experience {
  margin-bottom: 28px;
}
```
