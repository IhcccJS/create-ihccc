# create-ihccc <a href="https://npmjs.com/package/create-ihccc"><img src="https://img.shields.io/npm/v/create-ihccc" alt="npm package"></a>

## Scaffolding Your First ihccc Project

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

With Bun:

```bash
$ bun create ihccc
```

Then follow the prompts!

You can also directly specify the project name and the template you want to use via additional command line options. For example, to scaffold a ihccc + Admin project, run:

```bash
# npm 7+, extra double-dash is needed:
npm create ihccc@latest my-app -- --template admin

# yarn
yarn create ihccc my-vue-app --template admin

# pnpm
pnpm create ihccc my-vue-app --template admin

# Bun
bun create ihccc my-vue-app --template admin
```

Currently supported template presets include:

- `admin`

You can use `.` for the project name to scaffold in the current directory.
