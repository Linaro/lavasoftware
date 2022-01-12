# lavasoftware.org Static Jekyll Website

This is the git repository for static Jekyll-based lavasoftware.org website ([https://www.lavasoftware.org/](https://www.lavasoftware.org/)).

This static Jekyll site is using the [`linaro-jekyll-theme`](https://github.com/linaro-marketing/linaro-jekyll-theme).

Please take a moment to review the guides on the [theme's documentation site](https://linaro-jekyll-theme.readthedocs.io/en/latest/).

---

## Contributing

To make it easier to contribute to the content, Linaro provides a couple of Docker containers for building and checking the site. All you need is Docker installed on your computer and enough RAM and disc space.

To build the site:

```bash
cd <git repository directory>
./build-site.sh
```

To build the site and then serve it so that you can check your contribution appears:

```bash
cd <git repository directory>
JEKYLL_ACTION=serve ./build-site.sh
```

To check that your contribution doesn't include any broken links:

```bash
cd <built web site directory>
../check-links.sh
```

The built web site directory will be `production.lavasoftware.org`.

For more information, please see the [build container wiki](https://github.com/linaro-its/jekyll-build-container/wiki) and the [link checker wiki](https://github.com/linaro-its/jekyll-link-checker/wiki).
