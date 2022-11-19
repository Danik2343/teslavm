
# TeslaVM (early++ alpha)
[![GPLv3 license](https://img.shields.io/badge/License-GPLv3-blue.svg)](http://perso.crans.org/besson/LICENSE.html)
[![Windows](https://badgen.net/badge/icon/windows?icon=windows&label)](https://microsoft.com/windows/)
[![made-with-javascript](https://img.shields.io/badge/Made%20with-JavaScript-1f425f.svg)](https://www.javascript.com)
[![Visual Studio Code](https://img.shields.io/badge/--007ACC?logo=visual%20studio%20code&logoColor=ffffff)](https://code.visualstudio.com/)



TeslaVM is graphical user interface made for QEMU for windows usage, since only linux have well working GUI interface for QEMU and its kinda hard and not practical to use i thought that i can make a program like virt-manager.

## FAQ

#### Does it support machine acceleration and graphics acceleration?

&nbsp;Yes it does on AMD and Intel CPU's

#### What guest OS does it support?

&nbsp;Any linux distro 32bit/64bit and Windows (currently only 32bit)

#### Will it support more machines to save than only one?

&nbsp;Yes, we are planning to rework the GUI. We are currently working more on the backend than the frontend.

#### Will it fully support windows?

&nbsp;Currently Windows support is poor (only 32 bit, poor acceleration but it's ok) but we are going to improve it

#### HAX acceleration makes my machines doesnt launch! 😠

&nbsp;Probably you dont have [HAXM](https://github.com/intel/haxm/releases/tag/v7.7.1) or you have Hyper-V [enabled](https://www.nakivo.com/blog/uninstalling-or-disabling-hyper-v-in-windows-10/).

#### I cant launch machine with Hyper-V acceleration 😡
&nbsp;You have to [install](https://learn.microsoft.com/pl-pl/virtualization/hyper-v-on-windows/quick-start/enable-hyper-v) Hyper-V.

#### I cant even launch a VM 😡😡
&nbsp;Bro. You should check if your CPU supports VT-d/VT-x and if does, check if you have virtualization options enabled in BIOS.
## Screenshot from app

![demo](https://media.discordapp.net/attachments/1019861237741400145/1043629222981279764/image.png?width=581&height=448)

## Authors

- [@tesla15](https://www.github.com/tesla15)
