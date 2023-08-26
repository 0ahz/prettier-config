# @0ahz/prettier-config

> My personal [Prettier](https://prettier.io/) config.

## Install

```bash
pnpm i @0ahz/prettier-config -D
# or npm
# or yarn
```

## Usage

In `package.json`:

```json
{
  "prettier": "@0ahz/prettier-config"
}
```

or `.prettierrc`:

```json
"@0ahz/prettier-config"
```

or `.prettierrc.js`:

```js
module.exports = {
  ...require("@wfkit/prettier-config"),
  // other override
};
```

## License

MIT License - [0ahz](https://github.com/0ahz)
