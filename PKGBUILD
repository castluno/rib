pkgname=rib
pkgver=1.0
pkgrel=1
pkgdesc='a simple utility for running applications independently of the console. by castluno'
arch=('any')
license=('MIT')
depends=('bash')
source=('main.sh')
sha256sums=('SKIP')

package() {
    install -Dm755 "$srcdir/main.sh" "$pkgdir/usr/bin/rib"
}
