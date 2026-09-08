# ts-toolkit-cli

Learning TypeScript by building tiny CLIs

## Highlights

- Strict tsconfig, no any
- npm link friendly
- commander-based subcommands
- Ships as an ESM binary

## Examples

```bash
npx . convert data.csv -d ';'
# or after npm link: cliparse convert data.csv
```

## Install

```bash
npm install
npm run build
```

## Project structure

```text
├── .github/
│   └── workflows/
│       └── ci.yml
├── docs/
│   ├── faq.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── src/
│   └── index.ts
├── .gitignore
├── CHANGELOG.md
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── SECURITY.md
├── package.json
└── tsconfig.json
```

## Development

```bash
npm install
```
