# The Attogram Shared Media Project

The Attogram Shared Media Project is a set of PHP packages for working with Free Cultural Works.

## Shared Media Tagger
* url: https://github.com/attogram/shared-media-tagger
* about: Ratings website creator for images and media files, fed from administrator curated media from Wikimedia Commons.
* status: v0.7 - Proof of concept
* Demo: http://fosiper.com/smt/

## Shared Media API
* url: https://github.com/attogram/shared-media-api
* about: MediaWiki Query API wrapper that easily gets Category and Media file information into simple PHP arrays. Fine-tuned for WikiMedia Commmons
* status: v1.0
* packages: guzzlehttp/guzzle, psr/log

## Shared Media ORM
* url: https://github.com/attogram/shared-media-orm
* about: Database Object-relational mapping (ORM) for shared-media-api
* status: v1.0
* packages: attogram/shared-media-api, propel/propel

## Shared Media Sandbox
* url: https://github.com/attogram/shared-media-sandbox
* about: Web Sandbox for testing Shared Media API an ORM packages
* status v1.1
* packages: attogram/shared-media-api, attogram/shared-media-orm, psr/log

## Shared Media Gallery
* url: https://github.com/attogram/shared-media-gallery
* about: Web Gallery and Backend Adminn, using Shared Media API an ORM
* status: v0.0
* packages: attogram/shared-media-api, attogram/shared-media-orm, twig/twig

# License
All Shared Media packages are open source and available under the MIT License.
