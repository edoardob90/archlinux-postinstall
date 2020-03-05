# Requirements

Ansible must be installed: `pacman -S ansible git`

## Tasks

### Required

- [ ] `pkg`: configuration of APT. It should be translated for Arch package manager
- [ ] `realm`: join Kerberos domain
- [ ] `autofs`: setup Automount
- [ ] `sshd`: Open SSH client/server
- [ ] `cacerts`: Empa CA certificates
- [ ] `ipv6`: prefer IPv4 over IPv6. See also [page on ArchWiki](https://wiki.archlinux.org/index.php/IPv6#Prefer_IPv4_over_IPv6)

### Optional

- [ ] `eduroam`: connect to Eduroam. *Is it needed only for laptops, I think.*
- [ ] `evolution`: install Evolution email reader with Exchange support
- [ ] `plymouth`: splash screen with Empa theme during boot
