pkgname=untmp
pkgver=1.1.0
pkgrel=1
pkgdesc="Take an tmplinux container and make it no longer temporary"
arch=('any')
url="https://github.com/tmplinux/untmp"
license=('MIT')
depends=('python3' 'squashfs-tools')
makedepends=()
source=('untmp' 'qboot')
sha256sums=('SKIP' 'SKIP')

package() {
    install -Dm755 untmp "$pkgdir/usr/bin/untmp"
    install -Dm755 qboot "$pkgdir/usr/bin/qboot"
}
