# Maintainer: gandro <gandro@gmx.net>
pkgname=netctl-auto-cli
pkgver=0.2.1
pkgrel=1
pkgdesc="Command line interface for the netctl-auto service."
url="https://github.com/gandro/netctl-auto-cli"
arch=('any')
license=('MIT')
depends=('netctl' 'wpa_supplicant')
makedepends=()
conflicts=()
replaces=()
backup=()
source=("http://github.com/gandro/${pkgname}/archive/v${pkgver}.tar.gz")
md5sums=('128f5dad25274082f3eff6bf7ca43045')

package() {
  cd "${srcdir}/${pkgname}-${pkgver}"
  install -Dm755 nacli "${pkgdir}/usr/bin/nacli"
}
