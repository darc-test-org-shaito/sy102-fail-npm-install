# sy102-fail-npm-install

DARC test fixture for the SY-1.02 scan. Expected result: `fail` with the short
summary "Unfrozen CI installs". The lockfile is present; `ci.yml` runs a plain
`npm install`, which never freezes.
