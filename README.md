#####################################################################
## **JEKYLL BLOG**
#####################################################################

[![Build Status](https://travis-ci.org/rrevanth/rrevanth.github.io.svg?branch=source)](https://travis-ci.org/rrevanth/rrevanth.github.io)
<!-- [![Inline docs](http://inch-ci.org/github/redvers/pastenix.svg)](http://inch-ci.org/github/redvers/pastenix)-->

This contains source and webpage for my blog http://rrevanth.github.io build using jekyll and hosted on github pages.

The source is in source branch and master branch contains the built site.

It also includes configuration for build Rakefile and configuration for building automatically with Travis CI.

#####################################################################
## **DEPLOY YOUR OWN BLOG**
#####################################################################

To host your own blog with this theme :

- Clone this repo.
- Remove all posts in _posts directory.
- For generating website,
	use command ```rake``` inside the source repo.
	It will automatically build the code and push it to master branch of the repo.
**Note:** You need to change the repo points in the Rakefile and wherever there is automation happening.

#####################################################################
## **PLUGINS**
#####################################################################

- Github now supports some plugins and I have included all of them although I use some of them.
You can find the gems in _config.yml and Gemfile .Edit them according to your usage.

#####################################################################
## **AUTOMATED DEPLOYMENT SETUP**
#####################################################################

- For auto deploying with Travis,check out the link http://rrevanth.github.io/blog/autodeploywithtravis
- Also check my other post for adding,editing posts with online github editor Prose.
