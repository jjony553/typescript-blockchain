# typescript-blockchain  
### more projective for typescript environment  
## 1. add index.js  
*add> package.json > scripts >  "start": "node build/index.js"*
```javascript
  "scripts": {
    "build": "tsc",
    "dev": "nodemon --exec ts-node src/index.ts",
    "start": "node build/index.js"
  },
```
## 2. install  npm i -D ts-node  
#### for run typescript no having build all the time  
*add> package.json > scripts >  "dev": "ts-node src/index.ts"*
```javascript
  "scripts": {
    "build": "tsc",
    "dev": "ts-node src/index.ts",
    "start": "node build/index.js"
  },
```
## 3. install npm i nodemon  
#### auto refresh, no need to kill the server  
*add> package.json > scripts >  "dev": "nodemon --exec"*
```javascript
  "scripts": {
    "build": "tsc",
    "dev": "nodemon --exec ts-node src/index.ts",
    "start": "node build/index.js"
  },
```
- - -
## install @types/node  
#### for using 'crypto' package  
*npm i -D @types/node*
- - -
## result  
![result](https://user-images.githubusercontent.com/55618626/180645714-2dd7de4d-f7e5-4fb9-a478-a0cc228fa2c6.png)
