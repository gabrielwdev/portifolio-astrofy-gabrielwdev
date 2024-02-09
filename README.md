# Astrofy | Modelo de site de portfólio pessoal

## Astrofy | Modelo de site de portfólio pessoal usando Astro e TailwindCSS

Astrofy é um modelo gratuito e de código aberto para o seu site de portfólio pessoal criado com Astro e TailwindCSS. Com Página incicial, Seção de Projetos, e CV. <br>
Site original: [Astrofy Template ⚡️](https://astrofy-template.netlify.app/)

Compatível com todos os dispositivos móveis e com uma interface de usuário bonita e agradável. <br>
Curriculo online. <br>
Projetos pessoais e profissionais. <br>
Links externos para todas as minhas redes sociais. <br>

💙 Creditos para. [Manuel Ernesto](https://manuelernestog.github.io/)

<img src="./public/readme-img.png" style="width: 50%; heigth: 50%;"/>

## Tecnologias

- [Astro](https://astro.build)
- [tailwindcss](https://tailwindcss.com/)
- [DaisyUI](https://daisyui.com/)

## Estrutura do projeto

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

## Licença

Astrofy é licenciado sob a licença MIT - veja o [LICENSE](https://github.com/manuelernestog/astrofy/blob/main/LICENSE) arquivo para detalhes.

## Contribuições

<a href="https://github.com/manuelernestog/astrofy/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=manuelernestog/astrofy" />
</a>

Made with [contrib.rocks](https://contrib.rocks).
