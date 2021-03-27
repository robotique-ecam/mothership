### Mothership - Debian Packages Repository

*Inspired by the work of [assafmo](https://assafmo.github.io/2019/05/02/ppa-repo-hosted-on-github.html)*


#### Requirements

You need to be running Debian Buster ARM64 (raspbian arm64 included)


#### Setup

To add this repository, use :
```
curl -so /etc/apt/sources.list.d/robotique-ecam.list https://funtech-makers.ecam.fr/mothership/packages.list
sudo apt update
```

You're all set, happy robotics