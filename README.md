# launch

Launch web services from the command line.

## Setup

1. Clone the repo
2. Run installer in repo: `sh install`
3. Edit `.launchrc` in your home directory

Specify a port for each service starting with a colon. You may alternatively specify a full hostname with its own port. See `transmission` for an example below.

## Example
```
{
  "host": "tower.local",
  "services": {
    "unraid": ":81",
    "unmenu": ":8080",
    "boxcar": ":3000",
    "plex": ":32400/web",
    "transmission": "example.com:9091"
  },
  "aliases": {
    "": "unraid",
    "tr": "transmission"
  }
}
```
