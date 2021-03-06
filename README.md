# RodolfoCarvalho.net

Here's the content for my homepage at https://www.rodolfocarvalho.net/.


## Notes

### Development

Run a development server:

```
bin/dev-server
```

The live rendered website will be rendered to `${TMPDIR-/tmp}/hugo-rodolfocarvalho.net-DEV-*/`.  
The server will watch for file changes and re-render automatically.  
The browser should also refresh the page automatically.

### Adding a new blog post

Run:

```
bin/new-post SLUG
```

A new file will be created at `content/posts/YEAR/MONTH/DAY-SLUG.md`.

### Deployment

Build for publishing:

```
bin/build-release
```

The rendered website will be in the `public/` directory.

The website is deployed from
[GitHub](https://github.com/rhcarvalho/rodolfocarvalho.net) to
[Netlify](https://app.netlify.com/).  
The generated `public/` directory is not versioned.

---
Powered by [Hugo](https://gohugo.io/). Latest version used: <!-- hugo version -->v0.55.2-9D020348
