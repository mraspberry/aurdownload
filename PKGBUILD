#Maintainer: nixalot <nixalot at nixalot dot com>
pkgname=aurget
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

md5sums=('f80f547ce6f5a38166db9322721cd35c')
sha1sums=('2dc1b9ba935f5afda4422b1ce38235efc3ac6429')
sha512sums=('4a3f0400d2ad0d66b3d7e23aa7f118b1565f6fa635c1a83ea8281fdb09db134cd78a235301063693e1300b38e2c237f0e0b741c8b3ddc90e912b3ad26cf9a6a9')

package ()
{
  install -D -m755 "$srcdir/$pkgname-master/${pkgname}.py" "$pkgdir/usr/bin/$pkgname"
}

# vim: set ts=2 sw=2 et:
