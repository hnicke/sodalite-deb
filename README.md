# .deb packaging scripts for sodalite

This repo contains the necessary scripts to bundle [sodalite](https://www.github.com/hnicke/sodalite) as a .deb package.

#### HOWTO
```bash
./package 0.13.3 3
```
..will bundle the sodalite release v0.13.3 into the deb package `sodalite_0.13.3` with package revision 3.

Remember to keep the [changelog](DEBIAN/changelog) up-to-date.

