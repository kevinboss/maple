# Contributing

## Prerequisites

- [PowerShell](https://learn.microsoft.com/en-us/powershell/scripting/install/installing-powershell)
  5.1 or later
- [Scoop](https://scoop.sh/)
- [Pester](https://pester.dev/) (`>= 5.2.0`)
- [BuildHelpers](https://www.powershellgallery.com/packages/BuildHelpers)
  (`>= 2.0.1`)

## Running tests

After editing or adding a manifest in [`bucket/`](bucket/), run the test suite:

```powershell
.\bin\test.ps1
```

If `scoop` is not installed locally, set `$env:SCOOP_HOME` to a local Scoop
checkout before running the tests.

## Pull requests

Open a pull request once all tests pass.
