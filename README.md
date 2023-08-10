

### 1. Clone the repo

```sh
  $ https://github.com/tfobadar/next13-storyblok-boilerplate.git
```

### 2. Install all dependecies 
```sh
$  yarn # or npm install
```

### 3. Adding the Access token
Create a new empty Space and exchange the preview token with your own in ```pages/_app.js```.

```js
// in pages/_app.js
storyblokInit({
  accessToken: "your-preview-token",
  use: [apiPlugin],
  components,
});
```

### 4. Run your project
Set the preview domain in <strong>Storyblok</strong> to `http://localhost:3000/`

```sh
# to run in developer mode
$ yarn dev # or npm run dev
```

```sh
# to build your project
$ yarn build # or npm run build
```



## Resources

- [Next.js docs](https://nextjs.org/docs/#setup)
- [Storyblok Tutorial](https://www.storyblok.com/tp/add-a-headless-cms-to-next-js-in-5-minutes)
- [Preview Mode](https://nextjs.org/docs/advanced-features/preview-mode)


  