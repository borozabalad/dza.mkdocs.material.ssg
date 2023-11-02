# Welcome to MkDocs

For full documentation visit [mkdocs.org](https://www.mkdocs.org).

## Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.

### Code example
some `code` goes here

#### Plain code block
```python
def foo():
    bar = \
        'str'
    
    if not bar:
        return True
```

#### Highlighting lines
```python hl_lines="2 3"
def bubble_sort(items):
    for i in range(len(items)):
        for j in range(len(items) - 1 - i):
            if items[j] > items[j + 1]:
                items[j], items[j + 1] = items[j + 1], items[j]

```

## Equations
<script
  src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML"
  type="text/javascript">
</script>

**_NOTE:_** I added a script for *MathJax*
```
**_NOTE:_** I added a script for *MathJax*
```
[comment]: < script tag > (This is a comment, it will not be included) 
This is an inline equation: $$V_{sphere} = \frac{4}{3}\pi r^3$$,<br> 
followed by a display style equation: 

$$V_{sphere} = \frac{4}{3}\pi r^3$$
