# shirapslabs-top

Static site for Shiraps Labs.

## Cloudflare Pages

- Build command: none
- Build output directory: `dist`

Refresh the deployable files before publishing:

```sh
cp index.html dist/index.html
cp shiraps-labs-introduction.html dist/shiraps-labs-introduction.html
```

When `ads.txt` is ready, place it at `dist/ads.txt` so it is served from `/ads.txt`.
