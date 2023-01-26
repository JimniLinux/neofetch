pkgname=neofetch
pkgver=7.1.0
pkgrel=1
pkgdesc="A CLI system information tool written in BASH that supports displaying images."
arch=('x86_64')
url="https://github.com/JimniLinux/${pkgname}"
license=('MIT')
depends=('bash')
Maintainer=('wiz64')

package() {
  cd "${pkgdir}" && make install
  install -D -m644 LICENSE.md "${pkgdir}/${pkgname}/LICENSE.md"
}