# README

## Create site

```shell
hugo new site .
```

## Example content

```shell
git clone https://github.com/matcornic/hugo-theme-learn.git
cp -r hugo-theme-learn/exampleSite/\* .
rm -rf hugo-theme-learn
```

```shell
rm -rf .git themes/learn
git init
git add .
git remote add origin https://github.com/karstenmueller/example-hugo-docs
git submodule add -f https://github.com/matcornic/hugo-theme-learn themes/learn
git commit -m 'initial commit'
```
