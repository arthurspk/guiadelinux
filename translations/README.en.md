<p align="center">
  <a href="https://github.com/arthurspk/guiadevbrasil">
    <img src="../images/guia.png" alt="Guia Dev Brasil" width="160" height="160">
  </a>
  <h1 align="center">Linux Guide</h1>
</p>

<p align="center">
  <img src="https://img.shields.io/github/stars/arthurspk/guiadelinux?style=flat-square" alt="Stars">
  <img src="https://img.shields.io/github/forks/arthurspk/guiadelinux?style=flat-square" alt="Forks">
  <img src="https://img.shields.io/github/last-commit/arthurspk/guiadelinux?style=flat-square" alt="Last commit">
  <img src="https://img.shields.io/github/license/arthurspk/guiadelinux?style=flat-square" alt="License">
  <img src="https://img.shields.io/badge/PRs-welcome-brightgreen?style=flat-square" alt="PRs Welcome">
</p>

> Complete Linux guide: learning paths, courses, books, channels, tools and communities
> to get into the field and grow. Last review: September 2026.
>
> This is a translation of the Brazilian Portuguese guide. Resources are curated for the Brazilian community, so many are in Portuguese; 🇺🇸 marks English-language content.

## 🌍 Languages
[🇧🇷 Português](../README.md) · 🇺🇸 English (you are here)

## 📚 Table of contents
- [🎯 About this guide](#-about-this-guide)
- [🗺️ Roadmap](#-roadmap)
- [🚀 Where to start](#-where-to-start)
- [🎓 Free courses](#-free-courses)
- [💰 Paid courses](#-paid-courses)
- [📖 Documentation](#-documentation)
- [📚 Books](#-books)
- [🎥 YouTube channels](#-youtube-channels)
- [🎙️ Podcasts](#-podcasts)
- [📰 Sites, blogs and newsletters](#-sites-blogs-and-newsletters)
- [🛠️ Tools](#-tools)
- [🧪 Hands-on projects and challenges](#-hands-on-projects-and-challenges)
- [🐧 Distros and desktop environments](#-distros-and-desktop-environments)
- [🤖 AI in practice](#-ai-in-practice)
- [📜 Certifications](#-certifications)
- [💼 Career and jobs](#-career-and-jobs)
- [👥 Communities](#-communities)
- [🚨 How to contribute](#-how-to-contribute)
- [📄 License](#-license)
- [💙 Support the project](#-support-the-project)

## 🎯 About this guide
Linux is the kernel created by Linus Torvalds in 1991 which, together with the GNU tools and thousands of open source projects, forms the operating system that runs the internet: practically every server, the entire cloud, the 500 biggest supercomputers, Android, the Steam Deck and the containers you will use in any back-end, DevOps, data or security job. Knowing Linux is not "a sysadmin thing" — it is the foundation of almost every technical career.

This guide is for people who have never opened a terminal and also for those who already use Linux and want to go professional (systems administration, LPI/Red Hat certifications, DevOps). **Portuguese and free** resources come first in every section; 💰 marks paid content, 🇺🇸 English-language content and 🆕 material published or updated between 2024 and 2026. Every link was verified on the date of the last review.

## 🗺️ Roadmap
- [roadmap.sh — Linux Roadmap](https://roadmap.sh/linux) — Community-made visual, interactive roadmap: from the terminal to kernel, networking, security and automation, with links per topic. 🇺🇸
- [roadmap.sh — DevOps Roadmap](https://roadmap.sh/devops) — DevOps/SRE path showing where Linux fits in a career: OS, shell, networking, containers and cloud. 🇺🇸
- [LPI Learning Materials (em português)](https://learning.lpi.org/pt/) — Official, free Linux Professional Institute path: complete Linux Essentials and LPIC-1 study materials translated into Portuguese.
- [Guia Foca GNU/Linux](https://www.guiafoca.org/) — Classic, free Brazilian guide split into Beginner, Intermediate and Advanced — a complete learning path in Portuguese.

**Summary path** (follow in order; each step has resources in the sections below):

1. **First contact** — install a friendly distro (Ubuntu, Mint, Fedora) in a virtual machine, WSL or dual boot; understand distro × kernel × desktop environment.
2. **Basic terminal** — navigation (`pwd`, `ls`, `cd`), files (`cp`, `mv`, `rm`, `mkdir`), reading (`cat`, `less`, `head`, `tail`), help (`man`, `--help`, `tldr`).
3. **Filesystem and permissions** — the hierarchy (`/etc`, `/home`, `/var`, `/usr`), users and groups, `chmod`, `chown`, `sudo`.
4. **Text and pipes** — `grep`, `find`, `sort`, `cut`, `awk`, `sed`, redirection (`>`, `>>`, `|`) and regular expressions.
5. **Processes, packages and services** — `ps`, `top`/`htop`, `kill`, `apt`/`dnf`/`pacman`, `systemctl`, `journalctl`, cron and timers.
6. **Shell scripting** — variables, conditionals, loops, functions, `ShellCheck`; automate your routine.
7. **Networking and remote access** — `ip`, `ss`, `ping`, `curl`, DNS, SSH with keys, firewall (`nftables`/`firewalld`), rsync.
8. **A real server** — spin up a VM/VPS, host a service (Nginx, a database, Docker), back it up and monitor it; move on to certifications (LPIC-1, LFCS, RHCSA) and to the [Docker Guide](https://github.com/arthurspk/guiadedocker).

## 🚀 Where to start
1. **Get a Linux at hand without formatting anything:** on Windows, install [WSL](https://learn.microsoft.com/pt-br/windows/wsl/install) (`wsl --install`); on any OS, create a virtual machine in [VirtualBox](https://www.virtualbox.org/) with [Ubuntu](https://ubuntu.com/) or try distros right in the browser with [DistroSea](https://distrosea.com/).
2. **Take an introductory course in Portuguese:** [Curso de Linux — Primeiros Passos](https://www.youtube.com/playlist?list=PLHz_AreHm4dlIXleu20uwPWFOSswqLYbV) (Curso em Vídeo) or the [Guia definitivo do Linux para iniciantes 2025](https://www.youtube.com/watch?v=ZI5ZQGEHJho).
3. **Learn the terminal in a guided way:** the official [The Linux command line for beginners](https://ubuntu.com/tutorials/command-line-for-beginners) tutorial (🇺🇸) and [Linux Survival](https://linuxsurvival.com/) (🇺🇸), interactive in the browser.
4. **Read LPI's official, free study material** — [Linux Essentials in Portuguese](https://learning.lpi.org/pt/learning-materials/010-160/) — to consolidate the fundamentals with serious material.
5. **Practise by playing:** [OverTheWire Bandit](https://overthewire.org/wargames/bandit/) (levels 0 to 10 already teach a lot) and [cmdchallenge](https://cmdchallenge.com/).
6. **Go deeper with a full course:** [Curso de Linux Básico / LPIC-1](https://www.youtube.com/playlist?list=PLucm8g_ezqNp92MmkF9p_cj4yhT-fCTl7) (Bóson Treinamentos, Portuguese) and the free book [The Linux Command Line](https://linuxcommand.org/tlcl.php) (🇺🇸).
7. **Administer a real server for 21 days** with the [Linux Upskill Challenge](https://linuxupskillchallenge.org/) (🇺🇸) and fix real scenarios on [SadServers](https://sadservers.com/) (🇺🇸).
8. **Pick a direction:** certification ([LPIC-1](https://www.lpi.org/pt-br/our-certifications/lpic-1-overview/), [LFCS](https://training.linuxfoundation.org/certification/linux-foundation-certified-sysadmin-lfcs/)), [Shell Script](https://github.com/arthurspk/guiadeshellscript), [Docker](https://github.com/arthurspk/guiadedocker) or [Cyber Security](https://github.com/arthurspk/guiadecybersecurity).

Your first 60 seconds in the terminal:

```bash
whoami                 # who am I?
pwd                    # where am I?
ls -la ~               # what is in my home folder (including hidden files)?
mkdir -p ~/lab && cd ~/lab
echo "Hello, Guia Dev Brasil" > hello.txt
cat hello.txt
man ls                 # the documentation is one command away (q to quit)
```

```bash
# Update the system (Ubuntu/Debian; use dnf on Fedora, pacman -Syu on Arch)
sudo apt update && sudo apt upgrade
# Find out what a command does before running it
tldr tar            # or: curl cheat.sh/tar
```

## 🎓 Free courses
### In Portuguese
- [Curso de Linux — Primeiros Passos (Curso em Vídeo)](https://www.youtube.com/playlist?list=PLHz_AreHm4dlIXleu20uwPWFOSswqLYbV) — Gustavo Guanabara's playlist for people who have never used Linux: installation, desktop, terminal and first commands.
- [Curso de Linux Básico / Certificação LPIC-1 (Bóson Treinamentos)](https://www.youtube.com/playlist?list=PLucm8g_ezqNp92MmkF9p_cj4yhT-fCTl7) — Fábio dos Reis' extensive playlist covering LPIC-1 objectives: commands, filesystem, processes, packages and shell.
- [Curso básico e gratuito de Linux (Prof. Juliano Ramos)](https://www.youtube.com/playlist?list=PL0IggKUxTGp0pKaB1S7pjocBxIKoxGqTt) — Video course from scratch, focused on professional use and getting job-ready.
- [Guia definitivo do Linux para iniciantes 2025 (Prof. Juliano Ramos)](https://www.youtube.com/watch?v=ZI5ZQGEHJho) — Single, up-to-date lesson summarising what a beginner needs to know before diving into the terminal. 🆕
- [Treinamento gratuito Linux Essentials — Aula 1 (Gustavo Kalau)](https://www.youtube.com/watch?v=Be31mq6O1SI) — First lesson of a free training aligned with the LPI Linux Essentials certification, published in 2025. 🆕
- [Curso Gratuito de Linux LPIC1-101 (SuGE3K)](https://www.youtube.com/playlist?list=PLyLcPK3h0D7Dyz71HYBnQc7HBTj5Mal0E) — Playlist focused on the LPIC-1 101 exam, topic by topic.
- [Curso Grátis Linux Ubuntu Desktop (Bora para Prática!!!)](https://www.youtube.com/playlist?list=PLozhsZB1lLUMHaZmvczDWugUv9ldzX37u) — For everyday Ubuntu users: installation, apps, settings and a gentle intro to the terminal.
- [O semestre que falta na sua faculdade (MIT Missing Semester, PT-BR)](https://missing-semester-pt.github.io/) — Portuguese translation of MIT's lectures on shell, scripting, editors, Git, debugging and the command line — what college doesn't teach.

### In English
- [Introduction to Linux (LFS101) — Linux Foundation](https://training.linuxfoundation.org/training/introduction-to-linux/) — Free course from the Linux Foundation itself (also on edX): history, distros, terminal, files, processes and networking. 🇺🇸
- [LinuxFoundationX: Introduction to Linux (edX)](https://www.edx.org/learn/linux/the-linux-foundation-introduction-to-linux) — edX edition of LFS101; the whole content can be audited for free. 🇺🇸
- [Red Hat Enterprise Linux Technical Overview (RH024)](https://www.redhat.com/en/services/training/rh024-red-hat-linux-technical-overview) — Red Hat's free introductory course: what Linux is, terminal, users, permissions and services on RHEL. 🇺🇸
- [Linux Unhatched (Cisco Networking Academy)](https://www.netacad.com/courses/linux-unhatched) — Free ~8-hour course with a terminal embedded in the browser — ideal for a first contact. 🇺🇸
- [Linux Essentials (Cisco Networking Academy / NDG)](https://www.netacad.com/courses/linux-essentials) — Free course aligned with the LPI Linux Essentials certification, with hands-on labs. 🇺🇸
- [The Linux command line for beginners (Ubuntu)](https://ubuntu.com/tutorials/command-line-for-beginners) — Canonical's official tutorial: why use the terminal and the essential commands, step by step. 🇺🇸
- [Hands-on Introduction to Linux Commands and Shell Scripting (IBM/Coursera)](https://www.coursera.org/learn/hands-on-introduction-to-linux-commands-and-shell-scripting) — IBM course with real labs; can be audited for free (the certificate is paid). 🇺🇸
- [Introduction to Linux – Full Course for Beginners (freeCodeCamp)](https://www.youtube.com/watch?v=sWbUDq4S6Y8) — Full 6-hour video course based on LFS101, on the freeCodeCamp channel. 🇺🇸
- [Linux Operating System – Crash Course for Beginners (freeCodeCamp)](https://www.youtube.com/watch?v=ROjZy1WbCIA) — Quick overview of how Linux works under the hood before you open the terminal. 🇺🇸
- [Linux Crash Course (Learn Linux TV)](https://www.youtube.com/playlist?list=PLT98CRl2KxKHKd_tH3ssq0HPrThx2hESW) — Ongoing playlist with one command or concept per video — great for 15 minutes of study a day. 🇺🇸
- [Linux Survival](https://linuxsurvival.com/) — Interactive in-browser tutorial that simulates a terminal and teaches the basic commands in 4 modules. 🇺🇸
- [Linux Fundamentals (Hack The Box Academy)](https://academy.hackthebox.com/course/preview/linux-fundamentals) — Free HTB Academy module: terminal, permissions, networking and tools, with labs. 🇺🇸
- [KodeKloud — cursos gratuitos](https://kodekloud.com/free-courses/) — Catalogue of free Linux, shell, Docker and DevOps courses with in-browser labs. 🇺🇸
- [A Beginner's Guide to Linux Kernel Development (LFD103)](https://training.linuxfoundation.org/training/a-beginners-guide-to-linux-kernel-development-lfd103/) — Free Linux Foundation course for future kernel contributors: patch flow, mailing lists and etiquette. 🇺🇸

## 💰 Paid courses
- [Linux Fundamentals (4Linux)](https://4linux.com.br/cursos/produto/linux-fundamentals/) — Classic Brazilian fundamentals course, the base for 4Linux's other tracks. 💰
- [Certificação Linux (Uirá Ribeiro)](https://www.certificacaolinux.com.br/) — Portuguese prep courses for LPIC-1, LPIC-2 and DevOps, with hands-on labs. 💰
- [Red Hat System Administration I (RH124)](https://www.redhat.com/en/services/training/rh124-red-hat-system-administration-i) — First official course on the RHCSA track, with RHEL labs. 💰 🇺🇸
- [Linux System Administration Essentials (LFS207)](https://training.linuxfoundation.org/training/linux-system-administration-essentials-lfs207/) — Linux Foundation course that prepares you for the LFCS certification. 💰 🇺🇸
- [LFCS Prep Course (KodeKloud)](https://kodekloud.com/courses/linux-foundation-certified-system-administrator-lfcs/) — LFCS prep course with interactive in-browser labs. 💰 🇺🇸

## 📖 Documentation
- [Linux man pages online (man7.org)](https://man7.org/linux/man-pages/) — Every Linux man page browsable online, maintained by Michael Kerrisk. Start with `man man`. 🇺🇸
- [The Linux Kernel documentation](https://www.kernel.org/doc/html/latest/) — Official kernel documentation: user guide, administration, development process and subsystems. 🇺🇸
- [kernel.org — The Linux Kernel Archives](https://www.kernel.org/) — Official kernel site: stable and LTS releases and source code. 🇺🇸
- [ArchWiki (em português)](https://wiki.archlinux.org/title/Main_page_(Portugu%C3%AAs)) — Portuguese edition of the most complete wiki in the Linux world — useful for any distro, not just Arch.
- [ArchWiki](https://wiki.archlinux.org/) — The definitive technical reference: hardware, networking, systemd, security and thousands of up-to-date articles. 🇺🇸
- [Referência Debian (em português)](https://www.debian.org/doc/manuals/debian-reference/index.pt.html) — Official Debian manual in Portuguese: administration, packages, networking and shell in depth.
- [O Manual do Administrador Debian (pt-BR)](https://debian-handbook.info/browse/pt-BR/stable/) — Official, free Debian book translated into Portuguese — required reading for servers.
- [Ubuntu Server documentation](https://ubuntu.com/server/docs/) — Official Ubuntu Server docs: installation, networking, virtualisation, containers and security. 🇺🇸
- [Official Ubuntu Documentation](https://help.ubuntu.com/) — Official Ubuntu Desktop and Server documentation portal, by release. 🇺🇸
- [Fedora Docs](https://docs.fedoraproject.org/) — Official Fedora documentation: installation and administration guides plus Quick Docs. 🇺🇸
- [Rocky Linux Documentation](https://docs.rockylinux.org/) — Official Rocky Linux (RHEL-compatible) docs — great for practising the Red Hat world for free. 🇺🇸
- [AlmaLinux Wiki](https://wiki.almalinux.org/) — Official AlmaLinux wiki, another free RHEL-compatible alternative. 🇺🇸
- [Kali Linux Documentation](https://www.kali.org/docs/) — Official Kali docs: installation, tools and offensive-security usage. 🇺🇸
- [openSUSE Documentation](https://doc.opensuse.org/) — Official openSUSE Leap and Tumbleweed manuals, including YaST and Btrfs. 🇺🇸
- [Gentoo Wiki](https://wiki.gentoo.org/) — Gentoo wiki: excellent for understanding compilation, kernel and low-level configuration. 🇺🇸
- [The Linux Documentation Project (TLDP)](https://tldp.org/) — Historical archive of HOWTOs and guides — still useful for shell and system fundamentals. 🇺🇸
- [Advanced Bash-Scripting Guide (TLDP)](https://tldp.org/LDP/abs/html/) — Classic, complete Bash guide, from basics to regular expressions and debugging. 🇺🇸
- [Bash Guide for Beginners (TLDP)](https://tldp.org/LDP/Bash-Beginners-Guide/html/) — Introductory Bash guide for people who have never written a script. 🇺🇸
- [GNU Bash Reference Manual](https://www.gnu.org/software/bash/manual/) — Official Bash manual: syntax, expansions, variables and builtins. 🇺🇸
- [GNU coreutils manual](https://www.gnu.org/software/coreutils/manual/) — Official manual for the core utilities (`ls`, `cp`, `sort`, `cut`, `chmod`…). 🇺🇸
- [BashGuide (Greg's Wiki)](https://mywiki.wooledge.org/BashGuide) — Bash guide that fixes the most common bad habits of trial-and-error learners. 🇺🇸
- [systemd.io](https://systemd.io/) — Official systemd documentation: units, services, timers, journal and boot. 🇺🇸
- [Filesystem Hierarchy Standard (FHS)](https://refspecs.linuxfoundation.org/fhs.shtml) — The standard that defines what goes in `/etc`, `/var`, `/usr` and friends. 🇺🇸
- [HOWTO do Linux kernel development](https://kernel.org/doc/html/latest/process/howto.html) — Official starting point for understanding how the kernel is developed and how to contribute. 🇺🇸
- [LPI Learning Materials — Linux Essentials (010-160)](https://learning.lpi.org/pt/learning-materials/010-160/) — Official, free LPI study material in Portuguese covering all Linux Essentials objectives.
- [LPI Learning Materials — LPIC-1 Exam 101](https://learning.lpi.org/pt/learning-materials/101-500/) — Official, free LPI material for exam 101 (architecture, installation, GNU commands, filesystems).
- [LPI Learning Materials — LPIC-1 Exam 102](https://learning.lpi.org/pt/learning-materials/102-500/) — Official, free LPI material for exam 102 (shell, UI, administration, services, networking, security).
- [The Art of Command Line (em português)](https://github.com/jlevy/the-art-of-command-line/blob/master/README-pt.md) — One page with the essentials of the command line, from basic to advanced, translated into Portuguese.
- [SS64 — índice A-Z da linha de comando Linux](https://ss64.com/bash/) — Quick reference for every command, with syntax and examples. 🇺🇸
- [Bash scripting cheatsheet (devhints)](https://devhints.io/bash) — One-page Bash cheat sheet: expansions, conditionals, loops, arrays and functions. 🇺🇸
- [Google Shell Style Guide](https://google.github.io/styleguide/shellguide.html) — Google's style guide for shell scripts — when to use Bash and how to write it well. 🇺🇸

## 📚 Books
- [The Linux Command Line (William Shotts)](https://linuxcommand.org/tlcl.php) — Free PDF book (5th edition): the best starting point to master the terminal and the shell. 🇺🇸
- [Começando com o Linux: comandos, serviços e administração (Daniel Romero, Casa do Código)](https://www.casadocodigo.com.br/products/livro-linux) — Brazilian book for a first contact: shell, files, users, packages and services. 💰
- [Administração Linux (Juliano Ramos, Casa do Código)](https://www.casadocodigo.com.br/products/livro-admin-linux) — From the first command to servers: shell scripting, SSH, RAID, Apache and proxy, in Portuguese. 💰
- [Certificação Linux: guia prático para a prova LPIC-1 101 (Casa do Código)](https://www.casadocodigo.com.br/products/livro-certificacao-linux) — Objective Portuguese manual for the LPIC-1 101 exam. 💰
- [Certificação Linux: guia prático para a prova LPIC-1 102 (Casa do Código)](https://www.casadocodigo.com.br/products/livro-certificacao-linux-2) — Follow-up for exam 102: shell, administration, services, networking and security. 💰
- [Shell Script Profissional (Aurelio Marinho Jargas)](https://www.shellscript.com.br/) — The Brazilian reference book on shell scripting, by the author of Portuguese sed/regex guides. 💰
- [How Linux Works, 3rd Edition (Brian Ward, No Starch)](https://nostarch.com/howlinuxworks3) — Explains what happens underneath: boot, kernel, devices, systemd, networking and shell. 💰 🇺🇸
- [The Linux Programming Interface (Michael Kerrisk)](https://man7.org/tlpi/) — The bible of Linux systems programming: syscalls, processes, signals, sockets. 💰 🇺🇸
- [UNIX and Linux System Administration Handbook, 5th Edition](https://www.admin.com/) — Classic systems administration reference for anyone about to run servers. 💰 🇺🇸
- [Linux Fundamentals (Paul Cobbaut, linux-training.be)](https://linux-training.be/) — Free PDF study guides: fundamentals, administration, servers, networking and security. 🇺🇸
- [linux-insides (0xAX)](https://github.com/0xAX/linux-insides) — Open book about the kernel's internals: boot, interrupts, memory and syscalls. 🇺🇸
- [Linux Device Drivers, 3rd Edition (LWN)](https://lwn.net/Kernel/LDD3/) — The classic driver book, released for free by O'Reilly/LWN. 🇺🇸
- [The Linux Commands Handbook (freeCodeCamp)](https://www.freecodecamp.org/news/the-linux-commands-handbook/) — Free handbook of the most used commands, explained one by one. 🇺🇸
- [Bite Size Linux! (Julia Evans)](https://wizardzines.com/zines/bite-size-linux/) — Illustrated zine explaining processes, signals, permissions and filesystems with drawings. 💰 🇺🇸
- [Bite Size Command Line! (Julia Evans)](https://wizardzines.com/zines/bite-size-command-line/) — Illustrated zine about `grep`, `find`, `xargs`, `awk` and other everyday commands. 💰 🇺🇸

## 🎥 YouTube channels
### In Portuguese
- [LINUXtips (Jeferson Fernando)](https://www.youtube.com/@LINUXtips) — The biggest Brazilian Linux, containers and DevOps channel, with live streams and free courses.
- [Diolinux](https://www.youtube.com/@Diolinux) — News, distro reviews, desktop tips and the Diocast podcast.
- [Bóson Treinamentos](https://www.youtube.com/@bosontreinamentos) — Complete, free courses on Linux, networking, shell scripting and certifications.
- [Ricardo Prudenciato](https://www.youtube.com/@ricardoprudenciato) — Professional Linux: LPI certifications, career and systems administration.
- [Prof. Juliano Ramos — Linux do Zero ao Hacker](https://www.youtube.com/@ProfJulianoRamos) — Free Linux, security and infrastructure courses focused on employability.
- [Daniel Donda](https://www.youtube.com/@DanielDonda) — Infrastructure, Linux, Windows and cybersecurity explained for newcomers.
- [4Linux](https://www.youtube.com/@4linux) — Open lessons and webinars from the Brazilian Linux and open source school.
- [Certificação Linux (Uirá Ribeiro)](https://www.youtube.com/@CertificacaoLinux) — Exam tips, commands and LPIC concepts in short videos.
- [Linux Descomplicado](https://www.youtube.com/@LinuxDescomplicado) — Objective terminal and administration tutorials for daily work.
- [Gustavo Kalau](https://www.youtube.com/@gustavokalau) — Free Linux Essentials and infrastructure trainings.
- [Fabio Akita (Akitando)](https://www.youtube.com/@Akitando) — Long-form videos on how computers, operating systems and Linux really work.
- [Linux Kamarada](https://www.youtube.com/@LinuxKamarada) — Channel of the Kamarada project (openSUSE in Portuguese): desktop tips and tutorials.

### In English
- [Learn Linux TV](https://www.youtube.com/@LearnLinuxTV) — Complete courses on Linux, servers, Proxmox and Ansible, with flawless teaching. 🇺🇸
- [The Linux Experiment](https://www.youtube.com/@TheLinuxEXP) — Weekly Linux desktop news, reviews and accessible explanations. 🇺🇸
- [DistroTube](https://www.youtube.com/@DistroTube) — Distros, window managers, terminal and free software, every day. 🇺🇸
- [NetworkChuck](https://www.youtube.com/@NetworkChuck) — Linux, networking and security with high-energy teaching — great for beginners. 🇺🇸
- [Chris Titus Tech](https://www.youtube.com/@ChrisTitusTech) — Installation, tuning and scripts for Linux desktops and servers. 🇺🇸
- [Veronica Explains](https://www.youtube.com/@VeronicaExplains) — Short, clear explanations of commands, hardware and Unix/Linux history. 🇺🇸
- [Brodie Robertson](https://www.youtube.com/@BrodieRobertson) — Daily news on the kernel, Wayland, distros and the community. 🇺🇸
- [The Linux Foundation](https://www.youtube.com/@LinuxfoundationOrg) — Talks from Open Source Summit, KubeCon and the foundation's projects. 🇺🇸
- [freeCodeCamp.org](https://www.youtube.com/@freecodecamp) — Complete, free courses, including Linux, Bash and DevOps. 🇺🇸
- [Linux in 100 Seconds (Fireship)](https://www.youtube.com/watch?v=rrB13utjYV4) — What Linux is in 100 seconds — to send to anyone who asks. 🇺🇸
- [TechWorld with Nana](https://www.youtube.com/@TechWorldwithNana) — DevOps from scratch: Linux, Docker, Kubernetes and CI/CD in full courses. 🇺🇸
- [KodeKloud](https://www.youtube.com/@KodeKloud) — Linux, shell and certification lessons with labs. 🇺🇸
- [Red Hat](https://www.youtube.com/@RedHat) — Red Hat's official channel: RHEL, automation and open source stories. 🇺🇸
- [Linux Professional Institute](https://www.youtube.com/@LPIConnect) — LPI's official channel: webinars on certifications and career. 🇺🇸

## 🎙️ Podcasts
- [Diocast (Diolinux)](https://diolinux.com.br/diocast) — The Brazilian weekly podcast on Linux and technology, in audio and video.
- [Diocast — "Linux vem forte em 2026. Mas o motivo está em 2025"](https://www.youtube.com/watch?v=-M-7loG48DU) — Special episode reviewing the year Linux became a mainstream topic. 🆕
- [LINUXtips — Descomplicando Tecnologia](https://podcasts.apple.com/br/podcast/linuxtips-descomplicando-tecnologia/id1418626735) — Jeferson Fernando's podcast on career, DevOps and real stories from people working with Linux.
- [Hipsters Ponto Tech — episódios sobre Linux](https://www.hipsters.tech/?s=linux) — Search of the Alura podcast episodes about Linux, open source and infrastructure.
- [LINUX Unplugged](https://linuxunplugged.com/) — The most traditional weekly Linux podcast, from Jupiter Broadcasting. 🇺🇸
- [Late Night Linux](https://latenightlinux.com/) — Relaxed news and discussions on Linux and open source. 🇺🇸
- [Linux Action News](https://linuxactionnews.com/) — Weekly 30-minute news round-up of the Linux ecosystem. 🇺🇸
- [This Week in Linux (TuxDigital)](https://tuxdigital.com/podcasts/this-week-in-linux/) — This week's news in video and audio. 🇺🇸
- [2.5 Admins](https://2.5admins.com/) — Experienced sysadmins discussing servers, ZFS, backups and news. 🇺🇸
- [Ask Noah Show](https://podcast.asknoahshow.com/) — Listener questions on Linux and open source answered live. 🇺🇸
- [Linux Downtime](https://linuxdowntime.com/) — Conversations with community members about how they use Linux. 🇺🇸
- [Hacker Public Radio](https://hackerpublicradio.org/) — Daily community podcast produced by the listeners themselves, with lots of Linux. 🇺🇸

## 📰 Sites, blogs and newsletters
- [Diolinux](https://diolinux.com.br/) — Brazilian portal for Linux and open source news, tutorials and reviews.
- [Viva o Linux](https://www.vivaolinux.com.br/) — The oldest Brazilian Linux community: forum, thousands of user-submitted articles, tips and scripts.
- [SempreUpdate](https://sempreupdate.com.br/) — Daily news on Linux, distros and free software in Portuguese.
- [Linux Descomplicado](https://www.linuxdescomplicado.com.br/) — Portuguese tutorials and newsletter on terminal and administration.
- [Terminal Root](https://terminalroot.com.br/) — Brazilian blog on terminal, shell, C/C++ and command-line tools.
- [Linux Kamarada](https://linuxkamarada.com/) — Portuguese blog focused on the Linux desktop and openSUSE.
- [Dicas-L](https://www.dicas-l.com.br/) — Daily GNU/Linux and free software tips list running since 1997.
- [Aurelio.net](https://aurelio.net/) — Aurelio Jargas' site: shell, sed, regular expressions and Vim in Portuguese.
- [freeCodeCamp em português — tag Linux](https://www.freecodecamp.org/portuguese/news/tag/linux/) — Translated articles on commands, permissions and administration.
- [LWN.net](https://lwn.net/) — The reference publication on kernel and ecosystem development; weekly e-mail edition. 🇺🇸
- [It's FOSS (+ FOSS Weekly)](https://itsfoss.com/) — Beginner tutorials, news and the FOSS Weekly newsletter. 🇺🇸
- [OMG! Ubuntu](https://www.omgubuntu.co.uk/) — Ubuntu and Linux desktop news since 2009. 🇺🇸
- [Linux Journal](https://www.linuxjournal.com/) — Historic Linux magazine with technical and opinion articles. 🇺🇸
- [Linux Handbook](https://linuxhandbook.com/) — Terminal, server and sysadmin tutorials, well organised by topic. 🇺🇸
- [TecMint](https://www.tecmint.com/) — Thousands of Linux administration how-tos. 🇺🇸
- [Opensource.com — Linux](https://opensource.com/tags/linux) — Red Hat's archive of practical articles on Linux and open source culture. 🇺🇸
- [Linux.com](https://www.linux.com/) — News and tutorials maintained by the Linux Foundation. 🇺🇸
- [Julia Evans (jvns.ca)](https://jvns.ca/) — Blog explaining processes, signals, networking and debugging visually and playfully. 🇺🇸
- [Brendan Gregg — Linux Performance](https://www.brendangregg.com/linuxperf.html) — Map of Linux performance tools by the creator of many observability commands. 🇺🇸
- [DigitalOcean Community Tutorials](https://www.digitalocean.com/community/tutorials) — Very well-written step-by-step Linux server tutorials (Nginx, SSH, firewall, databases). 🇺🇸
- [Red Hat Blog](https://www.redhat.com/en/blog) — Red Hat technical articles on RHEL, automation and sysadmin. 🇺🇸
- [Ubuntu Blog](https://ubuntu.com/blog) — Official Ubuntu, Canonical and ecosystem news. 🇺🇸
- [Kernel Newbies](https://kernelnewbies.org/) — Readable summary of each kernel release and guides for new contributors. 🇺🇸
- [console.dev](https://console.dev/) — Free weekly developer-tools newsletter, with lots of CLI and Linux. 🇺🇸

## 🛠️ Tools
### Terminal, shell and editors
- [tmux](https://github.com/tmux/tmux/wiki) — Terminal multiplexer: multiple windows and sessions that survive SSH disconnects. 🇺🇸
- [Oh My Zsh](https://ohmyz.sh/) — Zsh framework with themes, plugins and supercharged autocompletion. 🇺🇸
- [fish shell](https://fishshell.com/) — Friendly shell with suggestions and colours out of the box, no configuration. 🇺🇸
- [Starship](https://starship.rs/) — Fast, good-looking prompt that works in any shell. 🇺🇸
- [Ghostty](https://ghostty.org/) — Modern, fast, native terminal emulator released in 2024. 🆕 🇺🇸
- [Alacritty](https://alacritty.org/) — Minimal, GPU-accelerated terminal. 🇺🇸
- [kitty](https://sw.kovidgoyal.net/kitty/) — Fast terminal with images, tabs and scripting. 🇺🇸
- [WezTerm](https://wezterm.org/) — Cross-platform terminal configured in Lua. 🇺🇸
- [Vim](https://www.vim.org/) — The editor that is on every server. Learn with `vimtutor` in your terminal. 🇺🇸
- [Neovim](https://neovim.io/) — Modern Vim with Lua, LSP and a huge plugin ecosystem. 🇺🇸
- [GNU nano](https://www.nano-editor.org/) — Simple editor for editing a config file without learning Vim. 🇺🇸
- [Helix](https://helix-editor.com/) — Modern modal editor with built-in LSP and tree-sitter, no plugins needed. 🇺🇸
- [micro](https://micro-editor.github.io/) — Terminal editor with familiar shortcuts (Ctrl+S, Ctrl+Z). 🇺🇸

### Modern utilities and productivity
- [tldr pages](https://tldr.sh/) — Practical examples for every command, community-maintained — the condensed `man`. 🇺🇸
- [explainshell](https://explainshell.com/) — Paste a command and see what every flag does, pulled from the man pages. 🇺🇸
- [cheat.sh](https://cheat.sh/) — Command cheat sheets straight in the terminal: `curl cheat.sh/tar`. 🇺🇸
- [ShellCheck](https://www.shellcheck.net/) — Static analyser that points out bugs in shell scripts before you run them. 🇺🇸
- [shfmt (mvdan/sh)](https://github.com/mvdan/sh) — Shell script formatter, to standardise the team's code. 🇺🇸
- [bat](https://github.com/sharkdp/bat) — `cat` with syntax highlighting and Git integration. 🇺🇸
- [eza](https://github.com/eza-community/eza) — Modern `ls` with colours, icons and tree view. 🇺🇸
- [fd](https://github.com/sharkdp/fd) — Simple, fast alternative to `find`. 🇺🇸
- [ripgrep](https://github.com/BurntSushi/ripgrep) — Extremely fast recursive `grep` that respects `.gitignore`. 🇺🇸
- [fzf](https://github.com/junegunn/fzf) — Fuzzy finder for history, files and any list in the terminal. 🇺🇸
- [zoxide](https://github.com/ajeetdsouza/zoxide) — Smart `cd` that learns the directories you use most. 🇺🇸
- [btop](https://github.com/aristocratos/btop) — Beautiful, complete resource monitor in the terminal. 🇺🇸
- [htop](https://htop.dev/) — Interactive process viewer available on almost every distro. 🇺🇸
- [jq](https://github.com/jqlang/jq) — Command-line JSON processor — indispensable for APIs and logs. 🇺🇸
- [lazygit](https://github.com/jesseduffield/lazygit) — Terminal UI for Git. 🇺🇸
- [modern-unix](https://github.com/ibraheemdev/modern-unix) — List of modern alternatives to the classic Unix commands. 🇺🇸
- [Glances](https://nicolargo.github.io/glances/) — System monitoring on one screen, local or via web. 🇺🇸
- [Netdata](https://www.netdata.cloud/) — Real-time monitoring with ready-made dashboards, one-command install. 🇺🇸
- [Timeshift](https://github.com/linuxmint/timeshift) — System snapshots to go back in time after a bad update. 🇺🇸
- [Cockpit](https://cockpit-project.org/) — Official web console for administering Linux servers (Red Hat/Fedora/Ubuntu). 🇺🇸

### Virtualisation, containers and lab
- [Instalar o WSL (Microsoft Learn, PT-BR)](https://learn.microsoft.com/pt-br/windows/wsl/install) — Run Linux inside Windows with one command — the easiest way to start without formatting anything.
- [VS Code — Developing in WSL](https://code.visualstudio.com/docs/remote/wsl) — Edit on Windows and run on WSL's Linux, with an integrated terminal. 🇺🇸
- [VirtualBox](https://www.virtualbox.org/) — Free virtual machines to test distros risk-free. 🇺🇸
- [QEMU](https://www.qemu.org/) — Open source emulator and virtualiser — the base of KVM on Linux. 🇺🇸
- [GNOME Boxes](https://apps.gnome.org/Boxes/) — VMs in three clicks on the Linux desktop. 🇺🇸
- [Multipass](https://canonical.com/multipass) — Instant Ubuntu VMs from the command line, on any OS. 🇺🇸
- [Vagrant](https://developer.hashicorp.com/vagrant) — Reproducible lab environments described in a file. 🇺🇸
- [Distrobox](https://distrobox.it/) — Use any distro inside a container, integrated with your desktop. 🇺🇸
- [Docker](https://www.docker.com/) — Linux containers: the natural next step after mastering the terminal. 🇺🇸
- [Install Docker Engine on Ubuntu](https://docs.docker.com/engine/install/ubuntu/) — Official Docker installation guide for Ubuntu. 🇺🇸
- [Killercoda](https://killercoda.com/) — Free interactive Linux, Kubernetes and DevOps scenarios in the browser. 🇺🇸
- [Proxmox VE](https://www.proxmox.com/en/products/proxmox-virtual-environment/overview) — Open source Debian-based hypervisor, the homelab favourite. 🇺🇸

### Packages, installation and bootable media
- [Flatpak](https://flatpak.org/) — Universal, sandboxed app format for the Linux desktop. 🇺🇸
- [Flathub](https://flathub.org/) — The Flatpak app store with thousands of apps. 🇺🇸
- [Snapcraft](https://snapcraft.io/) — Canonical's snap package store. 🇺🇸
- [AppImage](https://appimage.org/) — Apps in a single executable file, no installation. 🇺🇸
- [Homebrew](https://brew.sh/) — User-space package manager that also works on Linux. 🇺🇸
- [Ventoy](https://www.ventoy.net/) — Bootable USB with several ISOs at once — just copy the files. 🇺🇸
- [balenaEtcher](https://etcher.balena.io/) — Safely flash ISOs to USB drives, on any OS. 🇺🇸
- [Rufus](https://rufus.ie/) — Bootable USB creator for those still on Windows. 🇺🇸

### Networking, security and backup
- [OpenSSH](https://www.openssh.org/) — The secure remote access every server uses; learn keys, `ssh-agent` and `scp`. 🇺🇸
- [nftables / netfilter](https://www.nftables.org/) — The Linux kernel firewall and the successor of iptables. 🇺🇸
- [firewalld](https://firewalld.org/) — Dynamic firewall manager used on Fedora, RHEL and derivatives. 🇺🇸
- [fail2ban](https://github.com/fail2ban/fail2ban) — Bans IPs that brute-force SSH and other services. 🇺🇸
- [WireGuard](https://www.wireguard.com/) — Modern, simple VPN built into the Linux kernel. 🇺🇸
- [AppArmor](https://apparmor.net/) — Mandatory access control used on Ubuntu, Debian and SUSE. 🇺🇸
- [SELinux Project](https://github.com/SELinuxProject) — Mandatory access control from the Red Hat/Fedora world. 🇺🇸
- [BorgBackup](https://www.borgbackup.org/) — Deduplicated, compressed and encrypted backups. 🇺🇸
- [restic](https://restic.net/) — Simple, secure backup for local disk, SFTP and cloud. 🇺🇸
- [Ansible Documentation](https://docs.ansible.com/) — Automate the configuration of dozens of Linux servers over SSH. 🇺🇸

### Kernel, debugging and performance
- [torvalds/linux (GitHub)](https://github.com/torvalds/linux) — Mirror of the kernel source code — browse and read how Linux is made. 🇺🇸
- [strace](https://strace.io/) — See every system call a program makes — the number one debugging tool on Linux. 🇺🇸
- [Valgrind](https://valgrind.org/) — Detects memory leaks and errors in native programs. 🇺🇸
- [perf (wiki)](https://perfwiki.github.io/) — The Linux kernel's official profiler. 🇺🇸
- [eBPF.io](https://ebpf.io/) — Introduction and tutorials on eBPF, the technology that revolutionised observability and networking in the kernel. 🇺🇸
- [bpftrace](https://github.com/bpftrace/bpftrace) — High-level tracing language on top of eBPF, for diagnostic one-liners. 🇺🇸

## 🧪 Hands-on projects and challenges
- [Linux Upskill Challenge](https://linuxupskillchallenge.org/) — Free 21-day challenge course: you administer a real server, one task per day. 🇺🇸
- [OverTheWire: Bandit](https://overthewire.org/wargames/bandit/) — Level-based security game over SSH that teaches the terminal the hard way — start at level 0. 🇺🇸
- [SadServers](https://sadservers.com/) — "Sad servers" to fix: real Linux/DevOps troubleshooting scenarios in the browser. 🇺🇸
- [cmdchallenge](https://cmdchallenge.com/) — One-liner command challenges with automatic checking. 🇺🇸
- [Bashcrawl](https://gitlab.com/slackermedia/bashcrawl) — A dungeon game played entirely with `cd`, `ls` and `cat`. 🇺🇸
- [The Command Line Murder Mystery](https://github.com/veltman/clmystery) — Solve a murder using `grep`, `sort` and `head` on text files. 🇺🇸
- [VIM Adventures](https://vim-adventures.com/) — Game that teaches Vim keys; the first levels are free. 💰 🇺🇸
- [Linux From Scratch](https://www.linuxfromscratch.org/lfs/read.html) — Build your own Linux from source — the definitive project for understanding the system. 🇺🇸
- [Beyond Linux From Scratch](https://www.linuxfromscratch.org/blfs/) — LFS continuation: add networking, X, desktop and services to the system you built. 🇺🇸
- [devops-exercises](https://github.com/bregman-arie/devops-exercises) — Thousands of Linux, networking, Docker and cloud questions and exercises to practise and prep for interviews. 🇺🇸
- [build-your-own-x](https://github.com/codecrafters-io/build-your-own-x) — Tutorials to build your own shell, operating system and container from scratch. 🇺🇸
- [Linux Kernel Labs](https://linux-kernel-labs.github.io/) — University kernel programming labs, with a ready-made VM. 🇺🇸
- [Submitting patches (kernel docs)](https://docs.kernel.org/process/submitting-patches.html) — The official guide to sending your first patch to the Linux kernel. 🇺🇸
- [awesome-selfhosted](https://github.com/awesome-selfhosted/awesome-selfhosted) — List of services to self-host — the best way to practise server administration. 🇺🇸

## 🐧 Distros and desktop environments
There is no "best distro": there is the best one for your current moment. To start, **Ubuntu, Linux Mint or Fedora**; for the corporate market, learn the **Red Hat** family (Rocky/AlmaLinux are free and compatible); to understand the system in depth, **Arch** or **Debian**. The terminal is the same on all of them.
- [Ubuntu](https://ubuntu.com/) — The most popular distro with the most tutorials online; LTS releases every 2 years. 🇺🇸
- [Ubuntu Server](https://ubuntu.com/download/server) — Same Ubuntu base without a GUI, for servers and cloud. 🇺🇸
- [Linux Mint (User Guide)](https://linuxmint-user-guide.readthedocs.io/en/latest/) — Ubuntu-based, with a familiar desktop for people coming from Windows. 🇺🇸
- [Debian](https://www.debian.org/) — The "universal operating system", base of Ubuntu and dozens of distros; Debian 13 "trixie" shipped in 2025. 🆕 🇺🇸
- [Fedora](https://fedoraproject.org/) — Cutting-edge technology sponsored by Red Hat, without being unstable. 🇺🇸
- [Pop!_OS](https://system76.com/pop) — System76's distro focused on developers and creators. 🇺🇸
- [Zorin OS](https://zorin.com/os/) — Windows/macOS-like look, made for the transition. 🇺🇸
- [elementary OS](https://elementary.io/) — Elegant, consistent desktop inspired by macOS. 🇺🇸
- [Arch Linux](https://archlinux.org/) — Minimal rolling release: you build the system your way and learn a lot on the way. 🇺🇸
- [EndeavourOS](https://endeavouros.com/) — Arch with a graphical installer and a welcoming community. 🇺🇸
- [Manjaro](https://manjaro.org/) — Easier Arch, with packages tested before they reach you. 🇺🇸
- [CachyOS](https://cachyos.org/) — Arch-based distro with performance-optimised kernel and packages; among the most searched of 2025. 🆕 🇺🇸
- [openSUSE](https://www.opensuse.org/) — Leap (stable) and Tumbleweed (rolling), with YaST and Btrfs snapshots by default. 🇺🇸
- [Rocky Linux](https://rockylinux.org/) — RHEL-compatible and free — ideal for RHCSA study. 🇺🇸
- [AlmaLinux](https://almalinux.org/) — Another community RHEL-compatible distro, maintained by the AlmaLinux OS Foundation. 🇺🇸
- [Kali Linux](https://www.kali.org/) — Offensive-security distro with hundreds of ready-to-use tools. 🇺🇸
- [Alpine Linux](https://alpinelinux.org/) — Tiny and secure — the base of a large share of Docker images. 🇺🇸
- [NixOS](https://nixos.org/) — Declarative, reproducible system: the whole configuration in one file. 🇺🇸
- [Bazzite](https://bazzite.gg/) — Immutable Fedora-based distro for gaming and the Steam Deck, one of 2024's newcomers. 🆕 🇺🇸
- [DistroWatch](https://distrowatch.com/) — Ranking, news and comparisons of every distro. 🇺🇸
- [DistroSea](https://distrosea.com/) — Try dozens of distros right in the browser, no download. 🇺🇸
- [Distrochooser](https://distrochooser.de/) — Questionnaire that suggests the ideal distro for your profile. 🇺🇸
- [GNOME](https://www.gnome.org/) — The default desktop environment of Ubuntu, Fedora and Debian. 🇺🇸
- [KDE Plasma](https://kde.org/) — Complete, highly configurable desktop; used on the Steam Deck. 🇺🇸
- [Hyprland](https://hypr.land/) — Dynamic Wayland compositor that became a craze among desktop customisers. 🆕 🇺🇸

## 🤖 AI in practice
AI assistants are great for learning Linux — and dangerous when they run commands on your behalf. The terminal has no "undo": an `rm -rf` in the wrong directory, a `chmod -R 777 /` or a `dd` to the wrong disk wipes data instantly. Use AI to **understand**, and keep your finger on the trigger to **execute**.

**For learning**
- Paste an error output (e.g. `Permission denied`, `command not found`, `No space left on device`) and ask: *"explain the likely cause and three ways to diagnose it before fixing"*.
- Ask it to explain a command **flag by flag** (`tar -xzvf`, `find . -type f -mtime -7 -exec …`) and double-check on [explainshell](https://explainshell.com/) or in the man page.
- Ask for **exercises with answer keys** on the topic you are studying (permissions, pipes, systemd, networking) and solve them in a disposable VM.
- Ask for a study plan for a certification (LPIC-1, LFCS) cross-referenced with the official exam objectives — AI gets objectives wrong; the official page does not.
- Use a **local** model with [Ollama](https://ollama.com/) to practise without sending anything to the cloud — and, as a bonus, learn to manage GPU, services and ports on Linux.

**For work**
- Tools like [GitHub Copilot CLI](https://github.com/github/copilot-cli), [Claude Code](https://code.claude.com/docs/en/overview), [Gemini CLI](https://github.com/google-gemini/gemini-cli), [ShellGPT](https://github.com/TheR1D/shell_gpt) and the [Warp](https://www.warp.dev/) terminal turn "find the 10 largest log files from the last 3 days" into a ready-made command. Good uses: generating `find`/`awk`/`jq` one-liners, drafting scripts, systemd units, firewall rules and Ansible playbooks, and explaining long `journalctl` logs.
- **Read before you run.** Run first with `--dry-run`, `-n` (rsync), `echo` in front, or in a VM. Prefer tools that ask for confirmation before executing (all of the above have that mode — do not turn it off).
- Run generated scripts through [ShellCheck](https://www.shellcheck.net/) and test with `bash -n script.sh`. If a script uses `rm -rf "$VAR/"` without `set -u` and without checking whether `$VAR` is empty, it is wrong.
- Never run as root what the AI suggested without understanding it; never paste `curl … | sudo bash` from a source you do not know.

**Limits and good practices**
- AI **makes up flags and package names**, mixes distro syntax (`apt` × `dnf` × `pacman`) and suggests outdated solutions (`ifconfig`, `service`, `iptables`) where today you use `ip`, `systemctl` and `nftables`. Confirm in the [man page](https://man7.org/linux/man-pages/) or on the [ArchWiki](https://wiki.archlinux.org/).
- It cannot see your system: state your distro, version and the output of diagnostic commands (`uname -a`, `lsb_release -a`, `df -h`, `systemctl status`) so you do not get guesses.
- Do not paste SSH keys, passwords, `/etc/shadow`, cloud tokens or customer data into tools without your company's policy. On production servers, follow the team's change process.
- Understand what you accept: in an interview and in a production incident, the command is yours.

**AI tools for the terminal and for running models on Linux:**
- [GitHub Copilot CLI](https://github.com/github/copilot-cli) — Copilot agent in the terminal: explains and suggests commands and runs tasks with your approval. 🆕 🇺🇸
- [Claude Code](https://code.claude.com/docs/en/overview) — Anthropic's coding agent for the terminal; runs commands, edits files and asks permission before acting. 🆕 🇺🇸
- [Gemini CLI](https://github.com/google-gemini/gemini-cli) — Google's open source terminal agent, with a generous free tier. 🆕 🇺🇸
- [OpenAI Codex CLI](https://github.com/openai/codex) — OpenAI's lightweight coding agent that runs locally in the terminal. 🆕 🇺🇸
- [Amazon Q Developer CLI](https://aws.amazon.com/q/developer/) — AI autocomplete and chat in the terminal, focused on AWS and shell. 🆕 🇺🇸
- [Warp](https://www.warp.dev/) — Terminal with built-in AI (on Linux since 2024): write in natural language and get the command. 🆕 🇺🇸
- [ShellGPT](https://github.com/TheR1D/shell_gpt) — Generate and run shell commands from a description, using the model of your choice. 🇺🇸
- [aichat](https://github.com/sigoden/aichat) — All-in-one LLM CLI with a "shell assistant" and support for dozens of providers, including local ones. 🆕 🇺🇸
- [Ollama](https://ollama.com/) — Run language models locally on Linux with one command (`ollama run llama3`). 🆕 🇺🇸
- [llama.cpp](https://github.com/ggml-org/llama.cpp) — LLM inference in C/C++ — the base of Ollama and the lightest way to run models on any Linux box. 🇺🇸
- [Open WebUI](https://github.com/open-webui/open-webui) — Self-hosted web UI to chat with local models (Ollama) — a great server project. 🆕 🇺🇸

## 📜 Certifications
Linux is one of the few fields where certification really matters in Brazil: **LPIC-1** and **RHCSA** show up in infrastructure and support job posts, and **LFCS** is growing together with DevOps. All the exams below are hands-on or heavily command-based — study in a terminal, not on slides. LPI publishes [official free study materials in Portuguese](https://learning.lpi.org/pt/) for Linux Essentials and LPIC-1.
- [LPI Linux Essentials](https://www.lpi.org/pt-br/our-certifications/linux-essentials-overview/) — LPI's entry-level certification, no prerequisites; the exam is available in Portuguese.
- [LPIC-1: Linux Administrator](https://www.lpi.org/pt-br/our-certifications/lpic-1-overview/) — The most recognised Linux certification in Brazil (exams 101 and 102), distro-neutral.
- [LPIC-2: Linux Engineer](https://www.lpi.org/pt-br/our-certifications/lpic-2-overview/) — Advanced level: kernel, storage, networking, services and security.
- [LPIC-3: Mixed Environments](https://www.lpi.org/pt-br/our-certifications/lpic-3-300-overview/) — Top of the LPI track, with specialisations (mixed environments, security, virtualisation, high availability).
- [LFCS — Linux Foundation Certified System Administrator](https://training.linuxfoundation.org/certification/linux-foundation-certified-sysadmin-lfcs/) — The Linux Foundation's 100% hands-on terminal exam, highly valued in DevOps. 🇺🇸
- [LFCA — Linux Foundation Certified IT Associate](https://training.linuxfoundation.org/certification/certified-it-associate/) — The Linux Foundation's entry-level certification: Linux, cloud and DevOps fundamentals. 🇺🇸
- [CompTIA Linux+ (V8)](https://www.comptia.org/en-us/certifications/linux/) — CompTIA's vendor-neutral certification, refreshed in 2025 with focus on automation, containers and security. 🆕 🇺🇸
- [RHCSA — Red Hat Certified System Administrator](https://www.redhat.com/pt-br/services/certification/rhcsa) — Red Hat's hands-on exam, a reference in the Brazilian corporate market.
- [Certificações Red Hat (catálogo, incl. RHCE)](https://www.redhat.com/pt-br/services/certifications) — Official Portuguese page with the whole Red Hat track: RHCSA, RHCE, OpenShift and Ansible.
- [Guia de Certificações (Guia Dev Brasil)](https://github.com/arthurspk/guiadecertificacoes) — Sister guide with an overview of IT certifications, including Linux and cloud.

## 💼 Career and jobs
Linux is a requirement in infrastructure, technical support, DevOps/SRE, security, data and back-end jobs. Common roles in Brazil: support analyst, systems administrator (sysadmin), infrastructure/cloud engineer, DevOps/SRE and security analyst. Tip: in the GitHub job repositories below, search open issues for "Linux", "sysadmin" or "DevOps".
- [2025 Stack Overflow Developer Survey](https://survey.stackoverflow.co/2025/) — Linux remains the most used OS among professional developers worldwide. 🆕 🇺🇸
- [2024 State of Tech Talent Report (Linux Foundation)](https://www.linuxfoundation.org/research/open-source-jobs-report-2024) — Linux Foundation report on demand for Linux, cloud and open source skills. 🆕 🇺🇸
- [Programathor — vagas Linux](https://programathor.com.br/jobs-linux) — Tech jobs in Brazil asking for Linux.
- [Programathor — vagas DevOps](https://programathor.com.br/jobs-devops) — DevOps/SRE jobs, where Linux is a basic requirement.
- [GeekHunter](https://www.geekhunter.com/pt) — Brazilian platform where companies make offers to tech professionals.
- [Coodesh](https://coodesh.com/) — Tech jobs in Brazil with standardised hiring processes.
- [Remotar](https://remotar.com.br/) — 100% remote jobs for Brazilians.
- [backend-br/vagas](https://github.com/backend-br/vagas) — Back-end and infrastructure jobs posted as GitHub issues — search for "Linux".
- [CangaceirosDevels/vagas_de_emprego](https://github.com/CangaceirosDevels/vagas_de_emprego) — Tech jobs on GitHub, many in infrastructure and support.
- [RemoteOK — vagas Linux](https://remoteok.com/remote-linux-jobs) — International remote jobs with Linux. 🇺🇸
- [Tech Interview Handbook](https://www.techinterviewhandbook.org/) — Complete preparation for technical interviews. 🇺🇸
- [Guia de Shell Script (Guia Dev Brasil)](https://github.com/arthurspk/guiadeshellscript) — Natural next step: automate everything you learned in the terminal.
- [Guia de Redes (Guia Dev Brasil)](https://github.com/arthurspk/guiaderedes) — Computer networking — the other half of a Linux administrator's job.
- [Guia de Docker (Guia Dev Brasil)](https://github.com/arthurspk/guiadedocker) — Containers are Linux: move on to Docker once the terminal feels comfortable.
- [Guia de Cyber Security (Guia Dev Brasil)](https://github.com/arthurspk/guiadecybersecurity) — For those heading into security — Kali, hardening and CTFs.

## 👥 Communities
- [Diolinux Plus](https://plus.diolinux.com.br/) — Diolinux's Brazilian forum: installation, hardware and desktop questions answered fast.
- [Debian Brasil](https://debianbrasil.org.br/) — Brazilian Debian community: events, translation and help channels.
- [r/linuxbrasil](https://www.reddit.com/r/linuxbrasil/) — Portuguese-language Linux subreddit.
- [Lista de grupos de tecnologia no Telegram (TI-Brasil)](https://github.com/TI-Brasil/lista-telegram-brasil) — Directory of Brazilian Telegram groups, including Linux, distros and sysadmin.
- [Latinoware](https://latinoware.org/) — Latin America's largest free software conference, in Foz do Iguaçu.
- [TabNews](https://www.tabnews.com.br/) — Brazilian technical content community created by Filipe Deschamps.
- [He4rt Developers](https://heartdevs.com/) — Brazilian open source community with an active Discord.
- [Desenvolvedores Brasil (Discord)](https://discord.com/invite/t3vYGUuK6P) — Brazilian community with infrastructure, Linux and jobs channels.
- [Arch Linux Forums](https://bbs.archlinux.org/) — Official Arch forum — top-notch technical answers. 🇺🇸
- [Fedora Discussion](https://discussion.fedoraproject.org/) — Fedora's official forum. 🇺🇸
- [Ubuntu Community Hub](https://discourse.ubuntu.com/) — Ubuntu's official community Discourse. 🇺🇸
- [Linux Mint Community](https://community.linuxmint.com/) — Mint's community site: tutorials, compatible hardware and ideas. 🇺🇸
- [r/linux](https://www.reddit.com/r/linux/) — The biggest Linux subreddit. 🇺🇸
- [r/linux4noobs](https://www.reddit.com/r/linux4noobs/) — Subreddit for beginners — no question is silly. 🇺🇸
- [Fosstodon](https://fosstodon.org/) — Mastodon instance of the free software community. 🇺🇸
- [lore.kernel.org](https://lore.kernel.org/) — Public archive of the kernel mailing lists — where Linux is actually discussed. 🇺🇸

## 🚨 How to contribute
Found a broken link, a new course or a tool that deserves to be here? Open an issue using the repository templates or send a pull request. Criteria: working link, legal content that is free or clearly marked as paid, with a one-line description. Details in [CONTRIBUTING.md](../CONTRIBUTING.md).

## 📄 License
This project is under the [MIT](../LICENSE) license. Made with 💙 by [Arthur Coutinho (@arthurspk)](https://github.com/arthurspk) and the [Guia Dev Brasil](https://github.com/arthurspk/guiadevbrasil) community.

## 💙 Support the project
Star this repository and the [main guide](https://github.com/arthurspk/guiadevbrasil), share it with someone who is starting out and follow the project on social media:

[<img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">](https://github.com/arthurspk)
[<img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">](https://www.linkedin.com/in/arthurspk/)
[<img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white" alt="X (Twitter)">](https://x.com/manotoquinho)
[<img src="https://img.shields.io/badge/instagram-%23E4405F.svg?&style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram">](https://www.instagram.com/arthurspk/)
[<img src="https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white" alt="Facebook">](https://www.facebook.com/seixasqlc/)
