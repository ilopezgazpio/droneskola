# Dron eskola irekia
Drone eta urrutiko gailuen inguruko tinker eskola irekia.

## Aurkezpena

## Nor gara

## Ikasketa-ildoak

## Kontribuzioak

## Local Deployment of site (and debugging :S )

- apt requirements

```
ruby-dev header files
ruby-bundler
jekyll
jekyll github
```

- create a Gemfile with the content

```
source "https://rubygems.org"

gem "github-pages", group: :jekyll_plugins
gem "webrick"
```

then run

```
bundle install
```

- bundle requirements

```
jekyll - gem install bundler jekyll
```

For deployment, run:

```
ruby -v
jekyll -v
bundle exec jekyll serve --port 4000
```
