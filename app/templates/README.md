# <%= reactComponent %> 

<%= description %>


## Usage

```bash
yarn add <%= reactComponent %>
# or 
npm install <%= reactComponent %>
```

For more details, see [`src/js/components/<%= component %>.js`](./src/js/components/<%= component %>.js)


## Code Architecture

Check out the [`generator-poi@<%= generatorVersion %>`
docs](https://github.com/willmendesneto/generator-poi/tree/v<%= generatorVersion %>#code-architecture)
for info on the repo layout, structure and meaning.


## Publishing the package

This project is using `np` as publisher helper. For more information, please check [`np` documentation](https://github.com/sindresorhus/np#readme)


## NPM Commands

### Component commands

- `npm run start`:  start component page example using [`react-storybook`](https://github.com/storybooks/storybook);
- `npm run watch`:  start component page in watch mode example using [`react-storybook`](https://github.com/storybooks/storybook),
- `npm run demo:deploy`: Publishing your component page in your Github Page
- `npm run build:page`: Creates your page bundle;
- `npm run build:library`: Creates your component bundle to be published in your NPM repository (public or private). This bundle will NOT include [`react-storybook`](https://github.com/storybooks/storybook) and other development dependencies;
- `npm run serve:dist`: Creates a server based on the component page that will be deployed in your Github Page. This command is used to check the results locally before you deploy your component example page;
- `npm run test`: Running unit tests using MochaJS
- `npm run tdd`: Running unit tests using MochaJS in watch mode. It will help you to create a component using [`Test Driven Development` approach](https://en.wikipedia.org/wiki/Test-driven_development)


## Changes and history

See [CHANGELOG.md](./CHANGELOG.md).
