# Maintainer: agnotek <agnostic[dot]sn[at]gmail[dot]com>

pkgname=pushbullet-commons
pkgver=0.4.0
_anotherpkgver=14.04.1
_alienpkgrel=0
pkgrel=2
pkgdesc="A library to work width pushbullet. This library is necessary for pushbullet indicator and other applications"
arch=('any')
license=('GPL')
url="http://www.atareao.es"
options=()
conflicts=()
depends=('python-dbus' 'python-requests' 'python-gobject' 'python-ws4py' 'python-pillow')
optdepends=()
source=("https://launchpad.net/~atareao/+archive/ubuntu/atareao/+files/${pkgname}_${pkgver}-${_alienpkgrel}extras${_anotherpkgver}_all.deb")
md5sums=('b1cc9de8b2a71b96a05b187a76d3ecb4')

package() {
  cd "${srcdir}"

  ar x "${pkgname}_${pkgver}-${_alienpkgrel}extras${_anotherpkgver}_all.deb" > /dev/null
  tar -xJf data.tar.xz -C "${pkgdir}"
 
  install -d -m755 "${pkgdir}/usr/"
  install -d -m755 "${pkgdir}/opt/"


}
