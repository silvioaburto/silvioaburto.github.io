# About

Personal Website

# Local Dev using Docker

```
docker build -t my-jekyll-site .
docker run -p 4000:4000 -v $(pwd):/srv/jekyll my-jekyll-site
```
