## Next Release

BREAKING CHANGES:
FEATURES:
IMPROVEMENTS:
BUG FIXES:

## v3.26

BUG FIXES:

 * bug fix to query `select * from pipes where name in ("web_test");`
 * Command systemctl stop comet.service does not work on Ubuntu 16 ( #17 )

IMPROVEMENTS:

* Added parameter `send_user_online_events` to `main`
* Added parameter `send_user_offline_events` to `main`
* Added parameter `save_users_last_online_time` to `main`

* Added section `cluster`
* Added section `cometqlproxy`
* Added clustering mechanism #15
* Added pidfile option in section `main`.`pidfile`

* Added queryes like `set paramName paramValue`
* Added queryes like `set sectionName paramName paramValue`

## v3.25

IMPROVEMENTS:

* Added error messages for comet.ini parser

## v3.24

IMPROVEMENTS:

* Allowed adding spaces after section name in .ini file
 
BUG FIXES:

 * Was rename parameter `benchmark` to `statistics`

## v3.23

IMPROVEMENTS:

 * added parametr `allow` to section `statistics` in .ini file
 * added ini file documentation in to file ./docs/comet.ini.md

## v3.22

BUG FIXES:

 * last online time did not save

IMPROVEMENTS:

* Added functions for aggregating statistics of using server
* Added settings to .ini file for controll content-type header
* Added dosc in dokuwiki format
* Was translated comments in comet.ini
* Added the white list of hosts to .ini file

## v3.21

IMPROVEMENTS:

* Added caching in memory for sending static files
* Added cache-control headers for get requests

## v3.2

BUG FIXES:
 * Js Api version 3.28 (Fix bug in auth callbacks)
 * Fix bug in auth callbacks
 * complete api function getTrackPipeUsers

## v3.1

FEATURES:

 * Added function to getting users in track_pipes from js api
 * Added deleting api query for pipes history #5
 * Added CODE_OF_CONDUCT.md
 * Added CONTRIBUTING.md
 * Added CHANGELOG.md
 * Added server version to ws answer
 * Js Api version 3.26
 * Removed message `setState` from console log in Js Api
 * Fixed bug when Js api in offline