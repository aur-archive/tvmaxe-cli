# Maintainer: nkn <rstancuna at gmail dot com>
pkgname=tvmaxe-cli
pkgver=0.3.4
pkgrel=2
pkgdesc="tv-maxe in cli"
arch=('any')
url=http://linuxfans.ro/viewtopic.php?f=34&t=169
license=('GPL')
depends=('mplayer' 'sopcast')
optdepends=("axel: Download accelerator")
source=(http://content.wuala.com/contents/nknwn6666/tvmaxe-cli/$pkgname-$pkgver-$pkgrel)
md5sums=('4ee781779529fc9fc648e05caaa98ea6')

package() {
	install -d $pkgdir/usr/bin
	install -m 755 $srcdir/$pkgname-$pkgver-$pkgrel $pkgdir/usr/bin/$pkgname
}

