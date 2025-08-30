# Maintainer: malta-rf <seuemail@exemplo.com>

pkgname=wine32-bin
pkgver=10.14
pkgrel=1
pkgdesc="Wine 32-bit prebuilt binary package"
arch=('x86_64')
url="https://github.com/malta-rf/wine32-bin"
license=('LGPL')
provides=('wine32')
conflicts=('wine32')
depends=('freetype2' 'lib32-freetype2' 'lib32-gcc-libs' 'lib32-glibc')
source=("$pkgname-$pkgver-$pkgrel-x86_64.pkg.tar.zst::https://github.com/malta-rf/wine32-bin/releases/download/v${pkgver}-${pkgrel}/wine32-${pkgver}-${pkgrel}-x86_64.pkg.tar.zst")
sha256sums=('SKIP')

package() {
    # como já é pacote pacman pronto, só copiamos
    msg2 "Este é um pacote binário, use pacman -U para instalar manualmente."
}

