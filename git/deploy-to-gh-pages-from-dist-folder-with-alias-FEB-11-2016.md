#Deploy to gh-pages from dist folder with alias

You can create an alias in `~/.gitconfig` in the `[alias]` section like so:

````
[alias]
     stpp = subtree push --prefix
````

So, then to push to github:

`git stpp dist origin gh-pages`
