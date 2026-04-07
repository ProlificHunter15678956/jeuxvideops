# jeuxvideops


##  Installation

This project uses git submodules.
By default Git doesn't clone submodules of a repo.
So once you clone the repo, you must run :

``` bash
git submodule init
```

Or clone the repo by running : 

``` bash
git clone --recurse-submodules
```

##  Updating

Since we use submodules we must run the following commands to fetch updates : 

``` bash
git fetch
git submodule update
```

Run these command to push changes : 

``` bash
git push --recurse-submodules
```