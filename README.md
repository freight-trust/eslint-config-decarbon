# eslint-config-decarbon

> ESLint configuration for Decarbon

## Getting started

To install `eslint-config-carbon` in your project, you will need to run the
following command using [npm](https://www.npmjs.com/):

```bash
npm install -S eslint-config-decarbon
```

If you prefer [Yarn](https://yarnpkg.com/en/), use the following command
instead:

```bash
yarn add eslint-config-decarbon
```

## Usage

You can use `eslint-config-carbon` in your project by extending it in your
`eslint` configuration. For example, if we had an `.eslintrc` file:

```json
{
  "extends": ["decarbon"]
}
```

The default configuration available under `eslint-config-carbon` includes all
ESLint configuration and plugins, including plugins for React.js development. If
you'd like to not include these rules in your setup, you can also include a
`base` or `vanilla` oriented configuration by doing the following:

```json
{
  "extends": ["eslint-config-decarbon/base"]
}
```

## 🙌 Contributing

We're always looking for contributors to help us fix bugs, build new features,
or help us improve the project documentation. If you're interested, definitely
check out our [Contributing Guide](/.github/CONTRIBUTING.md)! 👀

## 📝 License

Licensed under the [Apache 2.0 License](/LICENSE).
