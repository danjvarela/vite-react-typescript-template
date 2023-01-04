# Vite React Typescript Template
A template for creating typescript-react apps using [vite]( https://vitejs.dev/ ).

## Installation
### Using degit
```
degit danjvarela/vite-react-typescript-template
```
### Manual
```
git clone https://github.com/danjvarela/vite-react-typescript-template.git
git remote rm origin
```

## Features
* [X] Built-in eslint config using the [Airbnb style guide](https://github.com/airbnb/javascript) and support for typescript.
* [X] Built-in Prettier config.
* [X] Use `@/` as an alias to the `src` directory.

## Scripts
Supports all scripts vite creates by default with the addition of the following:
```
# lint files
npm run lint
```

```
# lint and fix correctable errors
npm run lint:fix
```

```
# format files using prettier
npm run format
```
