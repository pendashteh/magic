What if you could do this without having Python3 installed:

```
$ magic python python3
```

Or compile your first haskell program without even having haskell!
```
$ echo 'main = printStrLn "Magic Works."' > hello.hs
$ magic haskell ghc -o hello hello.hs
Linking hello
$ ls
hello hello.hs
```

# INSTALL
Make sure you have docker installed. That is the only requirement.

