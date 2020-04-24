Conferences
===========

A community-curated list of conferences around the world for Android developers.


Adding a conference
-------------------

Send a pull-request which adds a file to the `_conferences/` directory
with a new file representing the conference. The file should be named
with the conference name, the year, and with an `.md` extension (for
example, `my-cool-conference-2016.md`).

The contents of the file should use the following template:
```
---
name: "Droidcon"
website: http://uk.droidcon.com/2015/
location: London, UK
status: Cancelled/Postponed # Optional, will show up in red if provided
online: true                # Optional, for online-only events.

date_start: 2015-10-29
date_end:   2015-10-30

cfp_start: 2015-06-16  # Optional
cfp_end:   2015-07-21  # Optional
cfp_site: http://uk.droidcon.com/2015/lineup-2015/ # Optional, will default to website
---
```

*Note: Do not include the location of the conference in the name. The above conference is often referred to as "Droidcon London", but we will always render the location with the name so it is redundant.*

### Online-only events

For online only events please set `online: true` in the template. They will show up in the _Upcoming_ page as well as in the [Online-only](http://androidstudygroup.github.io/conferences/online.html) page.

Please use the `status:` field only for cancellation or postponement as it will show up in red in the website.

Running locally
---------------
![Build Jekyll Pages](https://github.com/AndroidStudyGroup/conferences/workflows/Build%20Jekyll%20Pages/badge.svg)

```
bundle install --path vendor/bundle
bundle exec jekyll serve
```

Once running the site can be opened at http://localhost:4000.


License
-------

All content is [CC0][1].


 [1]: https://creativecommons.org/publicdomain/zero/1.0/
