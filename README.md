# Software Needs You
This is the Software Needs You website repo. It uses Jekyll to generate static pages via Github-pages.

## Setup
To get it up & running locally you need a working [ruby](https://www.ruby-lang.org/en/) or
[RVM](https://rvm.io/). Then do the following:

```Bash
# ruby gems manager
gem install bundler
# get the needed gems
bundler install
# start the local jekyll website
bundler exec jekyll serve
```

## Branches
There are 2 main remote branches (beside `master`, obviously); `content` and `cosmetic`. It gets as straight
forward as it can get, `content` is used to manage posts and drafts, and `cosmetic` keeps track of the layout
and aesthetic concerns.
