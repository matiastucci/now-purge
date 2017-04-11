# now-purge [![Version](https://img.shields.io/npm/v/now-purge.svg)](https://www.npmjs.com/package/now-purge)

> Remove [now](https://zeit.co/now) deployments without an alias

<p align="center">
  <img src="example.png" width="373" height="266" alt="example"/>
</p>

## CLI

### Installation

```bash
npm install -g now-purge
```

### Usage
```bash
now-purge <command> [options]

Commands:
  t  now token
  n  name in package.json or now.json to filter your deployments

Options:
  -h, --help     Show help                                             [boolean]
  -v, --version  Show version number                                   [boolean]
```

## As a package

### Installation

```bash
npm install now-purge --save
```

### Usage

```javascript
const nowPurge = require('now-purge')

// optional config parameters
const config = {
  token: 'YOUR_NOW_TOKEN',
  deploymentName: 'test'
}

nowPurge(config)
```
