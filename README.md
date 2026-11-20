# Sidiom drivers

The public feed of signed Sidiom driver packages. Every Sidiom Gateway reads it as its built-in
driver catalogue.

- `index.json` and `index.json.sig`: the signed index of every released driver version.
- Releases `<id>/v<version>`: one signed package per driver version.

This repository holds no source code. Packages are published by the release tool and verified by
every Gateway against the keys pinned in its build.
