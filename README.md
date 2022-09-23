# BILSEN Homepage

This repository contains the source code of BILSEN's homepage.
It is based on [this template](https://github.com/daattali/beautiful-jekyll).

## Development

The website is developed with Jekyll and Ruby.

For local development, you can use Docker:

```bash
docker run --rm --volume="${PWD}:/srv/jekyll:Z" -p 4000:4000 jekyll/jekyll:4.2.2 jekyll serve
```
