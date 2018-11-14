# MateriApp Debian Package: ALPSCore

### ALPSCore: Applications and Libraries for Physics Simulations Core libraries

The ALPS Core libraries aim to provide a set of well tested, robust, and standardized components for numerical simulations of condensed matter systems, in particular systems with strongly correlated electrons. They consist of a set of components that are used in tate of the art high performance codes. The ALPSCore libraries are a spinoff of the ALPS libraries available from alps.comp-phys.org.

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

* How to install ALPSCore

  1. Add MateriApps apt repository to Debian [[English](https://github.com/cmsi/MateriAppsLive/wiki/UsingMateriAppsInDebian-en)][[日本語](https://github.com/cmsi/MateriAppsLive/wiki/UsingMateriAppsInDebian)]

  2. Install ALPSCore runtime

     ```
     suto apt-get install libalpscore
     ```

  3. For developing software using ALPSCore

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
* [MateriApps LIVE! Forum](MateriApps LIVE! Forum) (Users Forum)
* [MateriApps LIVE! Wiki](MateriApps LIVE! Wiki) (Documents and FAQ)
* [MateriApps LIVE!](MateriApps LIVE!) on MateriApps

