#### Including nodemon to the typescript project 

```
npm install --save-dev ts-node-dev

```
- add a script to the package json

```
{
  // ...
  "scripts": {
      // ...
      "dev": "ts-node-dev index.ts",
  },
  // ...
}

```

-  by running npm run dev, we have a working, auto-reloading development environment for our project!
-  to initialize tsconfig.json settings by running

```
 npm run tsc -- --init
 
```
