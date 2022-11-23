pkgname='k-arch-update'
pkgver='0.5'
pkgrel='1'
arch=('any')
licence=('MIT')
pkgdesc='Archlinux system update utility'
depends=('sudo')
optdepends=('pacman-contrib: Manage pacman package cache'
            'flatpak: Update flatpak packages')

package() {
    mkdir -p "${pkgdir}/usr/bin"
    mkdir -p "${pkgdir}/usr/share/k-arch-update"

    cp "${srcdir}/bin/k-arch-update" "${pkgdir}/usr/bin"
    cp "${srcdir}/config/k-arch-update.conf.default" "${pkgdir}/usr/share/k-arch-update"

    chmod a+x "${pkgdir}/usr/bin/k-arch-update"
}