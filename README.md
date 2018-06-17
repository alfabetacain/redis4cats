fs2-redis
=========

Stream-based client built on top of [Fs2](https://functional-streams-for-scala.github.io/fs2/) and the async java client [Lettuce](https://lettuce.io/).

:warning: This project is under development and only includes a limited set of features :warning:

- [x] Safe connection management.
- [x] `PubSub` implemented on top of `fs2` streams.
- [x] `Streams` (Redis 5.0) experimental API, subject to changes (WIP).
      + Consumer Groups are yet not implemented.
      + Support for `XREAD`, `XADD` and high-level stream combinators `latest` and `append`.
- [x] `Basic Commands` such as `get`, `set`, `del`, `expire`.

Other features are not considered at the moment but PRs and suggestions are very welcome.

## LICENSE

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this project except in compliance with
the License. You may obtain a copy of the License at http://www.apache.org/licenses/LICENSE-2.0.

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an
"AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific
language governing permissions and limitations under the License.