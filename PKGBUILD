pkgname=ubuntu-keyring
pkgver=2012.05.19
pkgrel=1
pkgdesc="GnuPG keys of the Ubuntu archive"
url="http://packages.ubuntu.com/trusty/ubuntu-keyring"
arch=('x86_64')
license=('GPL')
depends=('gnupg')
source=("http://mirror.netcologne.de/ubuntu/pool/main/u/ubuntu-keyring/ubuntu-keyring_${pkgver}_all.deb")
sha512sums=('60d677ba81f6e4e61c34626aa791a3bd132f68b33d9ac587f1eda30b8d681853c23ed6d17d8960643ee9c5de95e5b8aedcf689fc59d4ca7945e9c26d95ebf902')

package() {
  tar xzvf "${srcdir}/data.tar.gz" -C "${pkgdir}/"
}
