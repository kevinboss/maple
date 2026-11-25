<h1 align="center">maple</h1>

<p align="center">
  A <a href="https://scoop.sh/">Scoop</a> bucket of tools developed or loved by <a href="https://github.com/kevinboss">@kevinboss</a>.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/PowerShell-5391FE?logo=powershell&logoColor=white" alt="PowerShell">
  <a href="https://github.com/kevinboss/maple/actions/workflows/ci.yml"><img src="https://img.shields.io/github/actions/workflow/status/kevinboss/maple/ci.yml?label=CI" alt="CI"></a>
  <a href="LICENSE"><img src="https://img.shields.io/github/license/kevinboss/maple" alt="License"></a>
</p>

maple is a [Scoop](https://scoop.sh/) bucket of Windows tools maintained by
[@kevinboss](https://github.com/kevinboss). Each package lives as a JSON
manifest in [`bucket/`](bucket/) and is checked for new releases on a schedule.

## Install

```powershell
scoop bucket add maple 'https://github.com/kevinboss/maple.git'
```

Replace `scoop` with `shovel` if you use Shovel.

## Usage

Install or update any app from [`bucket/`](bucket/), such as `port`:

```powershell
scoop install maple/port  # install an app from the bucket
scoop update              # update the bucket
scoop update maple/port   # update an installed app
```

## How to contribute

Add or edit manifests in [`bucket/`](bucket/) and open a pull request. See
[CONTRIBUTING.md](CONTRIBUTING.md) for prerequisites and running tests.
