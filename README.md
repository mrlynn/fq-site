# fq.mlynn.dev

The marketing page for [Fiscal Quarter](https://github.com/mrlynn/fq), a macOS menu bar app with widgets and an iPhone app for anyone whose work runs on quarters.

It is one static page: `index.html` with inline CSS and a little JavaScript, plus screenshots in `img/`. There is no build step. The headline quarter, the year line, and the countdowns are worked out in the visitor's browser from their own date, using the app's built-in calendar year.

To preview it locally:

```sh
python3 -m http.server 4317
```

It deploys to Vercel, which serves `fq.mlynn.dev`.
