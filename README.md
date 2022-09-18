# Express and TypeScript

## 1. Install TypeScript Global

```
npm i -g typescript
tsc -v
```
* Windows Error:  `Set-ExecutionPolicy Unrestricted`

## 2. Create file tsconfig.json
```
tsc --init
or
npx tsc --init
```
## 3. Start Nodejs application
```
npm init -y
```
## 4. Create Diretory
```
mkdir src
touch src/app.ts
```
## 5. Install Dependences
```
npm add ts-node-dev typescript -D
```
## Edit package.json to auto restart
```
"scripts": {
  "dev": "ts-node-dev --respawn --transpile-only  src/app.ts"
}
```
### Change file and add on app.ts
> console.log('Hello Word');

## 6. Install ExpressJS 
```
npm add express
npm add @types/node @types/express -D
```
### Run dev application command:
```
npm run dev
```
