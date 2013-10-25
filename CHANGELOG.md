### 0.2.0 / TODO

* Allow dots in pathnames, but block path traversal attempts
* Respond with `304` for conditional `GET` instead of `412`
* Only use `ETag`/`If-Match`/`If-None-Match` for versioning, not `Last-Modified`
* Add a `ca` option to the HTTPS config
* Storage engines now take versions as timestamps, not Dates
* User accounts now require an email address
* Fix some locking problems in the filesystem backend
* Add nice HTML views for home page, sign-up form, error pages

### 0.1.0 / 2013-02-25

* Initial release with working protocol usable by clients
* Filesystem and Redis backends