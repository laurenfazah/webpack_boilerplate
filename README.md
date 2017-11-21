# Webpack Boilerplate

## Setup

```bash
npm install
npm start
```

Application will be running at `http://localhost:8080/`.

## CSS

`node-sass` is installed with Bourbon configured.

`file-loader` is emitting images at `/img/<name>.<ext>`.

`index.scss` is required into `index.js` - there are no other configuration requirements for CSS. Changes are being watched by Webpack.

## Tests

Run tests with:

```bash
npm test
```

## GH Pages Deploy

```bash
npm run build
git add <>
git commit <>
git push origin master
```

Set `master` as source for GH Pages in repo's GitHub settings.
