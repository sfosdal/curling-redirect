# curling-redirect

The redirect stub for **curling.here.events** → **https://curling.events/**
(the site itself is sfosdal/curling-events). `index.html` and `404.html` are
the same page: a JS `location.replace` that keeps the path, query and hash,
with a meta refresh and a canonical link for readers and crawlers without JS.
Served by GitHub Pages from `main`.
