---
layout: githubproject
title: git-utils
description: Various git related utilities
github: git-utils
copyright: 2008-2011
hide: true
---


## About

git-utils is a collection of simple utilities that made my [Git](http://git-scm.com) life easier in some way or another. I tried to clean them up as much as necessary prior to putting here, so it should be easy to use for others as well.


## Installation

You don't need anything special, just a working installation of [Git](http://git-scm.com) and a UNIX system (tested with Mac OS X and Linux). To install the git-utils into `/usr/local` run

{% highlight console %}
$ sudo make install
{% endhighlight %}

or just pick the scripts that you need and place them wherever you want.


## Description

- <strong>git-copy</strong> Copy file from source path to target path and add the target path to the Git index.
- <strong>git-push-all</strong> Invoke `git-push` for all configured remote repositories.


## License

git-utils is licensed under the [GNU GENERAL PUBLIC LICENSE Version 3](http://www.gnu.org/licenses/gpl-3.0.html). See the [LICENSE](http://github.com/bmeurer/{{ page.github }}/raw/master/LICENSE) file for details.

