# now-purge

> Utility to remove deployments without alias

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
  n  now.json name to filter your deployments

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
