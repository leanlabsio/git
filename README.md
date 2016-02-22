# Git builder container

Docker git executable container.

### Usage

```bash
docker run --rm \
  -v `pwd`:/`pwd` \
  -w `pwd` \
  leanlabs/git clone https://github.com/leanlabsio/git.git
```
