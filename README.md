
<p align="center">
  Construção de um monorepo baseado em Design System e documentação storybook 🚀
  <br>
  <br>

  <img alt="Language count" src="https://img.shields.io/github/repo-size/alvarobraz/storybook-design-system"/>

  <a href="https://rocketseat.com.br">
    <img alt="Made by Rocketseat" src="https://img.shields.io/badge/made%20by-Rocketseat-%237519C1">
  </a>

  <a href="https://www.linkedin.com/in/alvarobraz/">
    <img alt="Made by alvarobraz" src="https://img.shields.io/badge/made%20by-alvarobraz-%237519C1">
  </a>

  <a href="https://github.com/alvarobraz/storybook-design-system/commits/main">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/alvarobraz/storybook-design-system">
  </a>

  <img alt="License" src="https://img.shields.io/github/license/alvarobraz/storybook-design-system">
</p>

---

<p align="center">
  <a href="#dart-sobre">Sobre</a> &#xa0; | &#xa0; 
  <a href="#rocket-tecnologias">Tecnologias</a> &#xa0; | &#xa0;
  <a href="#estrutura">Estrurura</a> &#xa0; | &#xa0;
  <a href="#white_check_mark-requerimentos">Requerimentos</a> &#xa0; | &#xa0;
  <a href="#checkered_flag-começando">Começando</a>
</p>

<br>

## :dart: Sobre ##

Aplicação em ReactJs/TypeScript de um monorepo baseado em Design System documentado em um Storyboard!<br/>Nesta aplicação foi criado repositoŕios de tokens,  doscs de storybook e componentes em react, está aplicação serve de base para usar em outros projetos.


## :rocket: Tecnologias ##

As seguintes tecnologias foram utilizadas no projeto:

- [React.js](https://pt-br.legacy.reactjs.org/)
- [TypeScript](https://www.typescriptlang.org/)
- [Turborepo](https://www.npmjs.com/package/turbo)
- [Storybook](https://storybook.js.org/)
- [Radix](https://www.radix-ui.com/)
- [stitches/react](https://www.npmjs.com/package/@stitches/react)
- [Eslint](https://eslint.org/)
- [Babel](https://babeljs.io/)


## Estrutura ##
```
.
├── LICENSE
├── package.json
├── package-lock.json
├── packages
│   ├── docs
│   │   ├── package.json
│   │   ├── src
│   │   │   ├── components
│   │   │   │   ├── ColorsGrid.tsx
│   │   │   │   └── TokensGrid.tsx
│   │   │   ├── pages
│   │   │   │   ├── home.stories.mdx
│   │   │   │   └── tokens
│   │   │   │       ├── colors.stories.mdx
│   │   │   │       ├── font-sizes.stories.mdx
│   │   │   │       ├── fonts.stories.mdx
│   │   │   │       ├── font-weights.stories.mdx
│   │   │   │       ├── line-height.stories.mdx
│   │   │   │       ├── radii.stories.mdx
│   │   │   │       └── space.stories.mdx
│   │   │   ├── stories
│   │   │   │   ├── Avatar.stories.tsx
│   │   │   │   ├── Box.stories.tsx
│   │   │   │   ├── Button.stories.tsx
│   │   │   │   ├── Checkbox.stories.tsx
│   │   │   │   ├── Heading.stories.tsx
│   │   │   │   ├── MultiStep.stories.tsx
│   │   │   │   ├── TextArea.stories.tsx
│   │   │   │   ├── TextInput.stories.tsx
│   │   │   │   └── Text.stories.tsx
│   │   │   └── styles
│   │   │       └── tokens-grid.css
│   │   ├── tsconfig.json
│   │   └── vite.config.js
│   ├── eslint-config
│   │   ├── index.js
│   │   ├── package.json
│   │   ├── package-lock.json
│   │   └── yarn-error.log
│   ├── react
│   │   ├── CHANGELOG.md
│   │   ├── dist
│   │   │   ├── index.d.ts
│   │   │   ├── index.js
│   │   │   └── index.mjs
│   │   ├── package.json
│   │   ├── src
│   │   │   ├── components
│   │   │   │   ├── Avatar
│   │   │   │   │   ├── index.tsx
│   │   │   │   │   └── styles.ts
│   │   │   │   ├── Box.tsx
│   │   │   │   ├── Button.tsx
│   │   │   │   ├── Checkbox
│   │   │   │   │   ├── index.tsx
│   │   │   │   │   └── styles.ts
│   │   │   │   ├── Heading.tsx
│   │   │   │   ├── MultiStep
│   │   │   │   │   ├── index.tsx
│   │   │   │   │   └── styles.ts
│   │   │   │   ├── TextArea.tsx
│   │   │   │   ├── TextInput
│   │   │   │   │   ├── index.tsx
│   │   │   │   │   └── styles.ts
│   │   │   │   └── Text.tsx
│   │   │   ├── index.tsx
│   │   │   └── styles
│   │   │       └── index.ts
│   │   ├── tsconfig.json
│   │   └── yarn-error.log
│   ├── tokens
│   │   ├── dist
│   │   │   ├── index.d.ts
│   │   │   ├── index.js
│   │   │   └── index.mjs
│   │   ├── package.json
│   │   ├── src
│   │   │   ├── colors.ts
│   │   │   ├── font-sizes.ts
│   │   │   ├── fonts.ts
│   │   │   ├── font-weights.ts
│   │   │   ├── index.ts
│   │   │   ├── line-heights.ts
│   │   │   ├── radii.ts
│   │   │   └── space.ts
│   │   ├── tsconfig.json
│   │   └── yarn-error.log
│   └── ts-config
│       ├── base.json
│       ├── package.json
│       ├── react.json
│       └── yarn-error.log
├── README.md
├── turbo.json
└── yarn.lock


```

## :white_check_mark: Requerimentos ##

- [Node](https://nodejs.org/en/)
- [Yarn](https://yarnpkg.com/lang/en/)

## :checkered_flag: Começando ##

```bash
# Clone this project
$ git clone https://github.com/alvarobraz/storybook-design-system

# Access
$ cd storybook-design-system

# Install dependencies
$ yarn install

# Run the project
$ yarn dev

# The server will initialize in the <http://localhost:3000>
```
