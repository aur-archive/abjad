# Maintainer: Bernardo Barros <bbarros@xsounds.org>

pkgname=abjad
_realname=Abjad
pkgver=2.10
pkgrel=1
pkgdesc="a python program for formalized score control and music composition"
url="http://www.projectabjad.org"
arch=(any)
license=('GPL')
depends=('python2>=2.7' 'lilypond')
makedepends=('python2-distribute')
conflicts=('abjad-svn')
options=(!emptydirs)
source=("http://pypi.python.org/packages/source/A/Abjad/$_realname-$pkgver.tar.gz")

build() {
  cd $srcdir/$_realname-$pkgver
  python2 setup.py install --root=$pkgdir/ --optimize=1
}

md5sums=('d12323e0bba8a005eeee251bb915247d')
