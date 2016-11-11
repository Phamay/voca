Fork the repostiory, then clone it into your project directory.

Install the development dependencies within Voca source directory:
```bash
npm install
```

1) Build the bundle into `dist/` folder.  
`dist/voca.js` is an [UMD](https://github.com/umdjs/umd) build compatible with CommonJS, RequireJS and Browser globals.  
`dist/voca.min.js` is the minified UMD, production-ready.

```bash
npm run build
```

2) Run the library over the unit tests:
```bash
npm test
```

3) Verify the code coverage:
```bash
npm run coverage
```

4) Check the code using eslint tool:
```bash
npm run eslint
```