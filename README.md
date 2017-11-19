# The Attogram Shared Media Project

The Attogram Shared Media Project is a set of PHP packages for working with [Free Cultural Works](https://freedomdefined.org/Definition).

## Shared Media Tagger 
Ratings website creator for images and media files, fed from administrator curated media from Wikimedia Commons.
* url: https://github.com/attogram/shared-media-tagger
* status: v0.7
* external packages: None.  *Proof of concept only.*
* Demo: http://fosiper.com/smt/

## Shared Media API
MediaWiki Query API wrapper that easily gets Category and Media file information into simple PHP arrays. Fine-tuned for WikiMedia Commmons
* url: https://github.com/attogram/shared-media-api
* status: v1.0
* external packages: guzzlehttp/guzzle, psr/log

## Shared Media ORM
Database Object-relational mapping (ORM) for `attogram/shared-media-api`
* url: https://github.com/attogram/shared-media-orm
* status: v1.0
* external packages: propel/propel, guzzlehttp/guzzle, psr/log

## Shared Media Sandbox
Web Sandbox for testing `attogram/shared-media-api` and  `attogram/shared-media-orm`
* url: https://github.com/attogram/shared-media-sandbox
* status v1.1
* external packages: propel/propel, guzzlehttp/guzzle, psr/log

## Shared Media Gallery
Web Gallery and Backend Admin, uses `attogram/shared-media-api` and  `attogram/shared-media-orm`
* url: https://github.com/attogram/shared-media-gallery
* status: v0.0
* external packages: twig/twig, propel/propel, guzzlehttp/guzzle, psr/log

# License
All Shared Media packages are open source and available under the MIT License.
