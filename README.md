# create-app-cli

## Scaffolding Your First webapp Project

> **Compatibility Note:**
> Vite requires [Node.js](https://nodejs.org/en/) version 14.18+, 16+. However, some templates require a higher Node.js version to work, please upgrade if your package manager warns about it.

With PNPM:

```bash
$ pnpx create-app-cli@latest
```

Then follow the prompts!

You can also directly specify the project name and the template you want to use via additional command line options. For example, to scaffold a Vite + React project, run:

```bash
# pnpm
pnpx create-app-cli@latest my-react-app --template react-ts
```

Currently supported template presets include:

- `react-ts` [点此去](https://github.com/kunlun-qilian/create-app-cli/tree/master/template-react-ts)
- `vue-ts` [点此去](https://github.com/kunlun-qilian/create-app-cli/tree/master/template-vue-ts)