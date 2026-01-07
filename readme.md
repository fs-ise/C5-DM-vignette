# Online labor markets and worker selection: A systematic review (vignette)

The vignette is available at []().

Build locally

```sh
cenv
rm -R _manuscript/ && rm -R _freeze/ && quarto render && quarto render *.qmd --to html && mv *_files _manuscript/ && mv -- *.html _manuscript/ && cp -r figures _manuscript/
```

Publish to GitHub pages:

```sh
quarto publish
```