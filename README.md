## vite dev server 404

This is a reproduction of an issue I encountered on vite `a` and vite `b`. With the dev server, if the server has to serve a page a path like `/sites/example.com` it will `404`. `/sites/example.com/more` works OK though.

You can see the code I added in `src/App.tsx`. Everything else is standard output from the `yarn create vite --template react-ts` command.

```
yarn install

yarn dev
```