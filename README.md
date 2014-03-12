# GAE pytz - modified

A fork of pytz which works on [Google App Engine](https://developers.google.com/appengine/).

Reintroduced capability to work without GAE and keeping the advantage of zipped zoneinfo.zip.

Has been written to overcome the nasty behaviour (very slow start) when packed with py2exe.

Based on [http://appengine-cookbook.appspot.com/recipe/caching-pytz-helper/](http://appengine-cookbook.appspot.com/recipe/caching-pytz-helper/) but modified so that it can be imported normally with `import pytz`.
