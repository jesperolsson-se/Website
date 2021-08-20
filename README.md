Personal website, available at [jesperolsson.se](http://jesperolsson.se/).

# Build and Serve with Docker

```
docker run --rm -it \
  --volume="$PWD:/srv/jekyll" \
  -p 4000:4000 jekyll/jekyll:3.8 \
  jekyll serve
```
