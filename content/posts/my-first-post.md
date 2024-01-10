+++
title = 'Trying out Hugo'
date = 2024-01-10T01:35:25+02:00
draft = false
+++

## Introduction

_Used instructions from [Hugo Site](https://gohugo.io/getting-started/quick-start/)_

#### These commands should get you started

```
hugo new site quickstart
cd quickstart
git init
git submodule add https://github.com/theNewDynamic/gohugo-theme-ananke.git themes/ananke
echo "theme = 'ananke'" >> hugo.toml
hugo server
```

Install themes as a submodule.

#### Create your first post

`hugo new content posts/my-first-post.md`

_You know markdown, right?_

#### Build

`hugo server --buildDrafts` or `hugo server -D`

## Publish

When publishing your site make sure to modify the parameter for `draft` from `false` to `true`.

## TODO
- [ ] Add copy to clipboard
