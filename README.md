# legacy-docs

Placeholder repository for legacy documentation that deployed to ReadTheDocs.

**To build:**

```sh
cd docs && make dirhtml
```

**To serve:**

```sh
# nodejs
npx http-server docs/_build/dirhtml
# python 2
cd docs/_build/dirhtml && python -m SimpleHTTPServer 8080
# python 3
cd docs/_build/dirhtml && python -m http.server 8080
```
