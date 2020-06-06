# Hugo 

This repo simply shows that having a `baseof.html` and `single.html`in the `layouts/_default` directory transforms `index.md` to html, but not `page1.md` or `page2.md` in the `content` directory to `html`.

## Version

```
hugo version
Hugo Static Site Generator v0.72.0/extended darwin/amd64 BuildDate: unknown
```

## Output

```
$ hugo
Building sites … WARN 2020/06/06 11:21:00 found no layout file for "HTML" for kind "home": You should create a template file which matches Hugo Layouts Lookup Rules for this combination.
WARN 2020/06/06 11:21:00 found no layout file for "HTML" for kind "taxonomyTerm": You should create a template file which matches Hugo Layouts Lookup Rules for this combination.
WARN 2020/06/06 11:21:00 found no layout file for "HTML" for kind "taxonomyTerm": You should create a template file which matches Hugo Layouts Lookup Rules for this combination.

                   | EN  
-------------------+-----
  Pages            |  6  
  Paginator pages  |  0  
  Non-page files   |  0  
  Static files     |  0  
  Processed images |  0  
  Aliases          |  0  
  Sitemaps         |  1  
  Cleaned          |  0  

Total in 10 ms
```