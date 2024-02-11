# General package information
pkgname=mod-overlay-git
pkgver=1.0.0
pkgrel=3
pkgdesc="OverlayFS mod manager"
url="https://github.com/Keelhauled/mod-overlay"
license=("GPL3")
arch=("any")

_tempreponame="mod-overlay-repo"
_binname="mod-overlay"

# Dependencies
depends=("python" "fuse-overlayfs")

# Download information
source=("${_tempreponame}::git+file://${PWD}")
#source=("${_tempreponame}::git+https://github.com/Keelhauled/mod-overlay")
sha256sums=("SKIP")

package() {
  cd "${srcdir}/${_tempreponame}"
  install -D -m755 "${_binname}" "${pkgdir}/usr/bin/${_binname}"
}
