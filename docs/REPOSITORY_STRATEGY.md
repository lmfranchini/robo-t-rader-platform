# Repository Strategy

## Recommended approach

Use this repository as the canonical submission repo.

Use the module repositories below as supporting evidence only.

## Supporting repositories

- `EpicAtlas`
  Canonical support repo, currently private
- `marketdatahub`
  Canonical support repo, currently private
- `edge-discovery-engine`
  Support repo, currently private
- `graphify`
  Support repo, currently private
- `robo-t-rader_prod`
  Support repo, currently private
- `robo-t-rader_naked`
  Support repo, currently private

## Why this structure works

It gives judges:

- one repo to understand the project
- enough evidence to validate Build Week work
- a clean hierarchy instead of a fragmented story

## Current verified repository facts

Verified from this environment:

- `robo-t-rader-platform` is publicly reachable at `https://github.com/lmfranchini/robo-t-rader-platform`
- `_work/EpicAtlas-param-pilot` points to `https://github.com/lmfranchini/EpicAtlas.git`

Satellite repositories are currently treated as private support modules from the competition point of view.

Not publicly reachable at verification time from this environment:

- `EpicAtlas`
- `marketdatahub`
- `robo-t-rader_prod`
- `robo-t-rader_naked`
- `graphify`
- `edge-discovery-engine`

Implication:

- the safest immediate public anchor is `robo-t-rader-platform`
- supporting repos do not need to be public if the public submission repo explains their role clearly
- Devpost should use the public canonical repo as the front door, and mention private support modules narratively unless you later decide to expose them

## Do not do this

- do not submit only the production runtime repo
- do not force judges to browse multiple repos without a map
- do not pretend every historical component was built during Build Week
