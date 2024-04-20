# Maintainer: Perkelo <alessandro [dot] scala [eight] [at] gmail [dot] com>

pkgname=ttf-pixeloid
pkgver=1.0
pkgrel=1
pkgdesc="Pixeloid Font"
arch=(any)
license=('custom:OFL')
depends=(fontconfig xorg-font-utils)
url="https://www.fontspace.com/pixeloid-font-f69232"
source=("pixeloid-font.zip::https://get.fontspace.co/download/family/mqz2e/acb0f928cbd14958935d2f02d7a6fa9a/pixeloid-font.zip")
sha256sums=('1fd3526d6258cf63622adb1548024b28ed7de109e56b5e7b510af365474ee9e8')
install=$pkgname.install

package() {
    install -d "$pkgdir/usr/share/fonts/TTF"
    install -m644 "$srcdir/PixeloidSans-mLxMm.ttf" "$pkgdir/usr/share/fonts/TTF/PixeloidSans.ttf"
    install -m644 "$srcdir/PixeloidSansBold-PKnYd.ttf" "$pkgdir/usr/share/fonts/TTF/PixeloidSansBold.ttf"
    install -m644 "$srcdir/PixeloidMono-d94EV.ttf" "$pkgdir/usr/share/fonts/TTF/PixeloidMono.ttf"
    install -d "$pkgdir/usr/share/licenses/ttf-pixeloid"
    install -m644 "$srcdir/misc/License.txt" "$pkgdir/usr/share/licenses/ttf-pixeloid/LICENSE"
}
