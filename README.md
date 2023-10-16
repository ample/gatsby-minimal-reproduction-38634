This repo recreates the behavior described here:
https://github.com/gatsbyjs/gatsby/issues/38634

To reproduce the broken GraphiQL UI, you just need ot export the `ENABLE_GATSBY_REFRESH_ENDPOINT` like so...

```
ENABLE_GATSBY_REFRESH_ENDPOINT=true ./node_modules/.bin/gatsby develop
```
