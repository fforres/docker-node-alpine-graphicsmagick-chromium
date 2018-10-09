# docker-node-alpine-graphicsmagick-chromium

> [https://hub.docker.com/r/fforres/node-alpine-graphicsmagick-chromium/](https://hub.docker.com/r/fforres/node-alpine-graphicsmagick-chromium/)
>
> A Docker Image with:
> - GraphicsMagick 1.3.30
> - Node 8.10.12
> - Chromium
>
> for working with graphics magick and puppeteer

Based on [https://github.com/mpneuried/nodejs-alpine-gm](https://github.com/mpneuried/nodejs-alpine-gm)

## Construir la imagen

- docker build .

## Pushear una nueva imagen

- docker build.

```Bash
  (....)
  Successfully built 21e073f0e146
```

- docker tag 21e073f0e146 fforres/node-alpine-graphicsmagick-chromium:8.10.12
- docker push fforres/node-alpine-graphicsmagick-chromium:8.10.12
