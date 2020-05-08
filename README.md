# Bluetent CircleCI Utils
Provides an orb for common needs among PropertyBrands/Bluetent developers.

## Commands

 - bt-utils/parse-commit-message: Writes variables provided by "tags" in git commit messages. Any items formed like
  `[btenv FOO=bar]` will be written to `./btenv.sh`. That file may be accessed via `source` to import context variables
  needed to influence the behavior of builds.
  
## Build/Update the Orb

```bash
circleci orb publish src/orb.yml bluetent-sandbox/bt-utils@dev:0.0.3
```
 
