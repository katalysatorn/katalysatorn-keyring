pkgname=katalysatorn-keyring
pkgver=20250108
pkgrel=1
pkgdesc="katalysatorn keyring"
arch=(any)
license=('GPL-3.0-or-later')
install=$pkgname.install
source=("katalysatorn.gpg"
"$install"
)

sha512sums=('0d4328454e175dcf25b9eb5fe9cea7c66aaf8dd5d8ee687c2d09476cfb54df16f5c3166218ececf092e51255a0ac59266c86601313b822131d6b874865641a36'
'5a6192a50f647c2eed0cc44f93ca216debf18e780d7becacd4de9400e32024aa3bf5185d6c6a49e0796fca3c7662f2c591085430f003b84c2d8f705955f87deb')

package() {
	install -D -m0644 -t "${pkgdir}"/usr/share/pacman/keyrings/ 'katalysatorn.gpg'
}
