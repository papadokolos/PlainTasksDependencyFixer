# Introduction

By installing this package, PlainTasks is able to import dateutil as expected (see Note below).

# Note

Given that you use the new Package Control channel (https://packages.sublimetext.io/channel.json) instead of the default one. See: https://packages.sublimetext.io/about. This is because the default channel doesn't support dateutil's latest release tag `2.9.0.post0` which adds back Python 3.3 support.

# Background

Since [commit 6324c69](https://github.com/packagecontrol/channel/commit/6324c697c53004f6cb8cd36c3374672136a00039) on May 13 2025, "dateutil" library's base URL was changed from "https://github.com/vovkkk/sublime-dateutil" to the official "https://pypi.org/project/python-dateutil".
This breaks [PlainTasks](https://github.com/aziz/PlainTasks/) package, and all Python 3.3 based packages.
See here for more details: [https://github.com/packagecontrol/thecrawl/issues/341]()


