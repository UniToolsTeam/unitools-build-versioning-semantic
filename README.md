# UniTools Build Versioning Semantic
Build steps to set a project version based on the [SemVer](https://semver.org) approach.

# Features
- Set MAJOR.MINOR.BUILD.REVISION using a pre build steps

# Dependencies
- [UniTools Build](https://github.com/UniToolsTeam/unitools-build)

# Installation

### Download
[Latest Releases](../../releases/latest)

### Unity Package Manager (UPM)

> You will need to have git installed and set in your system PATH.
> Check package [dependencies](https://github.com/UniToolsTeam/unitools-build-versioning-semantic/blob/master/package.json)

Add the following to `Packages/manifest.json` where x.x.x the version (tag) check [Latest Releases](../../releases/latest):

```
{
  "dependencies": {
    "com.unitools.build": "https://github.com/UniToolsTeam/unitools-build.git#x.x.x",
    "com.unitools.versioning.semantic": "https://github.com/UniToolsTeam/unitools-build-versioning-semantic.git#x.x.x",
    "...": "..."
  }
}
```

# Getting Started
In progress..
