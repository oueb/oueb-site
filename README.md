# OUEB.io

## setup

(required) [hugo extended version](https://gohugo.io/getting-started/installing/#snap-package) (it can compile sass and more)
```
$ git clone git@github.com:oueb/oueb-site.git
$ cd oueb-site
$ git submodule update --remote --init
$ hugo server
```

then go to [localhost:1313](http://localhost:1313)

## update theme
git submodules are a bit counter-intuitive
to keep the submodule up to date with master :
```
$ git submodule update --remote
```