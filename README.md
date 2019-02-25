# nub-javadocs

After *nub* api is compiled run:

```sh
#n below is the prescene release
$ cd nubjs/distribution/frames-n/reference
$ git init
$ git remote add origin https://github.com/VisualComputing/nub-javadocs.git
$ git add *
$ git commit -am'init commit'
$ git pull --allow-unrelated-histories origin gh-pages -Xours
$ git push origin master:gh-pages
```
