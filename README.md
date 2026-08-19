# Awesome linux rootkits with stars

## :key: feature table

Environment:

* CPU architecture
* Kernel/User mode (or mixed)

Core capabilities:

* Persistency
* Management interface
* Altering system (library) behavior

Stealth capabilities:

* Detection evasion
* System logs cleaning (filtering)

Hiding stuff capabilities:

* Hiding of files and directories
* Hiding (tampering) of file contents
* Hiding of processes and process trees
* Hiding of network connections and activity
* Hiding of process accounting information (like CPU usage)

Additional functions:

* Keylogger
* Backdoor/shell
* Gaining priveleges

## :see\_no\_evil: user mode rootkits

* <https://github.com/mempodippy/vlany> ⭐ 985 | 🐛 13 | 🌐 C | 📅 2020-12-11

  Linux LD\_PRELOAD rootkit (x86 and x86\_64 architectures)

* <https://github.com/chokepoint/azazel> ⭐ 804 | 🐛 7 | 🌐 C | 📅 2024-03-07

  Azazel is a userland rootkit based off of the original LD\_PRELOAD technique from Jynx rootkit.

* <https://github.com/unix-thrust/beurk> ⭐ 387 | 🐛 36 | 🌐 C | 📅 2017-04-28

  BEURK is an userland preload rootkit for GNU/Linux, heavily focused around anti-debugging and anti-detection.

* <https://github.com/chokepoint/Jynx2> ⭐ 182 | 🐛 0 | 🌐 C | 📅 2012-12-15

  JynxKit2 is an LD\_PRELOAD userland rootkit based on the original JynxKit.

* <https://github.com/NexusBots/Umbreon-Rootkit> ⭐ 64 | 🐛 1 | 🌐 C | 📅 2016-11-15

  LD\_PRELOAD based

* <https://github.com/chokepoint/jynxkit> ⭐ 61 | 🐛 0 | 🌐 C | 📅 2012-12-15

  JynxKit is an LD\_PRELOAD userland rootkit for Linux systems with reverse connection SSL backdoor

* <https://github.com/ChristianPapathanasiou/apache-rootkit> ⭐ 0 | 🐛 0 | 📅 2025-08-28

  A malicious Apache module with rootkit functionality

## :hear\_no\_evil: kernel mode rootkits

* <https://github.com/f0rb1dd3n/Reptile> ⭐ 2,716 | 🐛 31 | 🌐 C | 📅 2026-08-17 :zap: [details](details/reptile.md) :zap:

  Reptile is a LKM rootkit written for evil purposes that runs on Linux kernel 2.6.x/3.x/4.x

* <https://github.com/m0nad/Diamorphine> ⭐ 2,436 | 🐛 12 | 🌐 C | 📅 2026-04-27

  LKM rootkit for Linux Kernels 2.6.x/3.x/4.x/5.x (x86 and x86\_64)

* <https://github.com/h3xduck/TripleCross> ⭐ 1,977 | 🐛 19 | 🌐 C | 📅 2024-04-07

  A Linux eBPF rootkit with a backdoor, C2, library injection, execution hijacking, persistence and stealth capabilities.

* <https://github.com/MatheuZSecurity/Singularity> ⭐ 1,733 | 🐛 1 | 🌐 C | 📅 2026-06-11

  Singularity is a powerful Linux Kernel Module (LKM) rootkit designed for modern 6.x kernels. It provides comprehensive stealth capabilities through advanced system call hooking via ftrace infrastructure.

* <https://github.com/kris-nova/boopkit> ⭐ 1,678 | 🐛 13 | 🌐 C | 📅 2023-10-19

  Linux backdoor, rootkit, and eBPF bypass tools. Remote command execution over raw TCP.

* <https://github.com/nurupo/rootkit> ⭐ 827 | 🐛 1 | 🌐 C | 📅 2024-04-07

  Linux rootkit for Ubuntu 16.04 and 10.04 (Linux Kernels 4.4.0 and 2.6.32), both i386 and amd64

* <https://github.com/mncoppola/suterusu> ⭐ 684 | 🐛 5 | 🌐 C | 📅 2017-11-21

  An LKM rootkit targeting Linux 2.6.x/3.x on x86, and ARM

* <https://github.com/jarun/keysniffer> ⭐ 682 | 🐛 0 | 🌐 C | 📅 2022-04-15

  A Linux kernel module to grab keys pressed in the keyboard.

* <https://github.com/carloslack/KoviD> ⭐ 655 | 🐛 7 | 🌐 C | 📅 2026-05-31

  Linux 4.18+ rootkit with multiple reverse backdoors, task management, CPU usage hiding, stealth techniques, ELF infection and evasion from anti-rooktiks based on eBPF.

* <https://github.com/NoviceLive/research-rootkit> ⭐ 600 | 🐛 4 | 🌐 C | 📅 2021-12-01

  This is LibZeroEvil & the Research Rootkit project, in which there are step-by-step, experiment-based courses that help to get you started and keep your hands dirty with offensive or defensive development in the Linux kernel (LibZeroEvil).

* <https://github.com/ivyl/rootkit> ⭐ 404 | 🐛 0 | 🌐 TeX | 📅 2024-07-29

  Sample Rootkit for Linux

* <https://github.com/trailofbits/krf> ⭐ 360 | 🐛 12 | 🌐 C | 📅 2024-11-18

  A kernelspace randomized syscall faulter for Linux 4.15+

* <https://github.com/reveng007/reveng_rtkit> ⭐ 275 | 🐛 11 | 🌐 C | 📅 2025-12-06

  Linux Loadable Kernel Module (LKM) based rootkit capable of hiding itself, processes/implants, rmmod proof, has ability to bypass infamous rkhunter antirootkit.

* <https://github.com/trimpsyw/adore-ng> ⭐ 223 | 🐛 0 | 🌐 C | 📅 2015-12-30

  linux rootkit adapted for 2.6 and 3.x

* <https://github.com/croemheld/lkm-rootkit> ⭐ 180 | 🐛 0 | 🌐 C | 📅 2017-09-17

  A LKM rootkit for most newer kernel versions.

* <https://github.com/Eterna1/puszek-rootkit> ⭐ 162 | 🐛 1 | 🌐 C | 📅 2018-02-12

  Yet another LKM rootkit for Linux. It hooks syscall table.

* <https://github.com/h3xduck/Umbra> ⭐ 136 | 🐛 5 | 🌐 C | 📅 2021-09-19

  An experimental LKM rootkit for v4.x/5.x kernels which opens a backdoor that can be used to get a reverse shell remotely.

* <https://github.com/jermeyyy/rooty> ⭐ 121 | 🐛 1 | 🌐 C | 📅 2026-03-27

  Academic project of Linux rootkit made for Bachelor Engineering Thesis.

* <https://github.com/QuokkaLight/rkduck> ⭐ 92 | 🐛 10 | 🌐 C | 📅 2024-07-27 :zap: [details](details/rkduck.md) :zap:

  rkduck - Rootkit for Linux v4

* <https://github.com/David-Reguera-Garcia-Dreg/enyelkm> ⭐ 86 | 🐛 0 | 🌐 C | 📅 2023-08-11

  LKM rootkit for Linux x86 with the 2.6 kernel. It inserts salts inside system\_call and sysenter\_entry.

* <https://github.com/PinkP4nther/Sutekh> ⭐ 77 | 🐛 0 | 🌐 C | 📅 2019-10-17

  An example rootkit that gives a userland process root permissions (x86, 4.x)

* <https://github.com/milabs/kopycat> ⭐ 73 | 🐛 0 | 🌐 C | 📅 2021-03-11

  KOPYCAT - Linux Kernel module-less implant (backdoor).

* <https://github.com/bones-codes/the_colonel> ⭐ 56 | 🐛 0 | 🌐 Python | 📅 2015-05-01

  An experimental linux kernel module (rootkit) with a keylogger and built-in IRC bot

* <https://github.com/falk3n/subversive> ⭐ 51 | 🐛 0 | 🌐 C | 📅 2022-01-11

  x86\_64 linux rootkit using debug registers

* <https://github.com/ait-aecid/caraxes/> ⭐ 50 | 🐛 2 | 🌐 C | 📅 2025-06-05

  Academic Linux Kernel Module rootkit, from Linux 6.2 up tested until Linux 6.11 - may work with even newer versions.

  Features only hiding of files/directories and processes.

* <https://github.com/hanj4096/wukong> ⭐ 45 | 🐛 0 | 🌐 C | 📅 2016-04-06

  Wukong: a LKM rootkit for Linux kernel 2.6.x, 3.x and 4.x

* <https://github.com/a7vinx/liinux> ⭐ 37 | 🐛 0 | 🌐 C | 📅 2016-06-21

  A linux rootkit works on kernel 4.0.X or higher

* <https://github.com/kacheo/KernelRootkit> ⭐ 36 | 🐛 0 | 🌐 C | 📅 2026-06-04

  Linux kernel rootkit to hide certain files and processes.

* <https://github.com/dsmatter/brootus> ⭐ 33 | 🐛 0 | 🌐 C | 📅 2021-10-03

  bROOTus is a Linux kernel rootkit that comes as a single LKM (Loadable Kernel Module) and it is totally restricted to kernel 2.6.32.

* <https://github.com/vrasneur/randkit> ⭐ 28 | 🐛 2 | 🌐 C | 📅 2016-03-15

  Random number rootkit for the Linux kernel

* <https://github.com/En14c/LilyOfTheValley> ⭐ 24 | 🐛 1 | 🌐 C | 📅 2020-06-16

  LilyOfTheValley is a simple LKM linux kernel rootkit for v4.x that works on (x86 and x86\_64)

* <https://github.com/NinnOgTonic/Out-of-Sight-Out-of-Mind-Rootkit> ⭐ 24 | 🐛 0 | 🌐 Python | 📅 2014-11-15 :zap: [writeup](https://github.com/NinnOgTonic/Out-of-Sight-Out-of-Mind-Rootkit/blob/master/osom.pdf) ⭐ 24 | 🐛 0 | 🌐 Python | 📅 2014-11-15 :zap:

  Out of Sight, Out of Mind is a study and implementation of Linux rootkit methods. In addition a new covert network channel using additional Domain Name System (DNS) is implemented.

* <https://github.com/deb0ch/toorkit> ⭐ 14 | 🐛 0 | 🌐 C | 📅 2016-03-13

  A simple useless rootkit for the linux kernel

* <https://github.com/romeroperezabel/ARP-RootKit>

  An open source rootkit for the Linux Kernel to develop new ways of infection/detection.

* <https://github.com/jiayy/lkm-rootkit>

  An lkm rootkit support x86/64,arm,mips

* <https://github.com/varshapaidi/Kernel_Rootkit>

  Linux Kernel Rootkit - To hide modules and ssh service

## :speak\_no\_evil: related stuff

* <https://github.com/gianlucaborello/libprocesshider> ⭐ 1,131 | 🐛 11 | 🌐 C | 📅 2019-08-02

  Hide a process under Linux using the ld preloader

* <https://github.com/MatheuZSecurity/Rootkit> ⭐ 221 | 🐛 0 | 🌐 C | 📅 2025-10-22

  Collection of codes focused on Linux rootkits

* <https://github.com/landhb/DrawBridge> ⭐ 119 | 🐛 0 | 🌐 C | 📅 2023-10-14

  A layer 4 Single Packet Authentication (SPA) Module, used to conceal TCP ports on public facing machines and add an extra layer of security.

* <https://github.com/spiderpig1297/kprochide> ⭐ 23 | 🐛 0 | 🌐 C | 📅 2020-10-09

  LKM for hiding processes from the userland. The module is able to hide multiple processes and is able to dynamically receive new processes to hide.

* <https://github.com/spiderpig1297/kfile-over-icmp> ⭐ 18 | 🐛 0 | 🌐 C | 📅 2020-10-09

  kfile-over-icmp is a loadable kernel module for stealth sending of files over ICMP communication.

* <https://github.com/spiderpig1297/kunkillable> ⭐ 17 | 🐛 0 | 🌐 C | 📅 2020-09-26

  LKM (loadable kernel module) that makes userland processes unkillable.

* <https://web.archive.org/web/20140701183221/https://www.thc.org/papers/LKM_HACKING.html>

  Heroin, an LKM based rootkit, and many more LKM based rootkit techniques (it's backdated, but posses powerful knowledge).

## :mag: detection tools

Tools for detecting and analyzing rootkits:

* <https://github.com/CISOfy/lynis> ⭐ 16,177 | 🐛 218 | 🌐 Shell | 📅 2026-08-05

  Lynis - Security auditing tool for Linux, macOS, and UNIX-based systems with rootkit scanning.

* <https://github.com/draios/sysdig> ⭐ 8,286 | 🐛 116 | 🌐 C++ | 📅 2026-04-13

  Sysdig - Linux system exploration and troubleshooting tool with container support, useful for rootkit analysis.

* <https://github.com/ossec/ossec-hids> ⭐ 5,043 | 🐛 150 | 🌐 C | 📅 2026-08-12

  OSSEC is an Open Source Host-based Intrusion Detection System that performs log analysis, file integrity checking, policy monitoring, rootkit detection, real-time alerting and active response.

* <https://github.com/Sysinternals/SysmonForLinux> ⭐ 2,151 | 🐛 41 | 🌐 C | 📅 2026-07-13

  Sysmon For Linux - system monitoring tool that logs security-relevant events.

* <https://github.com/al0ne/LinuxCheck> ⭐ 2,092 | 🐛 1 | 🌐 Shell | 📅 2024-06-19

  Linux emergency response and security check tool with rootkit detection capabilities.

* <https://github.com/bad-antics/rupurt> ⭐ 11 | 🐛 1 | 🌐 C | 📅 2026-04-16

  rupurt - Advanced Linux rootkit hunter with 250+ signatures, eBPF analysis, memory forensics, and APT detection. Features real-time monitoring and comprehensive threat intelligence.

* <https://github.com/chkrootkit/chkrootkit>

  chkrootkit - locally checks for signs of a rootkit.

## Contributing

[Please refer the guidelines at contributing.md for details](CONTRIBUTING.md)

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-19._
