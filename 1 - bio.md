# 1 - Биография (размер шрифта)

## Термины для теории

- px
- font-size

## Стартовый код

```html
<section class="bio">
  <h1 class="bio-title">Anton Chornyi</h1>
  <p class="bio-occupation">Front-end developer</p>
  <p class="bio-about">
    Lorem ipsum dolor sit amet consectetur adipisicing elit. Amet odio adipisci
    illo, earum atque quae, sequi magni consectetur sit perferendis sunt laborum
    ipsum quas. A incidunt temporibus aut harum ad.
  </p>
</section>
```

```css
.bio-title {
}

.bio-occupation {
}

.bio-about {
}
```

## Ожидаемый код

```css
.bio-title {
  font-size: 45px;
}

.bio-occupation {
  font-size: 14px;
}

.bio-about {
  font-size: 14px;
}
```

# 2 - Биография (line height)

## Термины для теории

- высота линии
- картинку
- показывать ли перевод в множитель или давать px??

## Стартовый код

```html
<section class="bio">
  <h1 class="bio-title">Anton Chornyi</h1>
  <p class="bio-occupation">Front-end developer</p>
  <p class="bio-about">
    Lorem ipsum dolor sit amet consectetur adipisicing elit. Amet odio adipisci
    illo, earum atque quae, sequi magni consectetur sit perferendis sunt laborum
    ipsum quas. A incidunt temporibus aut harum ad.
  </p>
</section>
```

```css
.bio-title {
  font-size: 45px;
}

.bio-occupation {
  font-size: 14px;
}

.bio-about {
  font-size: 14px;
}
```

## Ожидаемый код

```css
.bio-title {
  font-size: 45px;
  line-height: 89px;
}

.bio-occupation {
  font-size: 14px;
  line-height: 24px;
}

.bio-about {
  font-size: 14px;
  line-height: 24px;
}
```

# 3 - Биография (цвет)

## Термины для теории

- hex

## Стартовый код

```html
<section class="bio">
  <h1 class="bio-title">Anton Chornyi</h1>
  <p class="bio-occupation">Front-end developer</p>
  <p class="bio-about">
    Lorem ipsum dolor sit amet consectetur adipisicing elit. Amet odio adipisci
    illo, earum atque quae, sequi magni consectetur sit perferendis sunt laborum
    ipsum quas. A incidunt temporibus aut harum ad.
  </p>
</section>
```

```css
.bio-title {
  font-size: 45px;
  line-height: 89px;
}

.bio-occupation {
  font-size: 14px;
  line-height: 24px;
}

.bio-about {
  font-size: 14px;
  line-height: 24px;
}
```

## Ожидаемый код

```css
.bio-title {
  color: #2a2a2a;
  font-size: 45px;
  line-height: 89px;
}

.bio-occupation {
  color: #2a2a2a;
  font-size: 14px;
  line-height: 24px;
}

.bio-about {
  color: #595959;
  font-size: 14px;
  line-height: 24px;
}
```

# 4 - Биография (оптимизация кода)

## Термины для теории

- группировка селекторов

## Стартовый код

```html
<section class="bio">
  <h1 class="bio-title">Anton Chornyi</h1>
  <p class="bio-occupation">Front-end developer</p>
  <p class="bio-about">
    Lorem ipsum dolor sit amet consectetur adipisicing elit. Amet odio adipisci
    illo, earum atque quae, sequi magni consectetur sit perferendis sunt laborum
    ipsum quas. A incidunt temporibus aut harum ad.
  </p>
</section>
```

```css
.bio-title {
  color: #2a2a2a;
  font-size: 45px;
  line-height: 89px;
}

.bio-occupation {
  color: #2a2a2a;
  font-size: 14px;
  line-height: 24px;
}

.bio-about {
  color: #595959;
  font-size: 14px;
  line-height: 24px;
}
```

## Ожидаемый код

```css
.bio-title {
  font-size: 45px;
  line-height: 89px;
}

.bio-title,
.bio-occupation {
  color: #2a2a2a;
}

.bio-occupation,
.bio-about {
  font-size: 14px;
  line-height: 24px;
}

.bio-about {
  color: #595959;
}
```

# 5 - Биография (отступы)

## Термины для теории

- margin

## Стартовый код

```html
<section class="bio">
  <h1 class="bio-title">Anton Chornyi</h1>
  <p class="bio-occupation">Front-end developer</p>
  <p class="bio-about">
    Lorem ipsum dolor sit amet consectetur adipisicing elit. Amet odio adipisci
    illo, earum atque quae, sequi magni consectetur sit perferendis sunt laborum
    ipsum quas. A incidunt temporibus aut harum ad.
  </p>
</section>
```

```css
.bio-title {
  font-size: 45px;
  line-height: 89px;
}

.bio-title,
.bio-occupation {
  color: #2a2a2a;
}

.bio-occupation,
.bio-about {
  font-size: 14px;
  line-height: 24px;
}

.bio-about {
  color: #595959;
}
```

## Ожидаемый код

```css
.bio-title {
  margin-bottom: 20px;
  font-size: 45px;
  line-height: 89px;
}

.bio-title,
.bio-occupation {
  color: #2a2a2a;
}

.bio-occupation {
  margin-bottom: 27px;
}

.bio-occupation,
.bio-about {
  font-size: 14px;
  line-height: 24px;
}

.bio-about {
  color: #595959;
}
```
