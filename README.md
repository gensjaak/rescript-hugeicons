# ReScript binding to [Hugeicons](https://hugeicons.com/)

Use Hugeicons ([supported icons list](./ICONS.md)) as ReScript-React Components, thanks to these bindings.

```OCaml
@jsx.component
let make = () => {
  <div>
    <Hugeicons.Search01Icon size=24 />
    <Hugeicons.ChampionIcon size=24 color="#FFF" />
  </div>
}
```

## Demo

Please visit the following link to check out the demo.
[ReScript-Hugeicons Demo](https://rescript-Hugeicons-demo.vercel.app)

## Installation

```bash
yarn add rescript-hugeicons

or

npm install rescript-hugeicons

or

bun add rescript-hugeicons
```

And in rescript.json, add `"rescript-hugeicons"` to `bs-dependencies`

```json
"bs-dependencies": ["rescript-hugeicons"]
```

The binding has the following dependencies, and they have to be installed.

- [@rescript/core](https://www.npmjs.com/package/@rescript/core)
- [hugeicons-react](https://www.npmjs.com/package/hugeicons-react?activeTab=dependencies)
- [rescript](https://www.npmjs.com/package/rescript)

## Author

Jean-Jacques Akakpo (gensjaak)

- LinkedIn: [Jean-Jacques Akakpo](https://www.linkedin.com/in/jeanjacques-akakpo/)
- Twitter: [@gensjaak](https://x.com/gensjaak)

### License

MIT
