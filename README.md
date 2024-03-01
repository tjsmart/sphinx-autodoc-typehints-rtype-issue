# Repo to demonstrate sphinx-autodoc-typehints :rtype: issue

To build the docs use `sphinx-build`, for example:
```shell
sphinx-build --color -E -W -a -T -b html docs/source docs/build
```

And then view the docs by starting an http server:
```shell
python -m http.server --directory docs/build 8080
```
and then navigating to `http://<hostname>:8080`.
