# LowDB Middleware

Forked version of [JSON Server](https://github.com/typicode/json-server). This package is intended to used as middleware from within an ExpressJS application.

## Roadmap

- [x] Update packages to latest versions
- [x] Drop CLI support
- [ ] Rewrite code base to use ES6 style code ie: import fs from 'fs
- [ ] Basic Auth plugin
- [ ] Database management screens
- [ ] Add dynamic databases routes
- [ ] Use FileAsync via async/await 
- [ ] Configurable setup
- [ ] Snapshots / Restore

## Fixes / Enhancements 

The following PRs were implemented from json-server repository

- [x] Fix bug with null expand reference. [PR640](https://github.com/typicode/json-server/pull/640/commits)
- [x] Add `_contains` operation [PR691](https://github.com/typicode/json-server/pull/691/commits)
- [x] Add `_attr` option to reduce query context [PR558](https://github.com/typicode/json-server/pull/558/commits)
- [x] Add `_flatten` option to flatten nested objects
- [x] Add `_keys` option to reduce returned results

Documenation coming....
