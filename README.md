# $ magic
What if you could get a `python3` shell without having it installed?

```
$ magic python python3
```

Or compile your first `haskell` program without even having haskell!
```
$ echo 'main = printStrLn "Magic Works."' > hello.hs
$ magic haskell ghc -o hello hello.hs
Linking hello ...
$ ls
hello hello.hs
```

# USAGE

```
$ magic APP COMMAND
```

`APP` is the name of a docker image on Docker Hub. e.g. `gcc`, `composer`, `drush/drush`

`COMMAND` is a shell command. It will be passed to `bash` inside the container.
(and yes, it only works on containers that have `bash` on them)

# INSTALL
Make sure you have docker installed. That is the only requirement.

