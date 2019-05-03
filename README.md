# Python

🐳 FSP Network Gen2 Server Infrastructure - Python

[![MicroBadger Size](https://img.shields.io/microbadger/image-size/fspnetwork/python.svg?style=flat-square)](https://microbadger.com/#/images/fspnetwork/python)
[![Docker Automated build](https://img.shields.io/docker/automated/fspnetwork/python.svg?style=flat-square)](https://hub.docker.com/r/fspnetwork/python/)
[![LICENSE](https://img.shields.io/badge/license-Anti%20996-blue.svg?style=flat-square)](https://github.com/996icu/996.ICU/blob/master/LICENSE)
[![996.icu](https://img.shields.io/badge/link-996.icu-red.svg?style=flat-square)](https://996.icu)


## Supported tags

- [`latest`, `3.7`, `3.7.2` (Dockerfile)](https://github.com/FSPNET/Python/blob/master/3.7/Dockerfile)
- [`development`, `development` (development)](https://github.com/FSPNET/Python/blob/master/development/Dockerfile)

**Notes:**
- `development` tag will always use the latest version based upstream.

## Details

- Based on [FSPNetwork/Infrastructure](https://github.com/FSPNET/c).

## Usage

Use like you would any other base image:

```dockerfile
FROM fspnetwork/python
...
ENTRYPOINT ["python", "/app.py"]
```

## LICENSE

The code in this repository, unless otherwise noted, is [Anti-996](LICENSE) licensed. See the LICENSE file in this repository.

## More

- Some code based on [jfloff/alpine-python](https://github.com/jfloff/alpine-python)