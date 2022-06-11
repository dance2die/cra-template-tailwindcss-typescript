# cra-template-tailwindcss-typescript

<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->

[![All Contributors](https://img.shields.io/badge/all_contributors-8-orange.svg?style=flat-square)](#contributors-)

<!-- ALL-CONTRIBUTORS-BADGE:END -->

A streamlined [Tailwind CSS v3.x](https://tailwindcss.com) template for [Create React App](https://github.com/facebook/create-react-app) in [TypeScript](https://www.typescriptlang.org/).

## Usage

```bash
npx create-react-app my-app --template tailwindcss-typescript
```

### Note to self

_This is for myself or others trying to create from source code._

Prepare the husky, pre-github hook

```bash
npm run prepare
```

Install `git-cz` globally

```
pnpm i -g git-cz
# or
npm i -g git-cz
```

Create a new create-react-app project from my source code

```bash
npx create-react-app tw3 --template file:/home/dance2die/src/github/dance2die/cra-template-tailwindcss-typescript
```

If you didn't run `npm run prepare` from the source code, you will get an error like this,

```
sh: husky: command not found
npm ERR! code 127
npm ERR! path /Users/X/Desktop/Workspace/project
npm ERR! command failed
npm ERR! command sh -c husky install
```

## Credits

This project was made possible thanks to the following projects.

1. [GeoffSelby/cra-template-tailwindcss](https://github.com/GeoffSelby/cra-template-tailwindcss) - A streamlined Tailwind CSS template for Create React App (in JavaScript).
2. [cra-template-typescript](https://github.com/facebook/create-react-app/tree/master/packages/cra-template-typescript) - An official TypeScript template for create-react-app.

## License

MIT © [Sung M. Kim](https://sung.codes)

## Contributors ✨

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <td align="center"><a href="https://www.jagdcake.com/"><img src="https://avatars3.githubusercontent.com/u/28141754?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Ivo Angelov</b></sub></a><br /><a href="https://github.com/dance2die/cra-template-tailwindcss-typescript/commits?author=JagdCake" title="Code">💻</a> <a href="#maintenance-JagdCake" title="Maintenance">🚧</a></td>
    <td align="center"><a href="https://github.com/rogerchi"><img src="https://avatars1.githubusercontent.com/u/625496?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Roger Chi</b></sub></a><br /><a href="https://github.com/dance2die/cra-template-tailwindcss-typescript/issues?q=author%3Arogerchi" title="Bug reports">🐛</a> <a href="https://github.com/dance2die/cra-template-tailwindcss-typescript/commits?author=rogerchi" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/jagreehal"><img src="https://avatars1.githubusercontent.com/u/3634906?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Jag Reehal</b></sub></a><br /><a href="https://github.com/dance2die/cra-template-tailwindcss-typescript/commits?author=jagreehal" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/michaeldlfx"><img src="https://avatars3.githubusercontent.com/u/24497482?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Michael</b></sub></a><br /><a href="https://github.com/dance2die/cra-template-tailwindcss-typescript/issues?q=author%3Amichaeldlfx" title="Bug reports">🐛</a></td>
    <td align="center"><a href="https://github.com/panalgin"><img src="https://avatars.githubusercontent.com/u/12881878?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Mustafa YILDIZ</b></sub></a><br /><a href="https://github.com/dance2die/cra-template-tailwindcss-typescript/commits?author=panalgin" title="Tests">⚠️</a> <a href="#projectManagement-panalgin" title="Project Management">📆</a> <a href="https://github.com/dance2die/cra-template-tailwindcss-typescript/issues?q=author%3Apanalgin" title="Bug reports">🐛</a></td>
    <td align="center"><a href="https://www.aryeeidelman.com/"><img src="https://avatars.githubusercontent.com/u/7709411?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Arye Eidelman</b></sub></a><br /><a href="https://github.com/dance2die/cra-template-tailwindcss-typescript/commits?author=arye-eidelman" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/ptaberg"><img src="https://avatars.githubusercontent.com/u/34740585?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Kolja P.</b></sub></a><br /><a href="https://github.com/dance2die/cra-template-tailwindcss-typescript/commits?author=ptaberg" title="Code">💻</a></td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/SaminYaser-work"><img src="https://avatars.githubusercontent.com/u/40205522?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Samin Yaser</b></sub></a><br /><a href="https://github.com/dance2die/cra-template-tailwindcss-typescript/commits?author=SaminYaser-work" title="Code">💻</a></td>
  </tr>
</table>

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!
