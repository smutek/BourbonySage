### 8.5.1: February 21st, 2017
* Up to date with Sage 8.5.1
  * Update gulp-imagemin options ([#1839](https://github.com/roots/sage/pull/1839))
  * Add error handling to `scripts` and `styles` gulp tasks ([#1832](https://github.com/roots/sage/pull/1832))
  * Update to Bootstrap 4.0.0-alpha.6  ([#1832](https://github.com/roots/sage/pull/1832))

### 1.2.2 : February 27, 2016

Fix [Issue 3](https://github.com/smutek/BourbonySage/issues/3), allowing visual grid to change as required by layout. Add Omega Reset mixin, merge latest from Sage Master.

* Remove grid settings from variables.scss
* Create assets/grid-settings.scss (holds grid settings and import neat helpers)
* Add override to bower.json - import bourbon then the new grid-settings file (allows grid-settings to be injected via wiredep after Bower, and before Neat)
* Add Omega Reset by Josh Fry - because this will likely become an issue as well. Code from Alex Vasquez's [Some Like It Neat](https://github.com/digisavvy/some-like-it-neat/blob/master/assets/sass/_grid-settings.scss) starter theme.
* Remove unnecessary .row class from base.php
* Merge pull request #1618 from sage/master


### 1.2.1 : February 24, 2016

* Delete the grid file which I inadvertently re-added when I merged the most recent commits from Sage master.
* Grid settings now live in common/layouts with associated variable definitions in common/variables
* Removed commented/unused code from components/comments

### 1.2: February 14, 2016

* Merge latest upstream branch of Sage master.

### 1.1: January 26, 2016

* Add visual grid options to variables ([Issue #1](https://github.com/smutek/BourbonySage/issues/1))
* Move grid variable definitions to variables
* Rename grid to layouts, move file from /components to /common
* Update style.css (theme name) and readme
