# create-ihccc

## Scaffolding Your Admin Project

> **Compatibility Note:**
> ihccc requires [Node.js](https://nodejs.org/en/) version 18+, 20+. However, some templates require a higher Node.js version to work, please upgrade if your package manager warns about it.

With NPM:

```bash
$ npm create ihccc@latest
```

With Yarn:

```bash
$ yarn create ihccc
```

With PNPM:

```bash
$ pnpm create ihccc
```

Then follow the prompts!

You can also directly specify the project name and the template you want to use via additional command line options. For example, to scaffold a ihccc + Admin project, run:

```bash
# npm 7+, extra double-dash is needed:
npm create ihccc@latest my-app --template ihccc-admin

# yarn
yarn create ihccc my-app --template ihccc-admin

# pnpm
pnpm create ihccc my-app --template ihccc-admin
```

Currently supported template presets include:

- `ihccc-admin`

You can use `.` for the project name to scaffold in the current directory.
