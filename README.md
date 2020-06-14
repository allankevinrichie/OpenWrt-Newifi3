![Minimum Build](https://github.com/allankevinrichie/OpenWrt-Newifi3/workflows/Minimum%20Build/badge.svg)
![Typical Build](https://github.com/allankevinrichie/OpenWrt-Newifi3/workflows/Typical%20Build/badge.svg)

# OpenWrt-Newifi3 Frameware Auto-build Repo Powered by GitHub Actions

- Template from [P3TERX/Actions-OpenWrt](https://github.com/P3TERX/Actions-OpenWrt)
- Source code from [coolsnowwolf/lede](https://github.com/coolsnowwolf/lede)

# Configuration

Avaliable actions: Minimum, Typical

## Minimum

- LUCI -> luci-app-ssr-plus(*)

## Typical

- Base System -> IPv6 Support

- Administration -> htop/sudo
- Network -> UnblockNeteaseMusic / curl / rsync-d / sshfs / ip6tables / iptables-mod-nat-extra / nstat / openssh-client-* / autossh / openssh-server-pam / openssh-sftp-client / openssh-sftp-server / sshtunnel / ntpclient / sstp-client / git-http / 6in4 / 6rd / 6to4 / ifstat / iftop / iputils-ping/ping6/tracepath/tracepath6/traceroute6 / socat(SSL)

- LUCI -> luci-theme-*/ luci-app-amule / luci-app-aria2 / luci-app-baidupcs-web / luci-app-diskman / luci-app-frpc / luci-app-frps / luci-app-guest-wifi / luci-app-minidlna / luci-app-mwan3-\* / luci-app-openvpn / luci-app-openvpn-server / luci-app-privoxy / luci-app-statistics / luci-app-transmission /  luci-app-webadmin

- Utilities -> bzip2 / gzip / unrar / unzip / xz / cgdisk / vim-full / fuse-utils / ntfs-3g-utils / xfs-mkfs / bash / findutils-* / getopt / grep / hwloc-utils / lscpu / lsof / mount-utils / tar / tree / usbutils / uuidgen
