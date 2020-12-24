# ESLint configuration for typescript

### Installation

#### npm 6

```bash
npm i @chernodub/eslint-config@latest \
      @typescript-eslint/eslint-plugin@4.11.0 \
      @typescript-eslint/parser@4.11.0 \
      eslint@7.16.0 eslint-plugin-import@2.22.1 \
      eslint-plugin-jsdoc@30.7.9 typescript@4.1.3 -D
```

#### npm 7

`TODO` when node 16 appears, npm 7 introduced automated installation of peer dependencies

### Usage
Then, create the `.eslintrc.json` in the directory of `package.json` and paste there the following

```json
{
  "extends": "@chernodub/eslint-config"
}
```
