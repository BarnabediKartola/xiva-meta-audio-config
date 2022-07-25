# This is an example PKGBUILD file. Use this as a start to creating your own,
# and remove these comments. For more information, see 'man PKGBUILD'.
# NOTE: Please fill out the license field for your package! If it is unknown,
# then please put 'unknown'.

# Maintainer: Your Name <youremail@domain.com>
pkgname=xiva-meta-audio-config
pkgver=1.0.0
pkgrel=9
epoch=
pkgdesc="Configura o sistema para audio profissional."
arch=('any')
# url=""
license=('GPL')
# groups=()
depends=('realtime-privileges' 'rtirq' 'rtapp' 'a52dec' 'faac' 'faad2' 'flac' 'jasper' 'lame' 'libdca' 'libdv' 'libmad' 'libmpeg2' 'libtheora' 'libvorbis' 'libxv' 'opus' 'wavpack' 'x264' 'xvidcore')
# makedepends=()
# checkdepends=()
# optdepends=()
# provides=()
conflicts=('pipewire-biglinux-config-git' 'biglinux-meta-audio-config')
#replaces=()
#backup=()
# options=()
install=post.install
# changelog=
# source=("$pkgname-$pkgver.tar.gz"
#         "$pkgname-$pkgver.patch")
# noextract=()
md5sums=()
# validpgpkeys=()

# prepare() {
# 	cd "$pkgname-$pkgver"
# 	patch -p1 -i "$srcdir/$pkgname-$pkgver.patch"
# }
# 
# build() {
# 	cd "$pkgname-$pkgver"
# 	./configure --prefix=/usr
# 	make
# }
# 
# check() {
# 	cd "$pkgname-$pkgver"
# 	make -k check
# }
# 
package() {
# 	cd "$pkgname-$pkgver"
# 	make DESTDIR="$pkgdir/" install
cp -r "usr" "${pkgdir}/"
cp -r "etc" "${pkgdir}/"
}
