# Maintainer: NekoIceCream <youremail@domain.com>
pkgname=neko-ice-pm
pkgver=1.0.0
pkgrel=1
pkgdesc="NekoIce AUR Helper Written With Bash"
arch=(x86_64)
license=('MIT')
depends=('wget')
conflicts=(neko-ice-pm-beta)
validpgpkeys=()

prepare() {
	wget https://raw.githubusercontent.com/NekoIceTeam/Neko-Ice-PM/main/neko
}

package() {
	sudo mv ./neko /usr/local/bin/neko
	sudo chmod +x /usr/local/bin/neko 
}
