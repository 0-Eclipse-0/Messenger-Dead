# Messenger || Do Not Use

>**This program contains a serious lack of input sanitization making it higly vulnerable to Stored XSS as well as SQL injection protection in the authentication if >memory sevrves me correctly (I haven't run this in 5 years and no longer deal with rails so I don't know for sure) so it should only be deployed in a secure >environment for security practice purposes (Not that anyone is/was ever going to actually deploy this.**

????????????????????????????????????????????????????????????????????????????????????????????????????????????

A simple anonymous messaging system in rails.

### Information
| Name             | Desription            |
|------------------|-----------------------|
| Name:            | Messenger             |
| Creator:         | Eclipse (0-Eclipse-0) |
| Creation Date:   | April 10th, 2016      |
| Current Version: | v1.0.3beta            |
| Language:        | Ruby                  |
| Requirements:    | Rails v4.2.5          |


### How to use
1. Install rails and ruby.
2. Go to the project's root directory in your command prompt.
3. Type 'bundle install'
4. Type 'rails server'
5. Open a browser and go to http://localhost:3000


### Reset Chat and User list
1. Delete 'development.sqlite3' and type 'rake db:reset' in the command prompt whilst in the root directory.
2. Reset Chat Button (Soon to come)

 
### Browser Stability
|       | Opera    | Chrome | Firefox | Internet Explorer | Chrome Canary |
|-------|----------|--------|---------|-------------------|---------------|
| 1.0   | Unstable | Stable | Stable  | Unstable          | Stable        |
| 1.0.2 | Stable   | Stable | Stable  | Unstable          | Stable        |
| 1.0.3 | Stable   | Stable | Stable  | Partially Stable  | Stable        |


### Status
[![Travis Build](https://travis-ci.org/ImagicalMine/ImagicalMine.svg)](https://travis-ci.org/0-Eclipse-0/Messenger)
[![wercker status](https://app.wercker.com/status/75529ee7d55b706c388e7a66bf751d7e/m "wercker status")](https://app.wercker.com/project/bykey/75529ee7d55b706c388e7a66bf751d7e)
[![wercker status](https://app.wercker.com/status/75529ee7d55b706c388e7a66bf751d7e/s "wercker status")](https://app.wercker.com/project/bykey/75529ee7d55b706c388e7a66bf751d7e)


### Commit Graph
[![Throughput Graph](https://graphs.waffle.io/0-Eclipse-0/Messenger/throughput.svg)](https://waffle.io/0-Eclipse-0/Messenger/metrics/throughput)


### Badges
[![Gitter](https://badges.gitter.im/0-Eclipse-0/Messenger.svg)](https://gitter.im/0-Eclipse-0/Messenger?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)
[![Stories in Ready](https://badge.waffle.io/0-Eclipse-0/Messenger.png?label=ready&title=Ready)](https://waffle.io/0-Eclipse-0/Messenger)
[![Codeship](https://codeship.com/projects/c3c52960-ec9b-0133-6d00-56fc93ede3cf/status?branch=master)](https://codeship.com/projects/148265/status?branch=master)
[![GitHub version](https://badge.fury.io/gh/boennemann%2Fbadges.svg)](http://badge.fury.io/gh/boennemann%2Fbadges)
