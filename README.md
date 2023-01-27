AHA! Website
==

[![deployment](https://github.com/AustinHackers/austinhackers.github.io/actions/workflows/pages/pages-build-deployment/badge.svg?branch=main)](https://github.com/AustinHackers/austinhackers.github.io/actions/workflows/pages/pages-build-deployment)

This github repository contains the [website](http://takeonme.org) for the Austin Hackers Anonymous group. Someone should really update it to make it suck less.

## Local Dev

If you want to make changes and actually test them locally, a [Rakefile](https://github.com/AustinHackers/austinhackers.github.io/blob/main/Rakefile) is included to run the local jekyll server for testing.

```bundle exec rake```

This will launch a local webserver running on http://127.0.0.1:4000/ that auto-updates the test site live when changes are detected on disk. 
