This repo recreates the behavior described here:
https://github.com/gatsbyjs/gatsby/issues/38634

To reproduce the broken GraphiQL UI, you just need ot export the `ENABLE_GATSBY_REFRESH_ENDPOINT` like so...

```
ENABLE_GATSBY_REFRESH_ENDPOINT=true ./node_modules/.bin/gatsby develop
```

<img width="1712" alt="Screen Shot 2023-10-16 at 3 50 46 PM" src="https://github.com/ample/gatsby-minimal-reproduction-38634/assets/50378/9a0fd2df-beb0-428d-9b48-7d2ac813bfae">
