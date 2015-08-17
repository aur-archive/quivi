# Maintainer: Brad Conte <b-con@archlinux.us>

pkgname=quivi
pkgver=1.2.1
pkgrel=2
pkgdesc="Image viewer designed to be fast and easy, specialized for comic/manga reading. Supports compressed ZIP and RAR archives."
arch=('i686' 'x86_64')
depends=('wxpython>=2.8.9' 'freeimage' 'unrar')
source=(http://downloads.sourceforge.net/project/$pkgname/$pkgname/$pkgver/$pkgname-$pkgver.tar.gz)
md5sums=('836410c85deae50f6b4a14ed7a9d3e18')
url="http://quivi.sourceforge.net"
license=('MIT')

build() {
	cd $srcdir/$pkgname-$pkgver || exit 1
	
	python2 setup.py install --prefix=/usr --root=$pkgdir
}
