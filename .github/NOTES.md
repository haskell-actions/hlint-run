Andreas, 2023-01-03

The file `hlint.json` here is located here by `MATCHER_DEF_PATH` in `hlint-run/src/hlint/index.ts`.
Probably this is a remnant of the migration from https://github.com/rwe/actions-hlint-run,
and this file should reside somewhere else, as local `.github` directories are not supported.
Atm, I am not familiar with this action, so leave things as they are.

Mihai, 2023-09-16

The `hlint.json` file could be moved now after splitting the repos
(https://github.com/haskell/actions/issues/141). Will do this in a separate
commit, but for now not that the paths in the above commit refer to the state
before the repo split.
