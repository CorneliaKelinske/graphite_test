# graphite_test

## How to install graphite

```
npm install -g @withgraphite/graphite-cli
```

## Initialize a repo (start tracking things)

```
gt repo init
```

## Create a new branch, commit, and draft PR

You need to have uncommitted work in your source control

```
gb new_branch_name Title of PR
```

## Sync your work with remote and rebase all the things (this is for rebasing)

```
gs
```

## How to rebase

Fix all the things as usual and then run

```
gt . && gt continue
```

Once you have finished all the rebasing, run `gs` one more time from `main`

## Mark pull request as ready for review

```
prr
```

## Look at a log of commits

```
gl
```

q to exit, you can use up and down arrows to navigate


## Navigate up and down

```
gu

gd
```


## New habits

Never add additional commits with any way other than `gb`, always use amend instead.