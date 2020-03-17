# CircleCI

## Configure Github

```
- run:
    name: _something special and unique_
    command: |
      bash <(curl -s https://raw.githubusercontent.com/varnish/circleci/master/scripts/github_config.sh)
```
