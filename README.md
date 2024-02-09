# Astrofy | Modelo de site de portfólio pessoal

# # Astrofy | Modelo de site de portfólio pessoal usando Astro e TailwindCSS

Astrofy é um modelo gratuito e de código aberto para o seu site de portfólio pessoal criado com Astro e TailwindCSS. Com Página incicial, Seção de Projetos, e CV.
Site original: [Astrofy Template ⚡️](https://astrofy-template.netlify.app/)

Compatível com todos os dispositivos móveis e com uma interface de usuário bonita e agradável.
Curriculo online.
Projetos pessoais e profissionais.
Links externos para todas as minhas redes sociais.

💙 Creditos para. [Manuel Ernesto](https://manuelernestog.github.io/)

![Astrofy | Personal Porfolio Website Template](public/social_img.webp)

## Tech Stack

- [Astro](https://astro.build)
- [tailwindcss](https://tailwindcss.com/)
- [DaisyUI](https://daisyui.com/)

## Project Structure

```php
├── src/
│   ├── components/
│   │   ├── cv/
│   │   │   ├── TimeLine
│   │   ├── BaseHead.astro
│   │   ├── Card.astro
│   │   ├── Footer.astro
│   │   ├── Header.astro
│   │   └── HorizontalCard.astro
│   │   └── SideBar.astro
│   │   └── SideBarMenu.astro
│   │   └── SideBarFooter.astro
│   ├── content/
│   │   ├── blog/
│   │   │   ├── post1.md
│   │   │   ├── post2.md
│   │   │   └── post3.md
│   │   ├── store/
│   │   │   ├── item1.md
│   │   │   ├── item2.md
│   ├── layouts/
│   │   └── BaseLayout.astro
│   │   └── PostLayout.astro
│   └── pages/
│   │   ├── blog/
│   │   │   ├── [...page].astro
│   │   │   ├── [slug].astro
│   │   └── cv.astro
│   │   └── index.astro
│   │   └── projects.astro
│   │   └── rss.xml.js
│   ├── styles/
│   │   └── global.css
│   └── config.ts
├── public/
│   ├── favicon.svg
│   └── profile.webp
│   └── social_img.webp
├── astro.config.mjs
├── tailwind.config.cjs
├── package.json
└── tsconfig.json
```

## License

Astrofy is licensed under the MIT license — see the [LICENSE](https://github.com/manuelernestog/astrofy/blob/main/LICENSE) file for details.

## Contributors

<a href="https://github.com/manuelernestog/astrofy/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=manuelernestog/astrofy" />
</a>

Made with [contrib.rocks](https://contrib.rocks).
