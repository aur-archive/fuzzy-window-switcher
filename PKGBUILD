# Maintainer: Edoardo Maria Elidoro <edoardo.elidoro@gmail.com>

pkgname=fuzzy-window-switcher
pkgver=1
pkgrel=1
pkgdesc="A fuzzy window switcher inspired by Sublime Text's Ctrl+P."
arch=('any')
url="https://github.com/XCMer/fuzzy-window-switcher"
license=('GPL')
depends=(gtk3 libkeybinder3)
source=(https://raw.github.com/XCMer/fuzzy-window-switcher/master/fuzzy-windows)
md5sums=('ca33eeb4592031ce27070d8905ad969b')

package() {
  install -Dm 744 "$srcdir/fuzzy-windows" "$pkgdir/usr/local/bin/fuzzy-windows"
  }
