# Hugo 

This repo simply shows that having a `baseof.html` in the `layouts/_default` directory doesn't transform the `index.md`, `page1.md` or `page2.md` in the `content` directory to `html`.

## Version

```
hugo version
Hugo Static Site Generator v0.72.0/extended darwin/amd64 BuildDate: unknown
```

## Output

```
$ hugo
Building sites … WARN 2020/06/06 11:13:26 found no layout file for "HTML" for kind "taxonomyTerm": You should create a template file which matches Hugo Layouts Lookup Rules for this combination.
WARN 2020/06/06 11:13:26 found no layout file for "HTML" for kind "taxonomyTerm": You should create a template file which matches Hugo Layouts Lookup Rules for this combination.
WARN 2020/06/06 11:13:26 found no layout file for "HTML" for kind "page": You should create a template file which matches Hugo Layouts Lookup Rules for this combination.
WARN 2020/06/06 11:13:26 found no layout file for "HTML" for kind "home": You should create a template file which matches Hugo Layouts Lookup Rules for this combination.

                   | EN  
-------------------+-----
  Pages            |  5  
  Paginator pages  |  0  
  Non-page files   |  0  
  Static files     |  0  
  Processed images |  0  
  Aliases          |  0  
  Sitemaps         |  1  
  Cleaned          |  0  

Total in 9 ms
```