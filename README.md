# APS Conecta Files Full Text Search

Maintenance fork of [Nextcloud Files Full Text Search](https://github.com/nextcloud/files_fulltextsearch) for APS Conecta on Nextcloud 34. This is an independent fork; the original licence and attribution remain in this repository.

The source includes the upstream [stable34 UID fix](https://github.com/nextcloud/files_fulltextsearch/pull/463), commit `26bd54ddcec5e26b1e5e905d7417910d2a6a0baf`. The app retains the `files_fulltextsearch` identity and upstream interface. The APS release workflow builds the settings bundle, copies the unchanged legacy script from `src/legacy-files.js`, and publishes the four signed release assets through the shared app publisher.

<!--
  - SPDX-FileCopyrightText: 2017 Nextcloud GmbH and Nextcloud contributors
  - SPDX-License-Identifier: AGPL-3.0-or-later
-->
# Full text search - Files

[![REUSE status](https://api.reuse.software/badge/github.com/nextcloud/files_fulltextsearch)](https://api.reuse.software/info/github.com/nextcloud/files_fulltextsearch)
[![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/nextcloud/files_fulltextsearch/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/nextcloud/files_fulltextsearch/?branch=master)

_Full text search - Files_ is an extension app to the _Full text search_ framework

It allows you to index the content of your users' files.



### Documentation

[Can be found on the Wiki](https://github.com/nextcloud/files_fulltextsearch/wiki)

