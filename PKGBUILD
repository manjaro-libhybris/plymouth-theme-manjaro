# Maintainer: Bardia Moshiri <fakeshell@bardia.tech>
# Contributor: JeyKul <jey@kulovac.de>

pkgname=plymouth-theme-manjaro
pkgver=0.1
pkgrel=1
pkgdesc="Manjaro theme for plymouth based on Droidian's plymouth theme"
arch=('aarch64')
url="https://github.com/manjaro-libhybris/plymouth-theme-manjaro"
license=('custom')
provides=()
depends=('plymouth-hybris')
options=()
source=('git+https://github.com/manjaro-libhybris/plymouth-theme-manjaro'
	'manjaro_logo.png'
	'manjaro_logo_glowing.png'
	'manjaro.plymouth'
	'manjaro.script'
	'progress_bar.png'
	'progress_box.png'
	'lock.png'
	'logo.png'
	'bullet.png'
	'entry.png'
	'box.png')
sha256sums=('SKIP'
            '3554c3c8cbd37aa20972e834f0b82d3a58f94d5fc5a6f7f6e98541de54d55da1'
            '704b7fa7d5c65095fccaac0e157945a82348a7f932b5dcecf22ca8237394cdbc'
            '0f2e784df94b1e2af3be24c979bc14914dc2481daa81d74185ab1c2e8a164c33'
            '4c1d89ccd48d7b9aa4e5257c16ea8d4333490eac170f348ddcbe7bfbd880155e'
	    'c75b790eb804b97a951e1e9db929ea0b3b8c0fcdd707abb0f01db8a8574c295a'
	    'ef7901ce0c9d74c9e6bb68551ebbe6431cfcbee8c42cb69aaef0e3f3d88125aa'
	    'ed5b5ca7f935efcb97f6dd59260664a8c223b4986b33705d6bf83572c9a25626'
	    '5c39ef159a1488c666e61adce1d32567a793eaa0313a330a6f705b95d075aa9c'
	    '490967949a9c20602c7293b3ce1e311d15de3966896bba0a54eaf94f2ea4ce1f'
	    'ea8b2bb15cd1c7ee4fe17bb55854e7ea8f1ec0308f3dc14e1a484904fd6163b0'
	    'f1d8e649196de565c05b1ff629d9439b4817182d2a15986e1e04c0791aa77b48')

package() {
  mkdir -p ${pkgdir}/usr/local/share/plymouth/themes/manjaro

  # Thanks to https://github.com/jeykul for manjaro_logo.png and manjaro_logo_glowing.png
  install -m644 "$srcdir"/manjaro_logo.png "$pkgdir"/usr/local/share/plymouth/themes/manjaro
  install -m644 "$srcdir"/manjaro_logo_glowing.png "$pkgdir"/usr/local/share/plymouth/themes/manjaro
  install -m644 "$srcdir"/manjaro.plymouth "$pkgdir"/usr/local/share/plymouth/themes/manjaro
  install -m644 "$srcdir"/manjaro.script "$pkgdir"/usr/local/share/plymouth/themes/manjaro
  install -m644 "$srcdir"/progress_bar.png "$pkgdir"/usr/local/share/plymouth/themes/manjaro
  install -m644 "$srcdir"/progress_box.png "$pkgdir"/usr/local/share/plymouth/themes/manjaro
  install -m644 "$srcdir"/lock.png "$pkgdir"/usr/local/share/plymouth/themes/manjaro
  install -m644 "$srcdir"/logo.png "$pkgdir"/usr/local/share/plymouth/themes/manjaro
  install -m644 "$srcdir"/bullet.png "$pkgdir"/usr/local/share/plymouth/themes/manjaro
  install -m644 "$srcdir"/entry.png "$pkgdir"/usr/local/share/plymouth/themes/manjaro
  install -m644 "$srcdir"/box.png "$pkgdir"/usr/local/share/plymouth/themes/manjaro

  mkdir -p ${pkgdir}/usr/share/plymouth/themes/manjaro

  install -m644 "$srcdir"/manjaro_logo.png "$pkgdir"/usr/share/plymouth/themes/manjaro
  install -m644 "$srcdir"/manjaro_logo_glowing.png "$pkgdir"/usr/share/plymouth/themes/manjaro
  install -m644 "$srcdir"/manjaro.plymouth "$pkgdir"/usr/share/plymouth/themes/manjaro
  install -m644 "$srcdir"/manjaro.script "$pkgdir"/usr/share/plymouth/themes/manjaro
  install -m644 "$srcdir"/progress_bar.png "$pkgdir"/usr/share/plymouth/themes/manjaro
  install -m644 "$srcdir"/progress_box.png "$pkgdir"/usr/share/plymouth/themes/manjaro
  install -m644 "$srcdir"/lock.png "$pkgdir"/usr/share/plymouth/themes/manjaro
  install -m644 "$srcdir"/logo.png "$pkgdir"/usr/share/plymouth/themes/manjaro
  install -m644 "$srcdir"/bullet.png "$pkgdir"/usr/share/plymouth/themes/manjaro
  install -m644 "$srcdir"/entry.png "$pkgdir"/usr/share/plymouth/themes/manjaro
  install -m644 "$srcdir"/box.png "$pkgdir"/usr/share/plymouth/themes/manjaro
}
