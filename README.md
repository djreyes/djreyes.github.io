# jeremyreyes.com

My site.

## Local Development

To launch the server:

```
$ bundle exec jekyll serve
```

## Deployment

Push to the `master` branch and GitHub should take it from there.

Domain is on [Namecheap](https://namecheap.com) and is configured with DNS nameservers from [Cloudflare](https://cloudflare.com).

- `A` records point to GitHub pages
- `CNAME` for `www` points to `djreyes.github.io`
- `MX` records point to G Suite

## Built With

* [GitHub Pages](https://pages.github.com/) - Simple hosting service
* [Jekyll](https://jekyllrb.com/) - Simple static site generator
