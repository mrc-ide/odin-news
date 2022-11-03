# odin-news

This is the source for our odin changelog, it will be deployed to https://mrc-ide.github.io/odin-news - it covers changes to the odin stack:

* [odin](https://mrc-ide.github.io/odin)
* [dust](https://mrc-ide.github.io/dust)
* [odin.dust](https://mrc-ide.github.io/odin.dust)
* [mcstate](https://mrc-ide.github.io/mcstate)

It does not cover [wodin](https://github.com/mrc-ide/wodin) related news, which is available [on its own site](https://reside-ic.github.io/wodin-news)

## Install hugo

This needs a recentish version of hugo (at least 0.83), which might not get on with the current reside blog. The version in apt is probably too old, but snap works (`sudo snap install hugo --channel=extended`)

## Download source

```
git clone --recursive git@github.com:mrc-ide/odin-news
```

## Create a new post

```
hugo new posts/<title>
```

This will create a .md file in `content/posts` which you should edit.

The front matter options that might be useful:

```
---
title: "Add a title here"
date: 2022-10-20T13:51:48+01:00
tags: ["release"]

hideSummary: false # set this to true to prevent the summary
summary: "A string here" # set this to force the summary content
---
```

## Develop

```
hugo serve
```

Visit http://localhost:1313/odin-news/ to see changes, editing the file will reflect immediately

## Docs

* [Theme docs](https://github.com/adityatelange/hugo-PaperMod)
* [Hugo docs](https://gohugo.io/documentation/)
