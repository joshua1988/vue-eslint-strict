# Vue ESLint Strict Rules

[![npm (scoped with tag)](https://flat.badgen.net/npm/v/@marvue/eslint-config-vue-strict)](https://npmjs.com/package/@marvue/eslint-config-vue-strict)
[![npm](https://flat.badgen.net/npm/dt/@marvue/eslint-config-vue-strict)](https://npmjs.com/package/@marvue/eslint-config-vue-strict)

## Usage

Would you like to make your vue code tight? Follow this guideline.

1. Create a vue project with Vue CLI (^3.x)

```bash
$ vue create <my-vue>
```

2. Select these following project options in order

- Please pick a preset: Manually select features
- Check the features needed for your project: Babel, Linter / Formatter
- Pick a linter / formatter config: ESLint + Prettier
- Pick additional lint features: Lint on Save
- Where do you prefer placing config for Babel, ESLint, etc.?: In dedicated config files
- Save this as a preset for future projects? n

3. install the npm package

```
$ npm i -D @nuxtjs/eslint-config
```

4. change the eslint config file `.eslintrc`

```js
{
  extends: [
    '@marvue/vue-strict',
  ]
}
```

## License

MIT - CaptainPangyo
