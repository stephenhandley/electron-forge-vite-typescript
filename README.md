# Electron + Forge + Vite (+ React)
Get code generated from the base [Electron Forge Vite template](https://github.com/electron/forge/tree/main/packages/template/vite) to work with Typescript ([branch](https://github.com/stephenhandley/electron-forge-vite-typescript/tree/typescript)) and optionally with React (react branch).

# Process

1. Created with:
```
npm init electron-app@latest electron-forge-vite-typescript -- --template=vite
```

2. Typescript was added with [this PR](https://github.com/stephenhandley/electron-forge-vite-typescript/pull/1) in this [branch](https://github.com/stephenhandley/electron-forge-vite-typescript/tree/typescript).

<img width="820" alt="typescript" src="https://github.com/stephenhandley/electron-forge-vite-typescript/assets/3257/7573089a-094c-45b4-8073-b8519bdc7a22">

3. React was added with [this PR](https://github.com/stephenhandley/electron-forge-vite-typescript/pull/2) in this [branch](https://github.com/stephenhandley/electron-forge-vite-typescript/tree/typescript-react). Changes were based on generating a new [Vite + React + Typescript](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) project with the following:
```
npm create vite@latest vite-react-swc-ts -- --template react-swc-ts
```

<img width="820" alt="typescript-react" src="https://github.com/stephenhandley/electron-forge-vite-typescript/assets/3257/a9e6bc14-2c23-4c77-a6c4-b63c6748f0e2">
