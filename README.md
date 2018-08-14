# plotly-browserify-issue
> Demonstrating an issue with plotly.js and Browserify

## Steps to reproduce the issue

### 1. Install deps

```
npm install
```

### 2. Reproduce issue with `dist` package

```
npm run example:dist
```

Error shown:

```
Error: Cannot find module '../src/lib' from '/home/frederik/projects/plotly-browserify-issue/node_modules/plotly.js-dist'
```

### 3. Reproduce issue with plotly package

```
npm run example:plotly
```

Error shown:

```
Error: Cannot find module './core' from '/home/frederik/projects/plotly-browserify-issue/node_modules/plotly.js/dist'
```

### 4. Create a bundle with non-dist

```
npm run example:main
```

Bundles correctly.

