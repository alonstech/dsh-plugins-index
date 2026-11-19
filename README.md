# Alonstech DSH plugin index

Public plugin market index for DeepSeek Harness, served by GitHub Pages:

```
https://alonstech.github.io/dsh-plugins-index/index.json
```

Add that URL under **Plugins → Discover** in DSH (after switching on
**Custom plugin indexes** under Experimental plugins) to browse and install the
plugins built by Alonstech.

This repository is generated. `index.json` and `icons/` are produced by
`node scripts/build-index.mjs` in the private
[`alonstech/dsh-plugins`](https://github.com/alonstech/dsh-plugins) repository and
pushed here by its publish workflow. Do not edit by hand; edit the plugin package
and republish instead.

The plugin packages themselves are private and live on GitHub Packages under the
`@alonstech` scope. Installing them needs a GitHub token with `read:packages`; see
the consuming guide in the source repository.
