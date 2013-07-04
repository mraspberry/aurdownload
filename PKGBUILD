#Maintainer: nixalot <nixalot at nixalot dot com>
pkgname=aurdownload
pkgver=1.0
pkgrel=1
pkgdesc='Retrieve and extract PKGBUILDS from the AUR'
arch=(any)
license=(GPL3)
url="https://github.com/nixalot/$pkgname"
depends=('python' 'python-requests')
source=(
  ${pkgname}_${pkgver}.zip::https://github.com/nixalot/${pkgname}/archive/master.zip
)

md5sums=('57246d20e6c38064f22294ed2bee5901')
sha1sums=('ce6833600a32c4c937e54c729bff57a5018581c4')
sha512sums=('63c2c149df9d5a185f28d351db7072ea8554b7cc3f5454e5aa38653efcb5684dd62665ce03e8728ef08f0681952d317a4fbb7e4aef3311639b9e7fec78a09fdc')

package ()
{
  install -D -m755 "$srcdir/$pkgname-master/${pkgname}.py" "$pkgdir/usr/bin/$pkgname"
}

# vim: set ts=2 sw=2 et:
