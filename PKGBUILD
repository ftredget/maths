# Maintainer: Finn Tredget <f.tredget@lancaster.ac.uk>
pkgname=maths
pkgver=1.0.0
pkgrel=1
pkgdesc="A rofi script for my maths work"
arch=('any')
url="http://www.github.com/ftredget/maths"
license=('GPL')
depends=('rofi' 'neovide' 'zathura')
noextract=("maths" "LICENSE")
source=("maths" "LICENSE")
sha256sums=('6a99a21c70ae75d8f9f7bd66f00d1e043d967021909b30f014261b7c3f37107f'
            '3972dc9744f6499f0f9b2dbf76696f2ae7ad8af9b23dde66d6af86c9dfb36986')

package() {
  install -Dm644 LICENSE "$pkgdir/usr/share/licenses/$pkgname/LICENSE"
  install -Dm755 maths "$pkgdir/usr/bin/maths"
}

