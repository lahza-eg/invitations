# LAHZA — published invitations

Finished invitation pages, served by GitHub Pages at
<https://lahza-eg.github.io/invitations/>.

**Nothing here is written by hand.** Every file is produced by the LAHZA studio when
somebody presses Publish, and committed through the GitHub API. Editing a file here
will be overwritten the next time that invitation is published.

## What is in here

```
<slug>/index.html      one invitation
_next/static/...       the shared build output every invitation uses
assets/...             generated artwork and uploaded photographs
.nojekyll              stops Pages ignoring _next (a leading underscore)
```

## What is deliberately NOT in here

The application source, the database, uploads as a whole, `.env` files, admin
endpoints, customer contact details, and any field a template did not draw. The
exporter publishes the rendered page, so an invitation's private data cannot reach
this repository even by accident — and it refuses to commit a file containing any of
a list of forbidden strings.

## Privacy

Invitations are **unlisted, not secret**. Every page carries `noindex, nofollow` so
search engines leave them alone, and nothing links to them. But this repository is
public, which means anyone who has a link — or who reads this repository — can open
any invitation in it. Treat a published invitation as something you have handed out,
not something you have locked.
