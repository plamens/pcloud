# Maintainer: Plamen Semerdzhiev <pl.semerdzhiev@gmail.com>
pkgname=pcloud-git
pkgver=2.0.0
pkgrel=1
pkgdesc="pCloud Drive client"
arch=('i686', 'x86_64')
url="http://pcloud.com"
license=('unknown')
depends=()
makedepends=('tar')
provides=('psyncgui')
conflicts=()
replaces=()
source="git://github.com/plamens/pcloud.git"
md5sums=('SKIP')

package() {
	tar -xf data.tar.gz
	mkdir "$pkgdir"/usr
	mkdir "$pkgdir"/usr/bin
	cp usr/bin/psyncgui "$pkgdir"/usr/bin/psyncgui
}
