# Maintainer: Gonzalo Ciruelos <comp.gonzalo@gmail.com> 

pkgname=maggot
_gitname=maggot
pkgver=0.0.2
pkgrel=2
pkgdesc="A simple snake game written in C"
arch=('i686' 'x86_64')
url="https://github.com/falziots/maggot"
license=('GPLv2')
depends=('pacman')
makedepends=('git' 'gcc')
source=('git://github.com/falziots/maggot.git')
# Because the sources are not static, skip Git checksum:
md5sums=('SKIP')

package() {
  cd $_gitname
  make
  make install
}
