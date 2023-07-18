# Conditional exports demo

> https://nodejs.org/api/packages.html#conditional-exports

- `node index.js` = uses `math/index.js` because it's importing using `import`
- `node index.cjs` = uses `math/index.cjs` because it's importing using `require()`
