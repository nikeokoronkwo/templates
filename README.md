# Templates

Problem: Whenever I want to start a project in a given language, I want to make sure certain things are done right from the start, including CI, testing, benchmarking, and more, and I tend to make mistakes and mix up sometimes. 

This repo is for me to be able to get starting points for my applications, with a combination of guides and reasons for specific stuff. Some are representative and derived from applications I have/currently am working on, while some are extras I got when doing research.

## Format

For the most part, the format would either just be `<lang>/` or `<lang>/<application>/` (i.e. `go/server/`, or `dart/`). There may be some shared features amongst them

## Monorepos

Monorepo setups where possible would have some of the CI features duplicated across each package, with the addition of a `on._.paths` to glob for only the package's affected paths. The release cycle may differ between applications, so one sample may be provided. 
