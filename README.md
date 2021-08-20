# ESlint + Prettier + Airbnb Style Guide Configuration

## Usage
In case there's no ```package.json``` in your project directory
```bash
npm init -y
```
### Install dependencies:
```bash
npm i -D eslint prettier eslint-plugin-prettier eslint-config-prettier eslint-plugin-node eslint-config-node @babel/eslint-parser
```

```bash
npx install-peerdeps --dev eslint-config-airbnb-base
```

### OR run it as a 1-liner
```bash
npm i -D eslint prettier eslint-plugin-prettier eslint-config-prettier eslint-plugin-node eslint-config-node @babel/eslint-parser && npx install-peerdeps --dev eslint-config-airbnb-base
```

Then, copy ```.prettierrc``` and ```.eslintrc``` to your project root directory.
