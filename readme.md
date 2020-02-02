```
cd test
pnpm i
pnpm r build
```
=> works

```
cd ../workspace
pnpm i -r
pnpm run -r build
```

=>
error TS7016: Could not find a declaration file for module 'ws'.
