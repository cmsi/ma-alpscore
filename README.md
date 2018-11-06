# ma-alpscore

## How to prepare source files for alpscore package

1. ソースファイルの準備 (ホスト上で)

        VERSION=2.2.0
        cd $HOME/vagrant/data/src
        wget https://github.com/ALPSCore/ALPSCore/archive/v$VERSION.tar.gz
        tar zxvf v$VERSION.tar.gz
        mv -f ALPSCore-$VERSION alpscore_$VERSION
        tar zcvf alpscore_$VERSION.orig.tar.gz alpscore_$VERSION
        rm -rf v$VERSION.tar.gz* alpscore_$VERSION
