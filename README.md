> url -> https://hub.docker.com/r/fforres/node-alpine-graphicsmagick-chromium/
A Docker Image with GraphicsMagick, node 8.10.12, and chromium for working with graphics magick and puppeteer

Using - https://github.com/mpneuried/nodejs-alpine-gm


### Construir la imagen
- docker build .

### Pushear una nueva imagen
- docker build.
  ```
  (....)
  Successfully built 21e073f0e146
  ```
- docker tag 21e073f0e146 fforres/node-alpine-graphicsmagick-chromium:8.10.12
- docker push fforres/node-alpine-graphicsmagick-chromium:8.10.12