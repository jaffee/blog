# setup

```
hugo new site blog
cd blog
git init
git submodule add https://github.com/zwbetz-gh/cupper-hugo-theme.git themes/cupper-hugo-theme
cp themes/cupper-hugo-theme/exampleSite/config.yaml .
mv config.toml  config.toml.bak
hugo new posts/pool.md
git commit -m "add copper hugo theme"
```
