
# MacHome Infrastructure Documentation

This repository contains a static site deployed to [https://jeffrey-p-mcateer.github.io/machome-infra-page/](https://jeffrey-p-mcateer.github.io/machome-infra-page/) and [http://machome.local](http://machome.local) which documents our printers,
file shares, TV controls, and other digital infrastructure at home.


## Deployment

Github Pages deploys to their domain, and internally you can
rsync to a mount point like so:

```bash
rsync -av --progress --exclude '.git/*' /j/proj/machome-infra-page/ /mnt/machome/web/
```

