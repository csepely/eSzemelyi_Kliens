# Maintainer: Peter Csepely <csp@szerencs.hu>
pkgname="eSzemelyi_Kliens"
_major=1
_minor=3
_main=14
pkgver="$_major.$_minor.$_main"
pkgrel=1
pkgdesc="eSzemelyi client software package for Hungarian eSzig card."
arch=('x86_64')
url="http://www.kekkh.gov.hu/Eszemelyi/uj_eszemelyi/altalanos_informaciok"
license=('unknown')
source=("http://www.kekkh.gov.hu/Eszemelyi/app/${pkgname}_x64_${_major}_${_minor}_${_main}.deb")
md5sums=('aafa454aa40699b9b5a42f76f5d1971f')

package() {
  echo ":: package()"
  tar -C $pkgdir -Jxf $srcdir/data.tar.xz
}
