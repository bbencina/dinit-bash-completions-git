pkgname=dinit-bash-completions-git
pkgver=20230814
pkgrel=1
pkgdesc="Dinit completions for Bash"
arch=('any')
url="https://github.com/davmac314/dinit/tree/master/contrib/shell-completion/bash/dinitctl"
depends=('bash-completion')
source=('dinitctl::https://raw.githubusercontent.com/davmac314/dinit/refs/heads/master/contrib/shell-completion/bash/dinitctl')
sha256sums=('04bd52d495a47f4416b63d6a820bb0c60ebdcdebf7c354e719b08f62e95c2f46')

package() {
    install -Dm644 dinitctl "$pkgdir/usr/share/bash-completion/completions/dinitctl"
}
