# Generated by debtap
# Maintainer: 
# Contributor: 
pkgname=e-school
pkgver=4.0.3
pkgrel=1
pkgdesc="E-SCHOOL CAMBODIA. ជាគេហទំព័រសម្រាប់ រៀនគួរត្រៀមប្រលងបាក់ឌុប តាម Online"
arch=('x86_64')
url="https://e-schoolcambodia.com/download/linux"
license=('')
groups=('')
depends=('alsa-lib' 'atk' 'at-spi2-atk' 'at-spi2-core' 'cairo' 'dbus' 'desktop-file-utils' 'discord' 'expat' 'gdk-pixbuf2' 'glib2' 'gtk3' 'hicolor-icon-theme' 'libcups' 'libnotify' 'libsecret' 'libx11' 'libxcb' 'libxcomposite' 'libxcursor' 'libxdamage' 'libxext' 'libxfixes' 'libxi' 'libxrandr' 'libxrender' 'libxss' 'libxtst' 'nspr' 'nss' 'pango' 'util-linux-libs' 'xdg-utils')
optdepends=('libappindicator-gtk3')
options=('!strip' '!emptydirs')
install=${pkgname}.install
source_x86_64=(
	"${pkgname}_${pkgver}_amd64.deb"
	"${pkgname}.desktop"
)
sha512sums_x86_64=(
	'SKIP'
	'8641b7a21c8fc8e9cd7eea00ffe95360c755be9d81c6382cf6b57607fcb1e0d9197073b097d74494294371ddd0f0c60c614613d9d50cc9b78aa2bb9c405be28c'
)

package(){

	# Extract package data
	tar xf data.tar.xz -C "${pkgdir}"
	install -D -m644 "${srcdir}/${pkgname}.desktop" "${pkgdir}/usr/share/applications/${pkgname}.desktop"

	install -D -m644 "${pkgdir}/opt/E-SCHOOL/LICENSES.chromium.html" "${pkgdir}/usr/share/licenses/${pkgname}/LICENSE"
	chmod 755 "${pkgdir}/opt/E-SCHOOL" "${pkgdir}/opt/E-SCHOOL/locales" "${pkgdir}/opt/E-SCHOOL/resources" "${pkgdir}/opt/E-SCHOOL/swiftshader"

}
