<img src="https://ma.issp.u-tokyo.ac.jp/wp-content/themes/materiapps/images/materiapps.svg" width=150>

# MateriApps Debian Package: ALPS Core

### ALPS Core: Applications and Libraries for Physics Simulations Core libraries

The ALPS Core libraries aim to provide a set of well tested, robust, and standardized components for numerical simulations of condensed matter systems, in particular systems with strongly correlated electrons. They consist of a set of components that are used in tate of the art high performance codes. The ALPS Core libraries are a spinoff of the ALPS libraries available from alps.comp-phys.org.

### Version

* 2.2.0-1 (01 Nov 2018)

### Provided packages

* libalpscore - shared libraries
* libalpscore-dev - headers and cmake files
* alpscore-doc - documentation
* alpscore-tutorials - tutorials

### Target distributions and architectures

* Debian stretch (amd64)

### For users

* How to install ALPS Core

  1. Add MateriApps LIVE! apt repository to Debian [[English](https://github.com/cmsi/MateriAppsLive/wiki/UsingMateriAppsInDebian-en)][[日本語](https://github.com/cmsi/MateriAppsLive/wiki/UsingMateriAppsInDebian)]

  2. Install ALPS Core runtime

     ```
     suto apt-get install libalpscore
     ```

  3. For developing software using ALPS Core

     ```
     suto apt-get install libalpscore-dev alpscore-doc alpscore-tutorials
     ```

### For developers

* How to prepare original source tarball

  ```
  VERSION=x.x.x
  wget https://github.com/ALPSCore/ALPSCore/archive/v$VERSION.tar.gz
  tar zxvf v$VERSION.tar.gz
  mv -f ALPSCore-$VERSION alpscore_$VERSION
  tar zcvf alpscore_$VERSION.orig.tar.gz alpscore_$VERSION
  rm -rf v$VERSION.tar.gz* alpscore_$VERSION
  ```
  
### Links
  
* [MateriApps LIVE! Home Page](http://cmsi.github.io/MateriAppsLive/)
* [MateriApps LIVE! Forum](https://github.com/cmsi/MateriAppsLive-forum/wiki) (Users Forum)
* [MateriApps LIVE! Wiki](https://github.com/cmsi/MateriAppsLive/wiki) (Documents and FAQ)
* [MateriApps LIVE!](https://ma.issp.u-tokyo.ac.jp/en/app/275) on MateriApps

