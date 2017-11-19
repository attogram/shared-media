# The Attogram Shared Media Project

The Attogram Shared Media Project is a set of PHP packages for working with [Free Cultural Works](https://freedomdefined.org/Definition).

## Shared Media Tagger
* url: https://github.com/attogram/shared-media-tagger
* about: Ratings website creator for images and media files, fed from administrator curated media from Wikimedia Commons.
* status: v0.7
* external packages: None.  *Proof of concept only.*
* Demo: http://fosiper.com/smt/

## Shared Media API
* url: https://github.com/attogram/shared-media-api
* about: MediaWiki Query API wrapper that easily gets Category and Media file information into simple PHP arrays. Fine-tuned for WikiMedia Commmons
* status: v1.0
* external packages: guzzlehttp/guzzle, psr/log

## Shared Media ORM
* url: https://github.com/attogram/shared-media-orm
* about: Database Object-relational mapping (ORM) for `attogram/shared-media-api`
* status: v1.0
* external packages: propel/propel

## Shared Media Sandbox
* url: https://github.com/attogram/shared-media-sandbox
* about: Web Sandbox for testing `attogram/shared-media-api` and  `attogram/shared-media-orm`
* status v1.1
* external packages: psr/log

## Shared Media Gallery
* url: https://github.com/attogram/shared-media-gallery
* about: Web Gallery and Backend Admin, uses `attogram/shared-media-api` and  `attogram/shared-media-orm`
* status: v0.0
* external packages: twig/twig

# License
All Shared Media packages are open source and available under the MIT License.
