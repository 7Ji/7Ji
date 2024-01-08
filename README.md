## Welcome to 7Ji's profile 

A FOSS enjoyer, creator, maintainer and contributor, preferring low-level over abstraction.

My blog site is available at https://7ji.github.io/ , but I don't write much there due to limited time.

Creator of the following projects:
 - [ampart](https://github.com/7Ji/ampart), a partition tool for Amlogic's proprietary eMMC partition format mainly found on their Android firmware, in C, a [patchset for mainline kernel](https://github.com/7Ji/linux/commit/049bddc86d7e2d1a7727bbc6d268be9cf5e779d2) is also available to natively support such partitions.
 - [git-mirrorer / gmr](https://github.com/7Ji/git-mirrorer), a tool to mirror git repos, and archive and checkout them with submodules included implicitly, in C, using libgit2 and libyaml.
 - [YAopenvfD](https://github.com/7Ji/YAopenvfD), a helper daemon to improve the functionality of the [linux_openvfd](https://github.com/arthur-liberman/linux_openvfd) kernel module, for fragment LCD displays found on set-top boxes, in C.
 - [eemount](https://github.com/7Ji/eemount), a system utility to efficiently and elegantly set up the external ROMs mounting for EmuELEC (see below), in C, using libsystemd.
 - [pkgbuild-rs](https://github.com/7Ji/pkgbuild-rs), a naive [PKGBUILD](https://wiki.archlinux.org/title/PKGBUILD) parsing library, in Rust.
 - [arch_repo_builder / arb](https://github.com/7Ji/arch_repo_builder), a builder to build an Arch Linux repo in a disk-space-and-network-efficient way, in Rust.
 - [archrepo](https://github.com/7ji/archrepo), an Arch Linux / Arch Linux ARM repo, focusing on media center use cases, hosting pre-built kernel and video de/encoding packages, notably for Rockchip RK3588 (Orange Pi 5/5B/5Plus, Orange Pi 3B, Radxa Rock 5B) and Amlogic platforms, updated hourly.
 - [amlogic-s9xxx-archlinuxarm](https://github.com/7Ji/amlogic-s9xxx-archlinuxarm), [orangepi5-archlinuxarm](https://github.com/7Ji/orangepi5-archlinuxarm/) and [orangepi5-rkloader](https://github.com/7Ji/orangepi5-rkloader) providing pre-built ALARM / bootloader images with my ported/maintained kernels pre-installed.
 - [nvrust](https://github.com/7Ji/nvrust), a daemon to turn any Linux box into a Network Video Recorder, in Rust, using libffmpeg.
 - [videoArchiver.py](https://github.com/7Ji/videoArchiver.py), a video archiving tool, in Python, using ffmpeg.
 - [usb2host](https://github.com/7Ji/usb2host) in C, [router_reporter](https://github.com/7Ji/router_reporter) in Go, [mirai-ip-notifier](https://github.com/7Ji/mirai-ip-notifier) in Go, [arch_pkgbuilds_dumper](https://github.com/7Ji/arch_pkgbuilds_dumper) in Python, [CargoStranding](https://github.com/7Ji/CargoStranding) in C++, [CargoStrandingWeb](https://github.com/7Ji/CargoStrandingWeb) in Javascript, and other nice tools.

Creater of the following organisations:
 - [7Ji-PKGBUILDs](https://github.com/7Ji-PKGBUILDs), collections of PKGBUILDs (recipes to build Arch Linux package from) submitted/maintained/co-maintained by myself, focusing on kernel, video de/encoding, and more.
 - [HybridELEC](https://github.com/HybridELEC), a downstream semi-distro to achieve side-by-side dual boot of CoreELEC (see below) and EmuELEC (see below), some special images are also released for chosen devices to achieve triple boot, with Android as the main OS. In various languages (including an Android App to switch OS) and based on kernel/booting reverse-engineering.

Maintainer of the following projects:
 - [EmuELEC](https://github.com/EmuELEC/EmuELEC), a distro focusing on smooth out-of-box retro gaming experience on entry-level ARM devices, for Amlogic and Rockchip devices. As the kernel expert in team to introduce support to new devices.

Contributor/Contributing to the following projects:
 - [libgit2](https://github.com/libgit2/libgit2), a C library that achieves the functionality of git.
 - [CoreELEC](https://github.com/CoreELEC/CoreELEC), a distro focusing on smooth out-of-box video playback experience on Amlogic devices, a Just Enough Operating System for Kodi, upstream distro of EmuELEC.
 - [systemd](https://github.com/systemd/systemd), really no need to introduce,
 - [archlinuxarm](https://github.com/archlinuxarm), a downstream distro of Arch Linux for ARM platforms.

Some of my upstreamable / non-upstreamable patches to mainline kernel and u-boot are hosted in the following repos/branches:
 - [7Ji/linux](https://github.com/7Ji/linux), the default amlogic tree contains my patchsets to enable Amlogic partitions support, port several device trees, and add/improve the JL21xx network PHY driver and openvfd driver.  
 - [7Ji/u-boot](https://github.com/7Ji/u-boot), the default random-boxes tree contains my patchsets to port/add several device trees, and add support for environment-based partitions.
 - [7Ji/linux-orangepi](https://github.com/7Ji/linux-orangepi), the default orange-pi-5.10-rk3588-gcc-12 branch contains my fixes to drivers, filesystem, memory management and more to make the BSP kernel buildable on post-gcc-12 toolchains.
 - I also submit to LKML directly when I consider them upstreamable, like the one for the embedded partitions in block subsystem ([v1](https://lore.kernel.org/linux-block/25655037ca3e404e9111341ea423f5ce@AcuMS.aculab.com/T/#t), [v2](https://lore.kernel.org/linux-block/20240102024115.4395-1-pugokushin@gmail.com/T/#u))
