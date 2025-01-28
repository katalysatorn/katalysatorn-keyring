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

sha512sums=('5bcf96e0ae9c7cd8ecc535b18047e78e3c4c67c3421c56bce42e1c13d02e963b8cfb6a75524ad72761de27f7e85eefd14459845370b4ddd0d41d9397d0424b5a'
'5a6192a50f647c2eed0cc44f93ca216debf18e780d7becacd4de9400e32024aa3bf5185d6c6a49e0796fca3c7662f2c591085430f003b84c2d8f705955f87deb')

package() {
	install -D -m0644 -t "${pkgdir}"/usr/share/pacman/keyrings/ 'katalysatorn.gpg'
}
