# cimlens

**Open it: https://m-mirz.github.io/cimlens-site/**

cimlens explores and checks CGMES and Network Code models in the browser:

- the grid and every object in it;
- validation and its findings;
- power flows, and security analyses with their SAR;
- edits saved back into the files.

It runs [gridoxide](https://github.com/m-mirz/gridoxide) and
[cimoxide](https://github.com/m-mirz/cimoxide) as WebAssembly in a static page. It installs as an
app and works offline.

Nothing you load leaves your machine. The page contacts other sites only when you ask it to:

- **"Load an example"** fetches ReliCapGrid, ENTSO-E's test configuration, from GitHub.
- **The chat** sends your questions, and what it reads of the model to answer them, to the AI
  provider you choose, with your own API key.

## This repository

This repository only hosts the built site. The source is developed in a separate repository.

## Licences

cimlens is licensed under the Apache License 2.0 (see `LICENSE`). The site includes libraries under
their own licences, some of them LGPL. They are listed with their notices in
`third-party-licenses.txt`, which ships with the site and which the page links to.
