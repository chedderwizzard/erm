
# Maintainer: chedderwizzard <chedderwizzard@gmail.com>
pkgname=erm
pkgver=1
pkgrel=1
epoch=
pkgdesc="stupid little bash script that prints out nerd emoji ascii"
arch=('x86_64')
url="https://github.com/chedderwizzard/erm"
license=('none')
depends=('bash' 'gzip')
makedepends=('git')
source=("git+https://github.com/chedderwizzard/erm")
sha256sums=('SKIP')

package() {
	cd "$pkgname"
	install -Dm755 ./erm "$pkgdir/usr/bin/erm"
}
