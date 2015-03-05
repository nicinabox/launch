# launch

Launch web services from the command line.

## Usage

```bash
$ launch SERVICE
```

## Setup

1. Clone the repo
2. Run installer in repo: `sh install`
3. Edit `.launchrc` in your home directory

Specify a port for each service starting with a colon. You may alternatively specify a full hostname with its own port. See `transmission` for an example below.

## Example
```
{
  "host": "10.0.0.2",
  "services": {
    "plex": ":32400/web",
    "transmission": ":9091",
    "router": "10.0.0.1",
    "camera": "10.0.0.8"
  },
  "aliases": {
    "torrents": "transmission",
    "orwell": "camera"
  }
}
```
