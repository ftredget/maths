# Maintainer: Finn Tredget <f.tredget@lancaster.ac.uk>
pkgname=maths
pkgver=1.2.1
pkgrel=1
pkgdesc="A rofi script for my maths work"
arch=('any')
url="http://www.github.com/ftredget/maths"
license=('GPL')
depends=('rofi' 'neovide' 'zathura')
noextract=("maths" "LICENSE")
source=("maths" "mathscombine" "LICENSE")
sha256sums=('c72c8155f2c6ec217e0bd83b51818d6b200ede009883bf212a74c8d090d346c9'
            'f6e54922731b68aad84a82ec5cd9b741f3f92cbc32e4b960659349dca3e0efe4'
            '3972dc9744f6499f0f9b2dbf76696f2ae7ad8af9b23dde66d6af86c9dfb36986')

package() {
  install -Dm644 LICENSE "$pkgdir/usr/share/licenses/$pkgname/LICENSE"
  install -Dm755 maths "$pkgdir/usr/bin/maths"
  install -Dm755 mathscombine "$pkgdir/usr/bin/mathscombine"
}

