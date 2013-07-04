# Maintainer: gandro <gandro@gmx.net>
pkgname=netctl-auto-cli
pkgver=0.1
pkgrel=1
pkgdesc="Command line interface for the netctl-auto service."
url="https://github.com/gandro/netctl-auto-cli"
arch=('any')
license=('GPL')
depends=('netctl' 'wpa_supplicant')
makedepends=()
conflicts=()
replaces=()
backup=()
source=("http://github.com/gandro/${pkgname}/archive/v${pkgver}.tar.gz")
md5sums=('f3b4511eecf7c33198575e3bc0562052')

package() {
  cd "${srcdir}/${pkgname}-${pkgver}"
  install -Dm755 nacli "${pkgdir}/usr/bin/nacli"
}
