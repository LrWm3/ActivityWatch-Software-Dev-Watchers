# ActivityWatch watchers

Experimental ActivityWatch watchers meant to capture all work a software developer might do.

Currently none of the watchers are implemented.

## Watchers

| watcher | description | status |
|--|--|--|
| [i](./src/watchers/i.py) | Enter a memo into activity watch from the terminal. Inspired by [i](https://github.com/kungfusheep/i)| unimplemented | 
| [git-commits](./src/watchers/git-commits.py) | Records git-commits as they are made to ActivityWatch | unimplemented |
| [jira](./src/watchers/jira.py) | Records activity in Jira | unimplemented |
| [confluence](./src/watchers/confluence.py) | Records activity in confluence | unimplmented |
| [slack](./src/watchers/slack.py) | Records activity in Slack | unimplmented |

### Complementary watchers

Other watchers which are intended to be used with this one.

Search them up and add as links later.

- the window one
- the browser one
- the vscode one
- the intellij one
- the pycharm one
- the vim one

## Setting up ActivityWatch to collect mobile & browser activity

For android users, we can set up ActivityWatch on mobile. If we then use a mobile Firefox fork like Fennec, we can install ActivityWatch from a custom collection onto our mobile devices.

### To install ActivityWatch in fennec

Open Fennec, go into the settings, click "about Fennec". Tap the Fennec logo 5 times. Now go back and there is a custom add-on collection option. Open it, add '18120000' and 'fennec-collections'. Click OK.

ActivityWatch may then be installed onto your phone for collecting mobile browsing statistics.
