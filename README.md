# Information

Site content.

## Install

```
git submodule add https://github.com/site-0001/content.git content
```

## Update

```
git submodule update --remote
```

## Uninstall

```
git submodule deinit -f content && git rm -r --cached content && rm -rf .git/modules/content
```
