<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://pi-hole.github.io/graphics/Vortex/Vortex_Vertical_wordmark_darkmode.png">
    <source media="(prefers-color-scheme: light)" srcset="https://pi-hole.github.io/graphics/Vortex/Vortex_Vertical_wordmark_lightmode.png">
    <img src="https://pi-hole.github.io/graphics/Vortex/Vortex_Vertical_wordmark_lightmode.png" width="168" height="270" alt="Pi-hole website">
  </picture>
    <br>
    <strong>Network-wide ad blocking via your own Linux hardware.</strong>
</p>

# <center>Steps to install _Pi-Hole_</center>

- You need a system that is a linux distribution | You can also use a virtual machine.
- You need to install certain terminal dependencies.
- I _**recommend**_ that you take notes.

## Install [Ubuntu](https://ubuntu.com/download)

To use Ubuntu you need to know the architecture of your processor, either [**RISC**](https://es.wikipedia.org/wiki/Reduced_instruction_set_computing) used for example by _ARM_ processors or [**CISC**](https://wikipedia.org/wiki/Complex_instruction_set_computer) used for example by _AMD_ or _Intel_ (x86).

### Install for chips _ARM_ (x64_32 Bits)

You need to install the [**Ubuntu Server**](https://ubuntu.com/download/server) version as there is no desktop version for _ARM_ users yet, I recommend you to watch a video on how to install ubuntu server for RISC chips.

### Install for chips _AMD_ or _Intel_ (x86)

To install ubuntu faster and easier I recommend using the [**Ubuntu Desktop**](https://ubuntu.com/download/desktop) version as it has the default graphical interface of the ubuntu operating system, I recommend you to watch a video on how to install ubuntu Desktop for CISC chips.

> [!NOTE]
> I recommend doing it in a virtual machine such as [Virtualbox](https://www.virtualbox.org/wiki/Downloads), [VMWare](https://www.vmware.com/products/fusion.html), [UTM](https://mac.getutm.app/), etc.

<br>

---

<br>

<sub>[Pi-Hole Documentation](https://docs.pi-hole.net/main/basic-install/)</sub>

## Install [_Pi-Hole_](https://github.com/pi-hole/pi-hole/tree/master?tab=readme-ov-file#one-step-automated-install) in Terminal

Inside your **Terminal** type or copy and paste the following code:

```bash
sudo curl -sSL https://install.pi-hole.net | bash
```

---

Follow the steps below once you have installed Pi-Hole on a terminal.

<div style="display: flex;">
  <img src="./IMG/StaticIpNeeded.png" width="413px" />
  <img src="./IMG/IpStaticAddress.png" width="413px" />
  <img src="./IMG/DnsProvider.png" width="413px" />
  <img src="./IMG/Blocklists.png" width="413px" />
  <img src="./IMG/AdminWebInterface.png" width="413px" />
  <img src="./IMG/PrivacyFtl.png" width="413px" />
</div>
