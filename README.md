# shirapslabs-top

Static site for Shiraps Labs.

## Cloudflare Pages

- Build command: none
- Build output directory: `dist`

Refresh the deployable files before publishing:

```sh
cp index.html dist/index.html
cp pc_sample.png mobile_sample.png profile_icon.png dist/
```

When `ads.txt` is ready, place it at `dist/ads.txt` so it is served from `/ads.txt`.
