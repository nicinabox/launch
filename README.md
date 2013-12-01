# launch

Launch web services from the command line.

## Setup

1. Clone the repo
2. Run installer in repo: `sh install`
3. Edit `.launchrc` in your home directory

## Example
```
{
  "host": "tower.local",
  "services": {
    "unraid": ":81",
    "unmenu": ":8080",
    "boxcar": ":3000",
    "plex": ":32400/web",
    "transmission": ":9091"
  },
  "aliases": {
    "": "unraid",
    "tr": "transmission"
  }
}
```
