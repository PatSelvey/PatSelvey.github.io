# PatSelvey.org

This is my personal website with my teaching resources, books and more.

The theme is based on the [Agency bootstrap theme](https://startbootstrap.com/theme/agency)

To update that, just copy in the new "dist" files (just the css and js).

## Serve locally

Use the devcontainer and run `bundle exec jekyll serve`

```powershell
docker build -t jekyll .devcontainer
docker run --rm -it -v "$PWD`:/srv/jekyll" -v "$PWD/vendor/bundle:/usr/local/bundle" -p 4000:4000 -d jekyll bundle exec jekyll serve
```

# Resources

I'm working on adding books, videos, and more. Currently, I just have books, which are in '/_posts' with the images (and downloads) in '/assets/img/books'

