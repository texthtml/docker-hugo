# Hugo

This a docker image for [Hugo](http://gohugo.io), a fast and flexible static site generator.

## Usage

Getting help:

```bash
docker run -v $(pwd):/site/ texthtml/hugo hugo --help
```

Serving content:

```bash
docker run -p 1313 -v $(pwd):/site/ texthtml/hugo hugo server --bind 0.0.0.0
```
