pkgname=skel-blend
pkgver=2023.01.01
pkgrel=2
pkgdesc='Skel configuration for blendOS'
url='https://github.com/blend-os/skel-blend'
arch=('any')
conflicts=('grml-zsh-config')
license=('Public domain')
source=('init.vim' '.zshrc')
sha256sums=('6f9f17c50e8566fb18960beb05d155b4439b9b42269dd9720f001e91aa50bc8f'
            '7755e054290733619bdf0be418bb3acbd702350e812880b00125cf74b41f7a8b')

package() {
	cd "$pkgdir"

	install -d etc/skel/.config/nvim

	install -m644 "$srcdir"/init.vim etc/skel/.config/nvim/
	install -m644 "$srcdir"/.zshrc etc/skel/
}

