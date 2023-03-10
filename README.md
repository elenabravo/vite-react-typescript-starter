<p align="center">
  <a href="https://github.com/elenabravo/vite-react-typescript-starter" rel="noopener" target="_blank"><img width="60" src="https://github.githubassets.com/images/icons/emoji/electron.png" alt="electron icon"></a>
</p>

<h1 align="center">Vite React TypeScript Starter</h1>
<br>

Vite React and TypeScript starter built on top of a custom component library inspired by [Chakra UI](https://github.com/chakra-ui/chakra-ui), [Material UI](https://github.com/mui/material-ui) and [Primer React](https://github.com/primer/react).
This starter comes with a fully customizable react component library and it is structured following the [atomic design principles](https://andela.com/insights/structuring-your-react-application-atomic-design-principles/). The library contains a set pre-configured react primitive components, such as `Flex` and `Box`, which can be easily styled by passing props, as also seen in Chakra UI, Materiasl UI and Primer React.

---

## Features

- [Vite](https://vitejs.dev/)
- [React](https://reactjs.org/)
- [TypeScript](https://www.typescriptlang.org/)
- [Stitches](https://stitches.dev/)
- [Prettier](https://prettier.io/)
- [ESLint](https://eslint.org/) with:
  - [Airbnb config](https://github.com/airbnb/javascript)
  - [TypeScript](https://www.npmjs.com/package/@typescript-eslint/eslint-plugin)
  - [Jest-dom](https://github.com/testing-library/eslint-plugin-jest-dom)
  - [Prettier](https://github.com/prettier/eslint-config-prettier)
  - And a few other ES2015+ related rules
- [Jest](https://jestjs.io) with [DOM Testing Library](https://testing-library.com/docs/dom-testing-library/)
- [React Testing Library](https://testing-library.com/docs/react-testing-library/)
- [GitHub Action workflows](https://github.com/features/actions) set up to run tests and linting on push

---

## Running the app

```
# install dependencies
npm install

# run in dev mode on port 3000
npm run start

# generate production build
npm run build
```

## Testing

### Jest with React Testing Library

```
npm run test
```

## Linting

```
# run linter
npm run lint

# fix lint issues
npm run lint:fix
```

## Formatting

```
# run prettier
npm run format
```
