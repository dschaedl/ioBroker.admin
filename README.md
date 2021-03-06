![Logo](admin/admin.png)

# ioBroker.admin

user interface for configuration and administration

## Todo


## Changelog
### 0.3.10 (2015-01-14)
* (bluefox) fix error with adapter instances with more modes

### 0.3.9 (2015-01-10)
* (bluefox) support of multiple hosts if one host is down.

### 0.3.8 (2015-01-08)
* (bluefox) fix errors with states update if filtered. Resize command putput window.

### 0.3.7 (2015-01-07)
* (bluefox) fix errors with history state update.

### 0.3.6 (2015-01-07)
* (bluefox) group edit of history settings. Move history settings from states to objects.

### 0.3.5 (2015-01-06)
* (bluefox) add events filter. Fix error with alive and connected status.

### 0.3.4 (2015-01-04)
* (bluefox) fix error with update adapters with "-" in name, like hm-rpc or hm-rega

### 0.3.3 (2015-01-03)
* (bluefox) fix error if states without object

### 0.3.2 (2015-01-02)
* (bluefox) fix error if states without object

### 0.3.1 (2015-01-02)
* (bluefox) Support of npm install

### 0.3.0 (2014-12-25)
* (bluefox) Support of debounce interval for history

### 0.2.9 (2014-12-20)
* (bluefox) fix filter of IDs in objects

### 0.2.8 (2014-12-20)
* (bluefox) support of controller restart

### 0.2.7 (2014-12-19)
* (bluefox) fix time in log (web)
* (bluefox) replace enum edit with tree

### 0.2.6 (2014-12-16)
* (bluefox) replace jqGrid with fancytree by objects

### 0.2.5 (2014-12-07)
* (bluefox) fix object tree (some nodes was hidden)

### 0.2.4 (2014-12-05)
* (bluefox) preload last 200 lines from iobroker.log

### 0.2.3 (2014-12-04)
* (bluefox) install adapter with npm

### 0.2.2 (2014-11-29)
* (bluefox) Set language settings after license confirmed
* (bluefox) try to use npm installer for this adapter

### 0.2.1 (2014-11-26)
* (bluefox) Charts in history dialog
* (bluefox) filter states by history
* (bluefox) show only 500 events

### 0.2.0 (2014-11-20)
* (bluefox) support of no-"io." schema
* (bluefox) better enum editing
* (bluefox) update of object tree online

### 0.1.9 (2014-11-15)
* (bluefox) fix scripts editor

### 0.1.8 (2014-11-10)
* (bluefox) fix problem if js-controller does not hav the most actual version 

### 0.1.7 (2014-11-09)
* (bluefox) add log pane

### 0.1.6 (2014-11-07)
* (bluefox) fix edit list in configuration

### 0.1.5 (2014-11-03)
* (bluefox) support of tables in edit configuration

### 0.1.4 (2014-11-01)
* (bluefox) update history dialog live (add new values on the fly to history table)

### 0.1.3 (2014-11-01)
* (bluefox) add link to web service of adapter instance

### 0.1.2 (2014-11-01)
* (bluefox) add functions to edit lists in adapter config

### 0.1.1 (2014-10-30)
* (bluefox) support of sendToHost command for adapter config.

### 0.1.0 (2014-10-29)
* (bluefox) update states if some adapter added or deleted. Update states if history enabled or disabled.

### 0.0.19 (2014-10-24)
* (bluefox) fix error with repository edition

### 0.0.18 (2014-10-20)
* (bluefox) fix error with "up to date"

### 0.0.17 (2014-10-19)
* (bluefox) fix delete of adapter

### 0.0.16 (2014-10-19)
* (bluefox) support of certificate list

### 0.0.15 (2014-10-09)
* (bluefox) make possible availableModes for adapter
* (bluefox) add auto changelog
* (bluefox) improve Grunt
* (bluefox) by default enabled.

### 0.0.14
* (bluefox) add repositories editor

### 0.0.13
* (hobbyquaker) gridAdapter style
* (hobbyquaker) moved system settings to dialog

### 0.0.12
* (bluefox) new concept of updates/upgrades

### 0.0.11
* (hobbyquaker) bugfix - slashes in IDs
* (hobbyquaker) bugfix - gridHistory 

### 0.0.10
* (hobbyquaker) more options in dialogHistory
* (hobbyquaker) add enums
* (hobbyquaker) hide not-implemented buttons (add/del object f.e.)
* (hobbyquaker) prepared tab log
* (hobbyquaker) gridAdapters: colors for release state (red = planned, orange = alpha, yellow = beta, green = stable)

### 0.0.9
* (hobbyquaker) history

### 0.0.8
* (hobbyquaker) added column "parent name" to gridStates

### 0.0.7
* (hobbyquaker) prepared enum members
* (hobbyquaker) hide logout button if auth disabled
* (hobbyquaker) refactoring
* (hobbyquaker) fixes

### 0.0.5
* (hobbyquaker) show available version, show update button if not up-to-date
* (hobbyquaker) minor fixes
