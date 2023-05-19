# 🪄 Nyxb Starter Templates

Quickly get started with a minimal Nyxb starter template!

## ⏱️ Quick start

Head over to [nyxb.new](https://nyxb.new) to get started quickly.

## 📖 Usage

You can use [`nyxbi`](https://github.com/nyxblabs/nyxbi) CLI to clone latest template to an empty directory:

```sh-session
$ npx nyxbi init [-t,--template=<template>] [<dir>]
```

**Example:** Clone `monorepo` to `my-app` directory:

```sh-session
$ npx nyxbi init -t monorepo my-app
```

## 📄 Templates

| Name                                                          | Description                                                           | Local                               | Online                                                                                                                        |
| ------------------------------------------------------------- | --------------------------------------------------------------------- | ----------------------------------- | ----------------------------------------------------------------------------------------------------------------------------- |
| [monorepo](https://github.com/nyxblabs/starter/tree/monorepo) | [Turborepo](https://turbo.build/repo/docs/getting-started/create-new) | `npx nyxbi init -t monorepo my-app` | [Stackblitz](https://stackblitz.com/edit/github-apsffz?file=README.md) / [CodeSandbox](https://codesandbox.io/s/y5ed3)        |
| [Nextjs](https://github.com/nuxt/starter/tree/nextjs)         | Latest [Nextjs](https://nextjs.org/)                                  | `npx nyxbi init -t nextjs`          | [Stackblitz](https://stackblitz.com/edit/nextjs-gmrwz1?file=README.md) / [CodeSandbox](https://codesandbox.io/s/nextjs-5tlgz) |

## Contribution

Each template is maintained in a branch (see [all branches](https://github.com/nyxblabs/starter/branches)).
For improvements, please open a Pull Request to each individual branch.

**Note:** Please avoid commiting lock-files such as `pnpm-lock.yaml` `yarn.lock` and `package-lock.json` to template branches!

## License

[MIT](./LICENSE) - Made with 💙
