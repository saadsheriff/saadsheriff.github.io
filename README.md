# { Personal } Jekyll Theme

## How to run locally

You can use Docker to run the website to avoid installing any dependencies to
your local environment. To do so, run:

```shell
docker-compose up --build
```

Alternatively, you can run the website locally by installing ruby and then
installing the project dependencies by running:

```shell
make install
```

And then start serving the website:

```shell
jekyll serve --watch --host 0.0.0.0 --config _config.yml,_config.dev.yml
```

## Documentation

The theme contains documentation in the form of
[blog posts](https://le4ker.github.io/personal-jekyll-theme/blog).
