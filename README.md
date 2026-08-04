<!-- Snake repo README -->

<h1 align="center">Snake · GitHub Contributions Animation</h1>

<p align="center">
  <b>Contribution graph animation for the GitHub profile of odin337</b>
</p>

<p align="center">
  <a href="https://github.com/odin337">
    <img src="https://komarev.com/ghpvc/?username=odin337&style=for-the-badge&color=0f172a" alt="Profile views" />
  </a>
  <a href="https://github.com/odin337/Snake/stargazers">
    <img src="https://img.shields.io/github/stars/odin337/Snake?style=for-the-badge&color=111827" alt="Repo stars" />
  </a>
  <a href="https://github.com/odin337/Snake/network/members">
    <img src="https://img.shields.io/github/forks/odin337/Snake?style=for-the-badge&color=111827" alt="Repo forks" />
  </a>
</p>

---

## Что это

Этот репозиторий генерирует анимированную змейку, которая «ест» вкладки GitHub contributions.  
Анимация автоматически обновляется через GitHub Actions и публикуется в ветку `output`.

Основа — `Platane/snk`, популярный GitHub Action для генерации SVG/GIF из contribution graph. [11][26]

---

## Как это работает

1. Workflow запускается по расписанию или вручную.
2. Action читает contribution graph пользователя `odin337`.
3. Генерируются SVG и GIF.
4. Файлы публикуются в `output`.
5. README профиля забирает эти файлы и показывает их на главной странице профиля.

---

## Демо

<p align="center">
  <picture>
    <source
      media="(prefers-color-scheme: dark)"
      srcset="https://raw.githubusercontent.com/odin337/Snake/output/github-snake-dark.svg"
    />
    <source
      media="(prefers-color-scheme: light)"
      srcset="https://raw.githubusercontent.com/odin337/Snake/output/github-snake.svg"
    />
    <img
      alt="GitHub Snake Animation"
      src="https://raw.githubusercontent.com/odin337/Snake/output/github-snake.svg"
    />
  </picture>
</p>

---

## Дополнительно

- Light/dark mode support.
- Auto-update via GitHub Actions.
- GIF export option.
- Можно использовать как основу для своего профиля.

---

## Credits

- [Platane/snk](https://github.com/Platane/snk)
- GitHub Actions
