---
title: OneClick Method
---


First, clone the repo
```
git clone https://github.com/notAperson535/OneClick-macOS-Simple-KVM.git
```

- `setup.sh` is for Debian based Linux Repositories like Ubuntu
- `setupArch.sh` is for Arch based Linux Repositories like Manjaro.
- `setupFedora.sh` is for Fedora based Linux Repositories.
- `setupSUSE.sh` is for openSUSE Tumbleweed
- `setupMageia.sh` is for Mageia

Run `./setup.sh` or the correct one depending on your Linux OS to make the VM. Follow the setup steps.

After the script is done, run this command to start the VM:
```
./basic.sh
```

Whenever you want to load up the machine again, run `./basic.sh`, NOT `./setup.sh`. `setup.sh` is only used for first initializing a VM.

## [Now head over to installing macOS for instructions on correctly installing macOS](/docs/installing-macos/)
