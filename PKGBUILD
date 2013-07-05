#Maintainer: nixalot <nixalot at nixalot dot com>
pkgname=aurdownload
pkgver=1.0
pkgrel=2
pkgdesc='Retrieve and extract PKGBUILDS from the AUR'
arch=(any)
license=(GPL3)
url="https://github.com/nixalot/$pkgname"
depends=('python' 'python-requests')
source=(
  ${pkgname}_${pkgver}.zip::https://github.com/nixalot/${pkgname}/archive/master.zip
)

md5sums=('d8c62c601b08e46bf3cafbe3bd9a1ecb')
sha1sums=('cdb2484b802babe136839dfa3ed55e88b430fdee')
sha256sums=('91afeed8015e8346c4320258a9dd02ab5680992b03e5d238c55b795178dc8a4c')
sha384sums=('42f83323f578152ebdde3ebb414f17185796977ed2ae339b3cbaa28c193e536d3dfd4c59c4cdfbbb7ddcddb343bceb92')
sha512sums=('8c349fcc4ffff9da0930e026fc0b212c1709c6fccef28035dc1c7a49d63bbb01f270ab380c84f524bb53dd474e17acb94ed7a7fdb02354c399f3a90c5865fd34')

package ()
{
  install -D -m755 "$srcdir/$pkgname-master/${pkgname}.py" "$pkgdir/usr/bin/$pkgname"
}

# vim: set ts=2 sw=2 et:
