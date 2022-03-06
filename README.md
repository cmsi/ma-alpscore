<img src="https://ma.issp.u-tokyo.ac.jp/wp-content/themes/materiapps/images/materiapps.svg" width=150>

# MateriApps Debian Package: ALPS Core

### ALPS Core: Applications and Libraries for Physics Simulations Core libraries

The ALPS Core libraries aim to provide a set of well tested, robust, and standardized components for numerical simulations of condensed matter systems, in particular systems with strongly correlated electrons. They consist of a set of components that are used in tate of the art high performance codes. The ALPS Core libraries are a spinoff of the ALPS libraries available from alps.comp-phys.org.

### Version

* 2.3.0-rc.1

### Provided packages

* libalpscore - shared libraries
* libalpscore-dev - headers and cmake files
* alpscore-doc - documentation
* alpscore-tutorials - tutorials

### Target distributions and architectures

* Debian bullseye (amd64, arm64) / buster (amd64, arm64, i386) / stretch (amd64, arm64, i386)
* Ubuntu focal (amd64, arm64) / bionic (amd64, arm64)

### For users

* How to install ALPS Core

  1. Add MateriApps LIVE! apt repository to Debian [[English](https://github.com/cmsi/MateriAppsLive/wiki/UsingMateriAppsInDebian-en)][[日本語](https://github.com/cmsi/MateriAppsLive/wiki/UsingMateriAppsInDebian)]

  2. Install ALPS Core runtime

     ```
     suto apt-get install libalpscore
     ```

  3. For developing software using ALPS Core

     ```
     suto apt-get install libalpscore-dev
     ```

  3. Documentation and tutorial

     ```
     suto apt-get install alpscore-doc alpscore-tutorials
     ```

### Links
  
* [MateriApps LIVE! Home Page](http://cmsi.github.io/MateriAppsLive/)
* [MateriApps LIVE! Forum](https://github.com/cmsi/MateriAppsLive-forum/wiki) (Users Forum)
* [MateriApps LIVE! Wiki](https://github.com/cmsi/MateriAppsLive/wiki) (Documents and FAQ)
* [MateriApps LIVE!](https://ma.issp.u-tokyo.ac.jp/en/app/275) on MateriApps
