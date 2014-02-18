jekyll-jquerymobile-app
=======================

A modified jekyll blog to produce a single page jquery mobile app.


Usage
-----

Write posts as usual, then use `jekyll build` to generate the SPA.

Folders
-------

*   `_source` contains all the jekyll assets
*   `_app` contains the generated app. This folder is intended to be a git submodule and should contain
    *   `www` which will receive the generated index.html et al.

`_app` is intended to have the folder structure required by either a local cordova/phonegap/icenium environment,
or in the case of a git submodule, the structure required by phonegap build or icenium.

Status
------

It's all still a bit rough, but it should be functional.
Although, there's nothing fancy yet.


