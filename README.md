# typescript-jiw9h8

[Edit on StackBlitz ⚡️](https://stackblitz.com/edit/typescript-jiw9h8)

Minimal example of my issues trying to get typescript working with mdoule aliasing. 

Compiles fine with `noEmit: false` but when set to `true`, fails with:

```
ERROR in ./src/index.ts
Module build failed (from ./node_modules/ts-loader/index.js):
Error: TypeScript emitted no output for C:\Users\xxx\Projects\Web-Dev\typescript-resolution\src\index.ts.
    at makeSourceMapAndFinish (C:\Users\xxx\Projects\Web-Dev\typescript-resolution\node_modules\ts-loader\dist\index.js:80:15)
    at successLoader (C:\Users\xxx\Projects\Web-Dev\typescript-resolution\node_modules\ts-loader\dist\index.js:68:9)
    at Object.loader (C:\Users\xxx\Projects\Web-Dev\typescript-resolution\node_modules\ts-loader\dist\index.js:22:12)
error Command failed with exit code 2.
```

Meanwhile, TS compiler returns `Error:(1, 26) TS2307: Cannot find module '@bunnies'.`
