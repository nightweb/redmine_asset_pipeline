Redmine Asset Pipeline plugin
=============================

This plugin adds asset pipeline awesomeness to Redmine and Redmine plugins.

For who ?
---------
This plugin only targets plugin developers. You shouldn't try to install this without a deep understanding of the benefits and the way to make it work.

Why ?
-----
By default, Redmine made the deliberate (and wise) choice to disable the asset pipeline for core development. Enabling the asset pipeline by default would bring a thousand questions for people who are not in Rails and have a deep understanding of how it works. See [some of my thoughs about this here](http://www.redmine.org/issues/11445#note-9).

Having the asset pipeline enabled would be interesting though if you have a lot of plugins, which is my case. The average page on my biggest Redmine instance downloads ~40 js/css individual files, which is a big waste in terms of performance and bandwith. I'd really like them to be minified and bundled into one application.js and one application.css.

How ?
-----
Don't know yet, let me do some tests first..