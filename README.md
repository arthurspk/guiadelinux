<p align="center">
  <a href="https://github.com/arthurspk/guiadevbrasil">
    <img src="./images/guia.png" alt="Guia Dev Brasil" width="160" height="160">
  </a>
  <h1 align="center">Guia de Linux</h1>
</p>

<p align="center">
  <img src="https://img.shields.io/github/stars/arthurspk/guiadelinux?style=flat-square" alt="Stars">
  <img src="https://img.shields.io/github/forks/arthurspk/guiadelinux?style=flat-square" alt="Forks">
  <img src="https://img.shields.io/github/last-commit/arthurspk/guiadelinux?style=flat-square" alt="Último commit">
  <img src="https://img.shields.io/github/license/arthurspk/guiadelinux?style=flat-square" alt="Licença">
  <img src="https://img.shields.io/badge/PRs-welcome-brightgreen?style=flat-square" alt="PRs Welcome">
</p>

> Guia completo de Linux: trilhas, cursos, livros, canais, ferramentas e comunidades
> para você entrar e evoluir na área. Última revisão: setembro/2026.

## 🌍 Idiomas
🇧🇷 Português (você está aqui) · [🇺🇸 English](./translations/README.en.md)

## 📚 Sumário
- [🎯 Sobre este guia](#-sobre-este-guia)
- [🗺️ Roadmap](#-roadmap)
- [🚀 Por onde começar](#-por-onde-começar)
- [🎓 Cursos gratuitos](#-cursos-gratuitos)
- [💰 Cursos pagos](#-cursos-pagos)
- [📖 Documentação e apostilas](#-documentação-e-apostilas)
- [📚 Livros](#-livros)
- [🎥 Canais no YouTube](#-canais-no-youtube)
- [🎙️ Podcasts](#-podcasts)
- [📰 Sites, blogs e newsletters](#-sites-blogs-e-newsletters)
- [🛠️ Ferramentas](#-ferramentas)
- [🧪 Projetos práticos e desafios](#-projetos-práticos-e-desafios)
- [🐧 Distros e ambientes de desktop](#-distros-e-ambientes-de-desktop)
- [🤖 IA na prática](#-ia-na-prática)
- [📜 Certificações](#-certificações)
- [💼 Carreira e vagas](#-carreira-e-vagas)
- [👥 Comunidades](#-comunidades)
- [🚨 Como contribuir](#-como-contribuir)
- [📄 Licença](#-licença)
- [💙 Apoie o projeto](#-apoie-o-projeto)

## 🎯 Sobre este guia
Linux é o kernel criado por Linus Torvalds em 1991 que, junto com as ferramentas GNU e milhares de projetos open source, forma o sistema operacional que roda a internet: praticamente todos os servidores, a nuvem inteira, os 500 maiores supercomputadores, o Android, o Steam Deck e os containers que você vai usar em qualquer vaga de back-end, DevOps, dados ou segurança. Saber Linux não é "coisa de sysadmin" — é a base de quase toda carreira técnica.

Este guia é para quem nunca abriu um terminal e também para quem já usa Linux e quer se profissionalizar (administração de sistemas, certificações LPI/Red Hat, DevOps). Os recursos em **português e gratuitos** vêm primeiro em cada seção; 💰 marca conteúdo pago, 🇺🇸 conteúdo em inglês e 🆕 material publicado ou atualizado entre 2024 e 2026. Todo link foi verificado na data da última revisão.

## 🗺️ Roadmap
- [roadmap.sh — Linux Roadmap](https://roadmap.sh/linux) — Roadmap visual e interativo da comunidade: do terminal a kernel, rede, segurança e automação, com links por tópico. 🇺🇸
- [roadmap.sh — DevOps Roadmap](https://roadmap.sh/devops) — Trilha de DevOps/SRE que mostra onde o Linux entra na carreira: sistema operacional, shell, rede, containers e nuvem. 🇺🇸
- [LPI Learning Materials (em português)](https://learning.lpi.org/pt/) — Trilha oficial e gratuita do Linux Professional Institute: apostilas completas de Linux Essentials e LPIC-1 traduzidas para o português.
- [Guia Foca GNU/Linux](https://www.guiafoca.org/) — Guia brasileiro clássico e gratuito, dividido em Iniciante, Intermediário e Avançado — uma trilha completa em português.

**Trilha resumida** (siga na ordem; cada etapa tem recursos nas seções abaixo):

1. **Primeiro contato** — instale uma distro amigável (Ubuntu, Mint, Fedora) em máquina virtual, WSL ou dual boot; entenda distro × kernel × ambiente de desktop.
2. **Terminal básico** — navegação (`pwd`, `ls`, `cd`), arquivos (`cp`, `mv`, `rm`, `mkdir`), leitura (`cat`, `less`, `head`, `tail`), ajuda (`man`, `--help`, `tldr`).
3. **Sistema de arquivos e permissões** — a hierarquia (`/etc`, `/home`, `/var`, `/usr`), usuários e grupos, `chmod`, `chown`, `sudo`.
4. **Texto e pipes** — `grep`, `find`, `sort`, `cut`, `awk`, `sed`, redirecionamento (`>`, `>>`, `|`) e expressões regulares.
5. **Processos, pacotes e serviços** — `ps`, `top`/`htop`, `kill`, `apt`/`dnf`/`pacman`, `systemctl`, `journalctl`, cron e timers.
6. **Shell script** — variáveis, condicionais, loops, funções, `ShellCheck`; automatize sua rotina.
7. **Rede e acesso remoto** — `ip`, `ss`, `ping`, `curl`, DNS, SSH com chaves, firewall (`nftables`/`firewalld`), rsync.
8. **Servidor de verdade** — suba uma VM/VPS, hospede um serviço (Nginx, banco de dados, Docker), faça backup e monitore; siga para certificações (LPIC-1, LFCS, RHCSA) e para o [Guia de Docker](https://github.com/arthurspk/guiadedocker).

## 🚀 Por onde começar
1. **Tenha um Linux à mão sem formatar nada:** no Windows, instale o [WSL](https://learn.microsoft.com/pt-br/windows/wsl/install) (`wsl --install`); em qualquer sistema, crie uma máquina virtual no [VirtualBox](https://www.virtualbox.org/) com o [Ubuntu](https://ubuntu.com/) ou teste distros direto no navegador com o [DistroSea](https://distrosea.com/).
2. **Faça um curso introdutório em português:** [Curso de Linux — Primeiros Passos](https://www.youtube.com/playlist?list=PLHz_AreHm4dlIXleu20uwPWFOSswqLYbV) (Curso em Vídeo) ou o [Guia definitivo do Linux para iniciantes 2025](https://www.youtube.com/watch?v=ZI5ZQGEHJho).
3. **Aprenda o terminal de forma guiada:** o tutorial oficial [The Linux command line for beginners](https://ubuntu.com/tutorials/command-line-for-beginners) (🇺🇸) e o [Linux Survival](https://linuxsurvival.com/) (🇺🇸), interativo no navegador.
4. **Leia a apostila oficial e gratuita da LPI** — [Linux Essentials em português](https://learning.lpi.org/pt/learning-materials/010-160/) — para consolidar os fundamentos com um material sério.
5. **Pratique jogando:** [OverTheWire Bandit](https://overthewire.org/wargames/bandit/) (níveis 0 a 10 já ensinam muito) e o [cmdchallenge](https://cmdchallenge.com/).
6. **Aprofunde com um curso completo:** [Curso de Linux Básico / LPIC-1](https://www.youtube.com/playlist?list=PLucm8g_ezqNp92MmkF9p_cj4yhT-fCTl7) (Bóson Treinamentos) e o livro gratuito [The Linux Command Line](https://linuxcommand.org/tlcl.php) (🇺🇸).
7. **Administre um servidor de verdade por 21 dias** com o [Linux Upskill Challenge](https://linuxupskillchallenge.org/) (🇺🇸) e conserte cenários reais no [SadServers](https://sadservers.com/) (🇺🇸).
8. **Escolha um rumo:** certificação ([LPIC-1](https://www.lpi.org/pt-br/our-certifications/lpic-1-overview/), [LFCS](https://training.linuxfoundation.org/certification/linux-foundation-certified-sysadmin-lfcs/)), [Shell Script](https://github.com/arthurspk/guiadeshellscript), [Docker](https://github.com/arthurspk/guiadedocker) ou [Cyber Security](https://github.com/arthurspk/guiadecybersecurity).

Seus primeiros 60 segundos no terminal:

```bash
whoami                 # quem sou eu?
pwd                    # onde estou?
ls -la ~               # o que há na minha pasta pessoal (incluindo ocultos)?
mkdir -p ~/lab && cd ~/lab
echo "Olá, Guia Dev Brasil" > ola.txt
cat ola.txt
man ls                 # a documentação está a um comando de distância (q para sair)
```

```bash
# Atualize o sistema (Ubuntu/Debian; use dnf no Fedora, pacman -Syu no Arch)
sudo apt update && sudo apt upgrade
# Descubra o que um comando faz antes de rodar
tldr tar            # ou: curl cheat.sh/tar
```

## 🎓 Cursos gratuitos
### Em português
- [Curso de Linux — Primeiros Passos (Curso em Vídeo)](https://www.youtube.com/playlist?list=PLHz_AreHm4dlIXleu20uwPWFOSswqLYbV) — Playlist do Gustavo Guanabara para quem nunca usou Linux: instalação, interface, terminal e primeiros comandos.
- [Curso de Linux Básico / Certificação LPIC-1 (Bóson Treinamentos)](https://www.youtube.com/playlist?list=PLucm8g_ezqNp92MmkF9p_cj4yhT-fCTl7) — Playlist extensa do Fábio dos Reis cobrindo os objetivos da LPIC-1: comandos, sistema de arquivos, processos, pacotes e shell.
- [Curso básico e gratuito de Linux (Prof. Juliano Ramos)](https://www.youtube.com/playlist?list=PL0IggKUxTGp0pKaB1S7pjocBxIKoxGqTt) — Curso em vídeo do zero, com foco em uso profissional e preparação para o mercado.
- [Guia definitivo do Linux para iniciantes 2025 (Prof. Juliano Ramos)](https://www.youtube.com/watch?v=ZI5ZQGEHJho) — Aula única e atualizada que resume o que um iniciante precisa saber antes de mergulhar no terminal. 🆕
- [Treinamento gratuito Linux Essentials — Aula 1 (Gustavo Kalau)](https://www.youtube.com/watch?v=Be31mq6O1SI) — Primeira aula de um treinamento gratuito alinhado à certificação LPI Linux Essentials, publicado em 2025. 🆕
- [Curso Gratuito de Linux LPIC1-101 (SuGE3K)](https://www.youtube.com/playlist?list=PLyLcPK3h0D7Dyz71HYBnQc7HBTj5Mal0E) — Playlist focada na prova 101 da LPIC-1, tópico a tópico.
- [Curso Grátis Linux Ubuntu Desktop (Bora para Prática!!!)](https://www.youtube.com/playlist?list=PLozhsZB1lLUMHaZmvczDWugUv9ldzX37u) — Para quem quer usar Ubuntu no dia a dia: instalação, aplicativos, configurações e terminal sem sustos.
- [O semestre que falta na sua faculdade (MIT Missing Semester, PT-BR)](https://missing-semester-pt.github.io/) — Tradução das aulas do MIT sobre shell, scripts, editores, Git, depuração e linha de comando — o que a faculdade não ensina.

### Em inglês
- [Introduction to Linux (LFS101) — Linux Foundation](https://training.linuxfoundation.org/training/introduction-to-linux/) — Curso gratuito da própria Linux Foundation (também no edX): história, distros, terminal, arquivos, processos e rede. 🇺🇸
- [LinuxFoundationX: Introduction to Linux (edX)](https://www.edx.org/learn/linux/the-linux-foundation-introduction-to-linux) — Versão no edX do LFS101, com opção de auditar gratuitamente todo o conteúdo. 🇺🇸
- [Red Hat Enterprise Linux Technical Overview (RH024)](https://www.redhat.com/en/services/training/rh024-red-hat-linux-technical-overview) — Curso introdutório gratuito da Red Hat: o que é Linux, terminal, usuários, permissões e serviços em RHEL. 🇺🇸
- [Linux Unhatched (Cisco Networking Academy)](https://www.netacad.com/courses/linux-unhatched) — Curso gratuito de ~8 horas com terminal embutido no navegador — ideal para o primeiro contato. 🇺🇸
- [Linux Essentials (Cisco Networking Academy / NDG)](https://www.netacad.com/courses/linux-essentials) — Curso gratuito alinhado à certificação LPI Linux Essentials, com laboratórios práticos. 🇺🇸
- [The Linux command line for beginners (Ubuntu)](https://ubuntu.com/tutorials/command-line-for-beginners) — Tutorial oficial da Canonical: por que usar o terminal e os comandos essenciais, passo a passo. 🇺🇸
- [Hands-on Introduction to Linux Commands and Shell Scripting (IBM/Coursera)](https://www.coursera.org/learn/hands-on-introduction-to-linux-commands-and-shell-scripting) — Curso da IBM com laboratórios reais; pode ser auditado gratuitamente (o certificado é pago). 🇺🇸
- [Introduction to Linux – Full Course for Beginners (freeCodeCamp)](https://www.youtube.com/watch?v=sWbUDq4S6Y8) — Curso completo em vídeo de 6 horas baseado no LFS101, no canal do freeCodeCamp. 🇺🇸
- [Linux Operating System – Crash Course for Beginners (freeCodeCamp)](https://www.youtube.com/watch?v=ROjZy1WbCIA) — Visão rápida de como o Linux funciona por dentro antes de você abrir o terminal. 🇺🇸
- [Linux Crash Course (Learn Linux TV)](https://www.youtube.com/playlist?list=PLT98CRl2KxKHKd_tH3ssq0HPrThx2hESW) — Playlist em andamento com um comando ou conceito por vídeo — ótima para estudar 15 minutos por dia. 🇺🇸
- [Linux Survival](https://linuxsurvival.com/) — Tutorial interativo no navegador que simula um terminal e ensina os comandos básicos em 4 módulos. 🇺🇸
- [Linux Fundamentals (Hack The Box Academy)](https://academy.hackthebox.com/course/preview/linux-fundamentals) — Módulo gratuito da HTB Academy: terminal, permissões, rede e ferramentas, com laboratórios. 🇺🇸
- [KodeKloud — cursos gratuitos](https://kodekloud.com/free-courses/) — Catálogo de cursos gratuitos de Linux, shell, Docker e DevOps com laboratórios no navegador. 🇺🇸
- [A Beginner's Guide to Linux Kernel Development (LFD103)](https://training.linuxfoundation.org/training/a-beginners-guide-to-linux-kernel-development-lfd103/) — Curso gratuito da Linux Foundation para quem quer contribuir com o kernel: fluxo de patches, listas e etiqueta. 🇺🇸

## 💰 Cursos pagos
- [Linux Fundamentals (4Linux)](https://4linux.com.br/cursos/produto/linux-fundamentals/) — Curso brasileiro clássico de fundamentos, base para as demais formações da 4Linux. 💰
- [Certificação Linux (Uirá Ribeiro)](https://www.certificacaolinux.com.br/) — Cursos preparatórios em português para LPIC-1, LPIC-2 e DevOps, com laboratórios práticos. 💰
- [Red Hat System Administration I (RH124)](https://www.redhat.com/en/services/training/rh124-red-hat-system-administration-i) — Primeiro curso oficial da trilha RHCSA, com laboratórios em RHEL. 💰 🇺🇸
- [Linux System Administration Essentials (LFS207)](https://training.linuxfoundation.org/training/linux-system-administration-essentials-lfs207/) — Curso da Linux Foundation que prepara para a certificação LFCS. 💰 🇺🇸
- [LFCS Prep Course (KodeKloud)](https://kodekloud.com/courses/linux-foundation-certified-system-administrator-lfcs/) — Preparatório para a LFCS com laboratórios interativos no navegador. 💰 🇺🇸

## 📖 Documentação e apostilas
- [Linux man pages online (man7.org)](https://man7.org/linux/man-pages/) — Todas as man pages do Linux navegáveis no navegador, mantidas por Michael Kerrisk. Comece por `man man`. 🇺🇸
- [The Linux Kernel documentation](https://www.kernel.org/doc/html/latest/) — Documentação oficial do kernel: guia do usuário, administração, processo de desenvolvimento e subsistemas. 🇺🇸
- [kernel.org — The Linux Kernel Archives](https://www.kernel.org/) — Site oficial do kernel: versões estáveis, LTS e código-fonte. 🇺🇸
- [ArchWiki (em português)](https://wiki.archlinux.org/title/Main_page_(Portugu%C3%AAs)) — Versão em português da wiki mais completa do mundo Linux — serve para qualquer distro, não só Arch.
- [ArchWiki](https://wiki.archlinux.org/) — Referência técnica definitiva: hardware, rede, systemd, segurança e milhares de artigos atualizados. 🇺🇸
- [Referência Debian (em português)](https://www.debian.org/doc/manuals/debian-reference/index.pt.html) — Manual oficial do Debian traduzido: administração, pacotes, rede e shell em profundidade.
- [O Manual do Administrador Debian (pt-BR)](https://debian-handbook.info/browse/pt-BR/stable/) — Livro oficial e gratuito do Debian, traduzido para o português — leitura obrigatória para servidores.
- [Ubuntu Server documentation](https://ubuntu.com/server/docs/) — Documentação oficial do Ubuntu Server: instalação, rede, virtualização, containers e segurança. 🇺🇸
- [Official Ubuntu Documentation](https://help.ubuntu.com/) — Portal de documentação oficial do Ubuntu Desktop e Server por versão. 🇺🇸
- [Fedora Docs](https://docs.fedoraproject.org/) — Documentação oficial do Fedora: guias de instalação, administração e Quick Docs. 🇺🇸
- [Rocky Linux Documentation](https://docs.rockylinux.org/) — Docs oficiais do Rocky Linux (compatível com RHEL) — bom para praticar o mundo Red Hat de graça. 🇺🇸
- [AlmaLinux Wiki](https://wiki.almalinux.org/) — Wiki oficial do AlmaLinux, outra alternativa gratuita compatível com RHEL. 🇺🇸
- [Kali Linux Documentation](https://www.kali.org/docs/) — Docs oficiais do Kali: instalação, ferramentas e uso em segurança ofensiva. 🇺🇸
- [openSUSE Documentation](https://doc.opensuse.org/) — Manuais oficiais do openSUSE Leap e Tumbleweed, incluindo YaST e Btrfs. 🇺🇸
- [Gentoo Wiki](https://wiki.gentoo.org/) — Wiki do Gentoo: excelente para entender compilação, kernel e configuração de baixo nível. 🇺🇸
- [The Linux Documentation Project (TLDP)](https://tldp.org/) — Acervo histórico de HOWTOs e guias — ainda útil para fundamentos de shell e sistema. 🇺🇸
- [Advanced Bash-Scripting Guide (TLDP)](https://tldp.org/LDP/abs/html/) — Guia clássico e completo de Bash, do básico a expressões regulares e depuração. 🇺🇸
- [Bash Guide for Beginners (TLDP)](https://tldp.org/LDP/Bash-Beginners-Guide/html/) — Guia introdutório de Bash para quem nunca escreveu um script. 🇺🇸
- [GNU Bash Reference Manual](https://www.gnu.org/software/bash/manual/) — Manual oficial do Bash: sintaxe, expansões, variáveis e builtins. 🇺🇸
- [GNU coreutils manual](https://www.gnu.org/software/coreutils/manual/) — Manual oficial dos utilitários básicos (`ls`, `cp`, `sort`, `cut`, `chmod`…). 🇺🇸
- [BashGuide (Greg's Wiki)](https://mywiki.wooledge.org/BashGuide) — Guia de Bash que corrige os vícios mais comuns de quem aprende por tentativa e erro. 🇺🇸
- [systemd.io](https://systemd.io/) — Documentação oficial do systemd: unidades, serviços, timers, journal e boot. 🇺🇸
- [Filesystem Hierarchy Standard (FHS)](https://refspecs.linuxfoundation.org/fhs.shtml) — Padrão que define o que vai em `/etc`, `/var`, `/usr` e companhia. 🇺🇸
- [HOWTO do Linux kernel development](https://kernel.org/doc/html/latest/process/howto.html) — Ponto de partida oficial para entender como o kernel é desenvolvido e como contribuir. 🇺🇸
- [LPI Learning Materials — Linux Essentials (010-160)](https://learning.lpi.org/pt/learning-materials/010-160/) — Apostila oficial e gratuita da LPI em português, cobrindo todos os objetivos da Linux Essentials.
- [LPI Learning Materials — LPIC-1 Exam 101](https://learning.lpi.org/pt/learning-materials/101-500/) — Apostila oficial e gratuita da LPI para a prova 101 (arquitetura, instalação, comandos GNU, sistema de arquivos).
- [LPI Learning Materials — LPIC-1 Exam 102](https://learning.lpi.org/pt/learning-materials/102-500/) — Apostila oficial e gratuita da LPI para a prova 102 (shell, interface, administração, serviços, rede, segurança).
- [The Art of Command Line (em português)](https://github.com/jlevy/the-art-of-command-line/blob/master/README-pt.md) — Uma página com o essencial da linha de comando, do básico ao avançado, traduzida para o português.
- [SS64 — índice A-Z da linha de comando Linux](https://ss64.com/bash/) — Referência rápida de todos os comandos, com sintaxe e exemplos. 🇺🇸
- [Bash scripting cheatsheet (devhints)](https://devhints.io/bash) — Folha de cola de Bash em uma página: expansões, condicionais, loops, arrays e funções. 🇺🇸
- [Google Shell Style Guide](https://google.github.io/styleguide/shellguide.html) — Guia de estilo do Google para scripts shell — quando usar Bash e como escrevê-lo bem. 🇺🇸

## 📚 Livros
- [The Linux Command Line (William Shotts)](https://linuxcommand.org/tlcl.php) — Livro gratuito em PDF (5ª edição): o melhor ponto de partida para dominar o terminal e o shell. 🇺🇸
- [Começando com o Linux: comandos, serviços e administração (Daniel Romero, Casa do Código)](https://www.casadocodigo.com.br/products/livro-linux) — Livro brasileiro para o primeiro contato: shell, arquivos, usuários, pacotes e serviços. 💰
- [Administração Linux (Juliano Ramos, Casa do Código)](https://www.casadocodigo.com.br/products/livro-admin-linux) — Do primeiro comando aos servidores: shell script, SSH, RAID, Apache e proxy, em português. 💰
- [Certificação Linux: guia prático para a prova LPIC-1 101 (Casa do Código)](https://www.casadocodigo.com.br/products/livro-certificacao-linux) — Manual objetivo em português para a prova 101 da LPIC-1. 💰
- [Certificação Linux: guia prático para a prova LPIC-1 102 (Casa do Código)](https://www.casadocodigo.com.br/products/livro-certificacao-linux-2) — Continuação para a prova 102: shell, administração, serviços, rede e segurança. 💰
- [Shell Script Profissional (Aurelio Marinho Jargas)](https://www.shellscript.com.br/) — O livro brasileiro de referência em shell script, do autor do sed/regex em português. 💰
- [How Linux Works, 3rd Edition (Brian Ward, No Starch)](https://nostarch.com/howlinuxworks3) — Explica o que acontece por baixo: boot, kernel, dispositivos, systemd, rede e shell. 💰 🇺🇸
- [The Linux Programming Interface (Michael Kerrisk)](https://man7.org/tlpi/) — A bíblia da programação de sistemas em Linux: syscalls, processos, sinais, sockets. 💰 🇺🇸
- [UNIX and Linux System Administration Handbook, 5th Edition](https://www.admin.com/) — Referência clássica de administração de sistemas para quem vai cuidar de servidores. 💰 🇺🇸
- [Linux Fundamentals (Paul Cobbaut, linux-training.be)](https://linux-training.be/) — Apostilas gratuitas em PDF: fundamentos, administração, servidores, rede e segurança. 🇺🇸
- [linux-insides (0xAX)](https://github.com/0xAX/linux-insides) — Livro aberto sobre o interior do kernel: boot, interrupções, memória e syscalls. 🇺🇸
- [Linux Device Drivers, 3rd Edition (LWN)](https://lwn.net/Kernel/LDD3/) — O livro clássico de drivers, liberado gratuitamente pela O'Reilly/LWN. 🇺🇸
- [The Linux Commands Handbook (freeCodeCamp)](https://www.freecodecamp.org/news/the-linux-commands-handbook/) — Manual gratuito com os comandos mais usados, explicados um a um. 🇺🇸
- [Bite Size Linux! (Julia Evans)](https://wizardzines.com/zines/bite-size-linux/) — Zine ilustrada que explica processos, sinais, permissões e sistema de arquivos em desenhos. 💰 🇺🇸
- [Bite Size Command Line! (Julia Evans)](https://wizardzines.com/zines/bite-size-command-line/) — Zine ilustrada sobre `grep`, `find`, `xargs`, `awk` e outros comandos do dia a dia. 💰 🇺🇸

## 🎥 Canais no YouTube
### Em português
- [LINUXtips (Jeferson Fernando)](https://www.youtube.com/@LINUXtips) — O maior canal brasileiro de Linux, containers e DevOps, com lives e cursos gratuitos.
- [Diolinux](https://www.youtube.com/@Diolinux) — Notícias, reviews de distros, dicas de desktop e o podcast Diocast.
- [Bóson Treinamentos](https://www.youtube.com/@bosontreinamentos) — Cursos completos e gratuitos de Linux, redes, shell script e certificações.
- [Ricardo Prudenciato](https://www.youtube.com/@ricardoprudenciato) — Linux profissional: certificações LPI, carreira e administração de sistemas.
- [Prof. Juliano Ramos — Linux do Zero ao Hacker](https://www.youtube.com/@ProfJulianoRamos) — Cursos gratuitos de Linux, segurança e infraestrutura, com foco em empregabilidade.
- [Daniel Donda](https://www.youtube.com/@DanielDonda) — Infraestrutura, Linux, Windows e cibersegurança explicados para quem está entrando na área.
- [4Linux](https://www.youtube.com/@4linux) — Aulas abertas e webinars da escola brasileira de Linux e open source.
- [Certificação Linux (Uirá Ribeiro)](https://www.youtube.com/@CertificacaoLinux) — Dicas de prova, comandos e conceitos da LPIC em vídeos curtos.
- [Linux Descomplicado](https://www.youtube.com/@LinuxDescomplicado) — Tutoriais objetivos de terminal e administração para o dia a dia.
- [Gustavo Kalau](https://www.youtube.com/@gustavokalau) — Treinamentos gratuitos de Linux Essentials e infraestrutura.
- [Fabio Akita (Akitando)](https://www.youtube.com/@Akitando) — Vídeos longos sobre como o computador, o sistema operacional e o Linux realmente funcionam.
- [Linux Kamarada](https://www.youtube.com/@LinuxKamarada) — Canal do projeto Kamarada (openSUSE em português): dicas e tutoriais para desktop.

### Em inglês
- [Learn Linux TV](https://www.youtube.com/@LearnLinuxTV) — Cursos completos de Linux, servidores, Proxmox e Ansible, com didática impecável. 🇺🇸
- [The Linux Experiment](https://www.youtube.com/@TheLinuxEXP) — Notícias semanais do desktop Linux, reviews e explicações acessíveis. 🇺🇸
- [DistroTube](https://www.youtube.com/@DistroTube) — Distros, window managers, terminal e software livre, todos os dias. 🇺🇸
- [NetworkChuck](https://www.youtube.com/@NetworkChuck) — Linux, redes e segurança com energia de professor de cursinho — ótimo para iniciantes. 🇺🇸
- [Chris Titus Tech](https://www.youtube.com/@ChrisTitusTech) — Instalação, otimização e scripts para Linux desktop e servidores. 🇺🇸
- [Veronica Explains](https://www.youtube.com/@VeronicaExplains) — Explicações curtas e claras de comandos, hardware e história do Unix/Linux. 🇺🇸
- [Brodie Robertson](https://www.youtube.com/@BrodieRobertson) — Notícias diárias do kernel, Wayland, distros e comunidade. 🇺🇸
- [The Linux Foundation](https://www.youtube.com/@LinuxfoundationOrg) — Palestras do Open Source Summit, KubeCon e projetos da fundação. 🇺🇸
- [freeCodeCamp.org](https://www.youtube.com/@freecodecamp) — Cursos completos e gratuitos, incluindo Linux, Bash e DevOps. 🇺🇸
- [Linux in 100 Seconds (Fireship)](https://www.youtube.com/watch?v=rrB13utjYV4) — O que é Linux em 100 segundos — para mandar para quem pergunta. 🇺🇸
- [TechWorld with Nana](https://www.youtube.com/@TechWorldwithNana) — DevOps do zero: Linux, Docker, Kubernetes e CI/CD em cursos completos. 🇺🇸
- [KodeKloud](https://www.youtube.com/@KodeKloud) — Aulas de Linux, shell e certificações com laboratórios. 🇺🇸
- [Red Hat](https://www.youtube.com/@RedHat) — Canal oficial da Red Hat: RHEL, automação e histórias de open source. 🇺🇸
- [Linux Professional Institute](https://www.youtube.com/@LPIConnect) — Canal oficial da LPI: webinars sobre certificações e carreira. 🇺🇸

## 🎙️ Podcasts
- [Diocast (Diolinux)](https://diolinux.com.br/diocast) — O podcast brasileiro sobre Linux e tecnologia, semanal, com episódios em áudio e vídeo.
- [Diocast — "Linux vem forte em 2026. Mas o motivo está em 2025"](https://www.youtube.com/watch?v=-M-7loG48DU) — Episódio especial que revisa o ano em que o Linux virou assunto do público geral. 🆕
- [LINUXtips — Descomplicando Tecnologia](https://podcasts.apple.com/br/podcast/linuxtips-descomplicando-tecnologia/id1418626735) — Podcast do Jeferson Fernando sobre carreira, DevOps e histórias reais de quem trabalha com Linux.
- [Hipsters Ponto Tech — episódios sobre Linux](https://www.hipsters.tech/?s=linux) — Busca dos episódios do podcast da Alura que falam de Linux, open source e infraestrutura.
- [LINUX Unplugged](https://linuxunplugged.com/) — O podcast semanal mais tradicional sobre Linux, da Jupiter Broadcasting. 🇺🇸
- [Late Night Linux](https://latenightlinux.com/) — Notícias e discussões descontraídas sobre Linux e open source. 🇺🇸
- [Linux Action News](https://linuxactionnews.com/) — Resumo semanal de notícias do ecossistema Linux em 30 minutos. 🇺🇸
- [This Week in Linux (TuxDigital)](https://tuxdigital.com/podcasts/this-week-in-linux/) — Notícias da semana em vídeo e áudio. 🇺🇸
- [2.5 Admins](https://2.5admins.com/) — Sysadmins experientes discutindo servidores, ZFS, backups e notícias. 🇺🇸
- [Ask Noah Show](https://podcast.asknoahshow.com/) — Perguntas de ouvintes sobre Linux e open source respondidas ao vivo. 🇺🇸
- [Linux Downtime](https://linuxdowntime.com/) — Conversas com pessoas da comunidade sobre como usam Linux. 🇺🇸
- [Hacker Public Radio](https://hackerpublicradio.org/) — Podcast comunitário diário produzido pelos próprios ouvintes, com muito Linux. 🇺🇸

## 📰 Sites, blogs e newsletters
- [Diolinux](https://diolinux.com.br/) — Portal brasileiro de notícias, tutoriais e reviews de Linux e open source.
- [Viva o Linux](https://www.vivaolinux.com.br/) — A comunidade brasileira mais antiga de Linux: fórum, milhares de artigos, dicas e scripts enviados por usuários.
- [SempreUpdate](https://sempreupdate.com.br/) — Notícias diárias sobre Linux, distros e software livre em português.
- [Linux Descomplicado](https://www.linuxdescomplicado.com.br/) — Tutoriais e newsletter em português sobre terminal e administração.
- [Terminal Root](https://terminalroot.com.br/) — Blog brasileiro sobre terminal, shell, C/C++ e ferramentas de linha de comando.
- [Linux Kamarada](https://linuxkamarada.com/) — Blog em português voltado ao desktop Linux e ao openSUSE.
- [Dicas-L](https://www.dicas-l.com.br/) — Lista de dicas diárias sobre GNU/Linux e software livre que existe desde 1997.
- [Aurelio.net](https://aurelio.net/) — Site do Aurelio Jargas: shell, sed, expressões regulares e Vim em português.
- [freeCodeCamp em português — tag Linux](https://www.freecodecamp.org/portuguese/news/tag/linux/) — Artigos traduzidos sobre comandos, permissões e administração.
- [LWN.net](https://lwn.net/) — A publicação de referência sobre o desenvolvimento do kernel e do ecossistema; edição semanal por e-mail. 🇺🇸
- [It's FOSS (+ FOSS Weekly)](https://itsfoss.com/) — Tutoriais para iniciantes, notícias e a newsletter semanal FOSS Weekly. 🇺🇸
- [OMG! Ubuntu](https://www.omgubuntu.co.uk/) — Notícias do Ubuntu e do desktop Linux desde 2009. 🇺🇸
- [Linux Journal](https://www.linuxjournal.com/) — Revista histórica do Linux, com artigos técnicos e de opinião. 🇺🇸
- [Linux Handbook](https://linuxhandbook.com/) — Tutoriais de terminal, servidores e sysadmin, bem organizados por tema. 🇺🇸
- [TecMint](https://www.tecmint.com/) — Milhares de how-tos de administração Linux. 🇺🇸
- [Opensource.com — Linux](https://opensource.com/tags/linux) — Acervo da Red Hat com artigos práticos sobre Linux e cultura open source. 🇺🇸
- [Linux.com](https://www.linux.com/) — Notícias e tutoriais mantidos pela Linux Foundation. 🇺🇸
- [Julia Evans (jvns.ca)](https://jvns.ca/) — Blog que explica processos, sinais, rede e depuração de forma visual e divertida. 🇺🇸
- [Brendan Gregg — Linux Performance](https://www.brendangregg.com/linuxperf.html) — Mapa de ferramentas de performance do Linux pelo criador de vários dos comandos de observabilidade. 🇺🇸
- [DigitalOcean Community Tutorials](https://www.digitalocean.com/community/tutorials) — Tutoriais passo a passo de servidores Linux (Nginx, SSH, firewall, bancos) muito bem escritos. 🇺🇸
- [Red Hat Blog](https://www.redhat.com/en/blog) — Artigos técnicos da Red Hat sobre RHEL, automação e sysadmin. 🇺🇸
- [Ubuntu Blog](https://ubuntu.com/blog) — Novidades oficiais do Ubuntu, Canonical e ecossistema. 🇺🇸
- [Kernel Newbies](https://kernelnewbies.org/) — Resumo legível de cada versão do kernel e guias para novos contribuidores. 🇺🇸
- [console.dev](https://console.dev/) — Newsletter semanal gratuita de ferramentas para desenvolvedores, com muito CLI e Linux. 🇺🇸

## 🛠️ Ferramentas
### Terminal, shell e editores
- [tmux](https://github.com/tmux/tmux/wiki) — Multiplexador de terminal: várias janelas e sessões que sobrevivem à desconexão do SSH. 🇺🇸
- [Oh My Zsh](https://ohmyz.sh/) — Framework para o Zsh com temas, plugins e autocompletar turbinado. 🇺🇸
- [fish shell](https://fishshell.com/) — Shell amigável com sugestões e cores por padrão, sem configuração. 🇺🇸
- [Starship](https://starship.rs/) — Prompt rápido e bonito que funciona em qualquer shell. 🇺🇸
- [Ghostty](https://ghostty.org/) — Emulador de terminal moderno, rápido e nativo, lançado em 2024. 🆕 🇺🇸
- [Alacritty](https://alacritty.org/) — Terminal minimalista acelerado por GPU. 🇺🇸
- [kitty](https://sw.kovidgoyal.net/kitty/) — Terminal rápido com imagens, abas e scripting. 🇺🇸
- [WezTerm](https://wezterm.org/) — Terminal multiplataforma configurável em Lua. 🇺🇸
- [Vim](https://www.vim.org/) — O editor que está em todo servidor. Aprenda com `vimtutor` no seu terminal. 🇺🇸
- [Neovim](https://neovim.io/) — Vim moderno com Lua, LSP e um ecossistema enorme de plugins. 🇺🇸
- [GNU nano](https://www.nano-editor.org/) — Editor simples para editar um arquivo de configuração sem aprender Vim. 🇺🇸
- [Helix](https://helix-editor.com/) — Editor modal moderno com LSP e tree-sitter embutidos, sem plugins. 🇺🇸
- [micro](https://micro-editor.github.io/) — Editor de terminal com atalhos familiares (Ctrl+S, Ctrl+Z). 🇺🇸

### Utilitários modernos e produtividade
- [tldr pages](https://tldr.sh/) — Exemplos práticos de cada comando, mantidos pela comunidade — o `man` resumido. 🇺🇸
- [explainshell](https://explainshell.com/) — Cole um comando e veja o que cada flag faz, extraído das man pages. 🇺🇸
- [cheat.sh](https://cheat.sh/) — Folhas de cola de comandos direto no terminal: `curl cheat.sh/tar`. 🇺🇸
- [ShellCheck](https://www.shellcheck.net/) — Analisador estático que aponta bugs em scripts shell antes de rodar. 🇺🇸
- [shfmt (mvdan/sh)](https://github.com/mvdan/sh) — Formatador de scripts shell, para padronizar o código do time. 🇺🇸
- [bat](https://github.com/sharkdp/bat) — `cat` com realce de sintaxe e integração com Git. 🇺🇸
- [eza](https://github.com/eza-community/eza) — `ls` moderno com cores, ícones e árvore. 🇺🇸
- [fd](https://github.com/sharkdp/fd) — Alternativa simples e rápida ao `find`. 🇺🇸
- [ripgrep](https://github.com/BurntSushi/ripgrep) — `grep` recursivo extremamente rápido que respeita o `.gitignore`. 🇺🇸
- [fzf](https://github.com/junegunn/fzf) — Busca difusa para histórico, arquivos e qualquer lista no terminal. 🇺🇸
- [zoxide](https://github.com/ajeetdsouza/zoxide) — `cd` inteligente que aprende os diretórios que você mais usa. 🇺🇸
- [btop](https://github.com/aristocratos/btop) — Monitor de recursos bonito e completo no terminal. 🇺🇸
- [htop](https://htop.dev/) — Visualizador interativo de processos, presente em quase toda distro. 🇺🇸
- [jq](https://github.com/jqlang/jq) — Processador de JSON na linha de comando — indispensável para APIs e logs. 🇺🇸
- [lazygit](https://github.com/jesseduffield/lazygit) — Interface de terminal para Git. 🇺🇸
- [modern-unix](https://github.com/ibraheemdev/modern-unix) — Lista de alternativas modernas aos comandos Unix clássicos. 🇺🇸
- [Glances](https://nicolargo.github.io/glances/) — Monitoramento de sistema em uma tela, local ou via web. 🇺🇸
- [Netdata](https://www.netdata.cloud/) — Monitoramento em tempo real com dashboards prontos, instalação em um comando. 🇺🇸
- [Timeshift](https://github.com/linuxmint/timeshift) — Snapshots do sistema para voltar no tempo depois de uma atualização que deu errado. 🇺🇸
- [Cockpit](https://cockpit-project.org/) — Painel web oficial para administrar servidores Linux (Red Hat/Fedora/Ubuntu). 🇺🇸

### Virtualização, containers e laboratório
- [Instalar o WSL (Microsoft Learn, PT-BR)](https://learn.microsoft.com/pt-br/windows/wsl/install) — Rode Linux dentro do Windows com um comando — a forma mais fácil de começar sem formatar nada.
- [VS Code — Developing in WSL](https://code.visualstudio.com/docs/remote/wsl) — Edite no Windows e execute no Linux do WSL, com terminal integrado. 🇺🇸
- [VirtualBox](https://www.virtualbox.org/) — Máquinas virtuais gratuitas para testar distros sem risco. 🇺🇸
- [QEMU](https://www.qemu.org/) — Emulador e virtualizador open source — a base do KVM no Linux. 🇺🇸
- [GNOME Boxes](https://apps.gnome.org/Boxes/) — VMs em três cliques no desktop Linux. 🇺🇸
- [Multipass](https://canonical.com/multipass) — VMs Ubuntu instantâneas pela linha de comando, em qualquer sistema. 🇺🇸
- [Vagrant](https://developer.hashicorp.com/vagrant) — Ambientes de laboratório reproduzíveis descritos em um arquivo. 🇺🇸
- [Distrobox](https://distrobox.it/) — Use qualquer distro dentro de um container, integrada ao seu desktop. 🇺🇸
- [Docker](https://www.docker.com/) — Containers Linux: o próximo passo natural depois de dominar o terminal. 🇺🇸
- [Install Docker Engine on Ubuntu](https://docs.docker.com/engine/install/ubuntu/) — Guia oficial de instalação do Docker no Ubuntu. 🇺🇸
- [Killercoda](https://killercoda.com/) — Cenários interativos gratuitos de Linux, Kubernetes e DevOps no navegador. 🇺🇸
- [Proxmox VE](https://www.proxmox.com/en/products/proxmox-virtual-environment/overview) — Hipervisor open source baseado em Debian, o favorito para homelabs. 🇺🇸

### Pacotes, instalação e mídia bootável
- [Flatpak](https://flatpak.org/) — Formato universal de aplicativos para desktop Linux, isolado em sandbox. 🇺🇸
- [Flathub](https://flathub.org/) — A loja de aplicativos Flatpak com milhares de apps. 🇺🇸
- [Snapcraft](https://snapcraft.io/) — Loja de pacotes snap da Canonical. 🇺🇸
- [AppImage](https://appimage.org/) — Aplicativos em um único arquivo executável, sem instalação. 🇺🇸
- [Homebrew](https://brew.sh/) — Gerenciador de pacotes de usuário que também funciona no Linux. 🇺🇸
- [Ventoy](https://www.ventoy.net/) — Pendrive bootável com várias ISOs ao mesmo tempo — basta copiar os arquivos. 🇺🇸
- [balenaEtcher](https://etcher.balena.io/) — Grave ISOs em pendrive com segurança, em qualquer sistema. 🇺🇸
- [Rufus](https://rufus.ie/) — Criador de pendrive bootável para quem ainda está no Windows. 🇺🇸

### Rede, segurança e backup
- [OpenSSH](https://www.openssh.org/) — O acesso remoto seguro que todo servidor usa; aprenda chaves, `ssh-agent` e `scp`. 🇺🇸
- [nftables / netfilter](https://www.nftables.org/) — O firewall do kernel Linux e o sucessor do iptables. 🇺🇸
- [firewalld](https://firewalld.org/) — Gerenciador de firewall dinâmico usado no Fedora, RHEL e derivados. 🇺🇸
- [fail2ban](https://github.com/fail2ban/fail2ban) — Bloqueia IPs que tentam força bruta no SSH e em outros serviços. 🇺🇸
- [WireGuard](https://www.wireguard.com/) — VPN moderna e simples, integrada ao kernel Linux. 🇺🇸
- [AppArmor](https://apparmor.net/) — Controle de acesso obrigatório usado no Ubuntu, Debian e SUSE. 🇺🇸
- [SELinux Project](https://github.com/SELinuxProject) — Controle de acesso obrigatório do mundo Red Hat/Fedora. 🇺🇸
- [BorgBackup](https://www.borgbackup.org/) — Backups deduplicados, comprimidos e criptografados. 🇺🇸
- [restic](https://restic.net/) — Backup simples e seguro para disco local, SFTP e nuvem. 🇺🇸
- [Ansible Documentation](https://docs.ansible.com/) — Automatize a configuração de dezenas de servidores Linux via SSH. 🇺🇸

### Kernel, depuração e performance
- [torvalds/linux (GitHub)](https://github.com/torvalds/linux) — Espelho do código-fonte do kernel — navegue e leia como o Linux é feito. 🇺🇸
- [strace](https://strace.io/) — Veja cada chamada de sistema que um programa faz — a ferramenta nº 1 de depuração no Linux. 🇺🇸
- [Valgrind](https://valgrind.org/) — Detecta vazamentos e erros de memória em programas nativos. 🇺🇸
- [perf (wiki)](https://perfwiki.github.io/) — Profiler oficial do kernel Linux. 🇺🇸
- [eBPF.io](https://ebpf.io/) — Introdução e tutoriais sobre eBPF, a tecnologia que revolucionou observabilidade e rede no kernel. 🇺🇸
- [bpftrace](https://github.com/bpftrace/bpftrace) — Linguagem de tracing de alto nível sobre eBPF, para one-liners de diagnóstico. 🇺🇸

## 🧪 Projetos práticos e desafios
- [Linux Upskill Challenge](https://linuxupskillchallenge.org/) — Curso-desafio gratuito de 21 dias: você administra um servidor de verdade, uma tarefa por dia. 🇺🇸
- [OverTheWire: Bandit](https://overthewire.org/wargames/bandit/) — Jogo de segurança por níveis via SSH que ensina o terminal na marra — comece pelo nível 0. 🇺🇸
- [SadServers](https://sadservers.com/) — "Servidores tristes" para consertar: cenários reais de troubleshooting Linux/DevOps no navegador. 🇺🇸
- [cmdchallenge](https://cmdchallenge.com/) — Desafios de uma linha de comando cada, com correção automática. 🇺🇸
- [Bashcrawl](https://gitlab.com/slackermedia/bashcrawl) — Um jogo de masmorra jogado inteiramente com `cd`, `ls` e `cat`. 🇺🇸
- [The Command Line Murder Mystery](https://github.com/veltman/clmystery) — Resolva um assassinato usando `grep`, `sort` e `head` em arquivos de texto. 🇺🇸
- [VIM Adventures](https://vim-adventures.com/) — Jogo que ensina as teclas do Vim; os primeiros níveis são gratuitos. 💰 🇺🇸
- [Linux From Scratch](https://www.linuxfromscratch.org/lfs/read.html) — Construa seu próprio Linux a partir do código-fonte — o projeto definitivo para entender o sistema. 🇺🇸
- [Beyond Linux From Scratch](https://www.linuxfromscratch.org/blfs/) — Continuação do LFS: adicione rede, X, desktop e serviços ao sistema que você construiu. 🇺🇸
- [devops-exercises](https://github.com/bregman-arie/devops-exercises) — Milhares de perguntas e exercícios de Linux, rede, Docker e nuvem para praticar e treinar para entrevistas. 🇺🇸
- [build-your-own-x](https://github.com/codecrafters-io/build-your-own-x) — Tutoriais para construir seu próprio shell, sistema operacional e container do zero. 🇺🇸
- [Linux Kernel Labs](https://linux-kernel-labs.github.io/) — Laboratórios universitários de programação de kernel, com VM pronta. 🇺🇸
- [Submitting patches (kernel docs)](https://docs.kernel.org/process/submitting-patches.html) — O guia oficial para enviar seu primeiro patch ao kernel Linux. 🇺🇸
- [awesome-selfhosted](https://github.com/awesome-selfhosted/awesome-selfhosted) — Lista de serviços para hospedar em casa — o melhor jeito de praticar administração de servidores. 🇺🇸

## 🐧 Distros e ambientes de desktop
Não existe "a melhor distro": existe a melhor para o seu momento. Para começar, **Ubuntu, Linux Mint ou Fedora**; para o mercado corporativo, aprenda a família **Red Hat** (Rocky/AlmaLinux são gratuitas e compatíveis); para entender o sistema a fundo, **Arch** ou **Debian**. O terminal é o mesmo em todas.
- [Ubuntu](https://ubuntu.com/) — A distro mais popular e com mais tutoriais na internet; versões LTS a cada 2 anos. 🇺🇸
- [Ubuntu Server](https://ubuntu.com/download/server) — A mesma base do Ubuntu, sem interface gráfica, para servidores e nuvem. 🇺🇸
- [Linux Mint (User Guide)](https://linuxmint-user-guide.readthedocs.io/en/latest/) — Baseada no Ubuntu, com área de trabalho familiar para quem vem do Windows. 🇺🇸
- [Debian](https://www.debian.org/) — O "sistema operacional universal", base do Ubuntu e de dezenas de distros; Debian 13 "trixie" saiu em 2025. 🆕 🇺🇸
- [Fedora](https://fedoraproject.org/) — Tecnologia de ponta patrocinada pela Red Hat, sem ser instável. 🇺🇸
- [Pop!_OS](https://system76.com/pop) — Distro da System76 focada em desenvolvedores e criadores. 🇺🇸
- [Zorin OS](https://zorin.com/os/) — Visual parecido com Windows/macOS, feita para a transição. 🇺🇸
- [elementary OS](https://elementary.io/) — Desktop elegante e consistente, inspirado no macOS. 🇺🇸
- [Arch Linux](https://archlinux.org/) — Rolling release minimalista: você monta o sistema do jeito que quer e aprende muito no processo. 🇺🇸
- [EndeavourOS](https://endeavouros.com/) — Arch com instalador gráfico e comunidade acolhedora. 🇺🇸
- [Manjaro](https://manjaro.org/) — Arch mais fácil, com pacotes testados antes de chegar a você. 🇺🇸
- [CachyOS](https://cachyos.org/) — Distro baseada em Arch com kernel e pacotes otimizados para desempenho; entre as mais buscadas de 2025. 🆕 🇺🇸
- [openSUSE](https://www.opensuse.org/) — Leap (estável) e Tumbleweed (rolling), com o YaST e snapshots Btrfs por padrão. 🇺🇸
- [Rocky Linux](https://rockylinux.org/) — Compatível com RHEL e gratuita — ideal para estudar para RHCSA. 🇺🇸
- [AlmaLinux](https://almalinux.org/) — Outra distro comunitária compatível com RHEL, mantida pela AlmaLinux OS Foundation. 🇺🇸
- [Kali Linux](https://www.kali.org/) — Distro de segurança ofensiva com centenas de ferramentas prontas. 🇺🇸
- [Alpine Linux](https://alpinelinux.org/) — Minúscula e segura — a base de grande parte das imagens Docker. 🇺🇸
- [NixOS](https://nixos.org/) — Sistema declarativo e reproduzível: toda a configuração em um arquivo. 🇺🇸
- [Bazzite](https://bazzite.gg/) — Distro imutável baseada em Fedora para jogos e Steam Deck, uma das novidades de 2024. 🆕 🇺🇸
- [DistroWatch](https://distrowatch.com/) — Ranking, notícias e comparativos de todas as distros. 🇺🇸
- [DistroSea](https://distrosea.com/) — Teste dezenas de distros direto no navegador, sem baixar nada. 🇺🇸
- [Distrochooser](https://distrochooser.de/) — Questionário que sugere a distro ideal para o seu perfil. 🇺🇸
- [GNOME](https://www.gnome.org/) — O ambiente de desktop padrão do Ubuntu, Fedora e Debian. 🇺🇸
- [KDE Plasma](https://kde.org/) — Desktop completo e altamente configurável; usado no Steam Deck. 🇺🇸
- [Hyprland](https://hypr.land/) — Compositor Wayland dinâmico que virou febre entre quem personaliza o desktop. 🆕 🇺🇸

## 🤖 IA na prática
Assistentes de IA são ótimos para aprender Linux — e perigosos quando executam comandos no seu lugar. O terminal não tem "desfazer": um `rm -rf` no diretório errado, um `chmod -R 777 /` ou um `dd` no disco errado apagam dados na hora. Use IA para **entender**, e mantenha o dedo no gatilho para **executar**.

**Para aprender**
- Cole a saída de um erro (ex.: `Permission denied`, `command not found`, `No space left on device`) e peça: *"explique a causa provável e três formas de diagnosticar antes de corrigir"*.
- Peça para explicar um comando **flag por flag** (`tar -xzvf`, `find . -type f -mtime -7 -exec …`) e confira no [explainshell](https://explainshell.com/) ou na man page.
- Peça **exercícios com gabarito** sobre o tópico que está estudando (permissões, pipes, systemd, rede) e resolva numa VM descartável.
- Peça um roteiro de estudo para uma certificação (LPIC-1, LFCS) cruzando com os objetivos oficiais da prova — a IA erra objetivos; a página oficial não.
- Use um modelo **local** com o [Ollama](https://ollama.com/) para praticar sem enviar nada para a nuvem — e, de quebra, aprender a administrar GPU, serviços e portas no Linux.

**Para trabalhar**
- Ferramentas como [GitHub Copilot CLI](https://github.com/github/copilot-cli), [Claude Code](https://code.claude.com/docs/en/overview), [Gemini CLI](https://github.com/google-gemini/gemini-cli), [ShellGPT](https://github.com/TheR1D/shell_gpt) e o terminal [Warp](https://www.warp.dev/) transformam "encontre os 10 maiores arquivos de log dos últimos 3 dias" em um comando pronto. Bom uso: gerar one-liners de `find`/`awk`/`jq`, rascunhar scripts, unidades do systemd, regras de firewall e playbooks do Ansible, e explicar logs longos do `journalctl`.
- **Leia antes de executar.** Rode primeiro com `--dry-run`, `-n` (rsync), `echo` na frente ou em uma VM. Prefira ferramentas que pedem confirmação antes de executar (todas as acima têm esse modo — não o desligue).
- Passe scripts gerados pelo [ShellCheck](https://www.shellcheck.net/) e teste com `bash -n script.sh`. Se o script usa `rm -rf "$VAR/"` sem `set -u` e sem checar se `$VAR` está vazio, ele está errado.
- Nunca rode como root o que a IA sugeriu sem entender; nunca cole `curl … | sudo bash` de fonte que você não conhece.

**Limites e boas práticas**
- IA **inventa flags e nomes de pacotes**, mistura sintaxe de distros (`apt` × `dnf` × `pacman`) e sugere soluções antigas (`ifconfig`, `service`, `iptables`) onde hoje se usa `ip`, `systemctl` e `nftables`. Confirme na [man page](https://man7.org/linux/man-pages/) ou na [ArchWiki](https://wiki.archlinux.org/).
- Ela não vê o seu sistema: informe distro, versão e saída dos comandos de diagnóstico (`uname -a`, `lsb_release -a`, `df -h`, `systemctl status`) para não receber chutes.
- Não cole chaves SSH, senhas, `/etc/shadow`, tokens de nuvem ou dados de clientes em ferramentas sem a política da sua empresa. Em servidores de produção, siga o processo de mudança do time.
- Entenda o que você aceita: em entrevista e em incidente de produção, o comando é seu.

**Ferramentas de IA para o terminal e para rodar modelos no Linux:**
- [GitHub Copilot CLI](https://github.com/github/copilot-cli) — Agente do Copilot no terminal: explica e sugere comandos e executa tarefas com sua aprovação. 🆕 🇺🇸
- [Claude Code](https://code.claude.com/docs/en/overview) — Agente de codificação da Anthropic para o terminal; roda comandos, edita arquivos e pede permissão antes de agir. 🆕 🇺🇸
- [Gemini CLI](https://github.com/google-gemini/gemini-cli) — Agente open source do Google para o terminal, com camada gratuita generosa. 🆕 🇺🇸
- [OpenAI Codex CLI](https://github.com/openai/codex) — Agente de codificação leve da OpenAI que roda localmente no terminal. 🆕 🇺🇸
- [Amazon Q Developer CLI](https://aws.amazon.com/q/developer/) — Autocompletar e chat de IA no terminal, com foco em AWS e shell. 🆕 🇺🇸
- [Warp](https://www.warp.dev/) — Terminal com IA embutida (disponível para Linux desde 2024): escreva em linguagem natural e receba o comando. 🆕 🇺🇸
- [ShellGPT](https://github.com/TheR1D/shell_gpt) — Gere e execute comandos shell a partir de uma descrição, usando o modelo que você escolher. 🇺🇸
- [aichat](https://github.com/sigoden/aichat) — CLI de LLM tudo-em-um com "shell assistant" e suporte a dezenas de provedores, inclusive locais. 🆕 🇺🇸
- [Ollama](https://ollama.com/) — Rode modelos de linguagem localmente no Linux com um comando (`ollama run llama3`). 🆕 🇺🇸
- [llama.cpp](https://github.com/ggml-org/llama.cpp) — Inferência de LLMs em C/C++ — a base do Ollama e a forma mais leve de rodar modelos em qualquer máquina Linux. 🇺🇸
- [Open WebUI](https://github.com/open-webui/open-webui) — Interface web auto-hospedada para conversar com modelos locais (Ollama) — um ótimo projeto de servidor. 🆕 🇺🇸

## 📜 Certificações
Linux é uma das poucas áreas em que certificação pesa de verdade no Brasil: **LPIC-1** e **RHCSA** aparecem em vagas de infraestrutura e suporte, e **LFCS** cresce junto com DevOps. Todas as provas abaixo são práticas ou fortemente baseadas em comandos — estude em um terminal, não em slides. A LPI publica [apostilas oficiais gratuitas em português](https://learning.lpi.org/pt/) para Linux Essentials e LPIC-1.
- [LPI Linux Essentials](https://www.lpi.org/pt-br/our-certifications/linux-essentials-overview/) — Certificação de entrada da LPI, sem pré-requisitos; a prova pode ser feita em português.
- [LPIC-1: Linux Administrator](https://www.lpi.org/pt-br/our-certifications/lpic-1-overview/) — A certificação Linux mais reconhecida no Brasil (provas 101 e 102), neutra em relação à distro.
- [LPIC-2: Linux Engineer](https://www.lpi.org/pt-br/our-certifications/lpic-2-overview/) — Nível avançado: kernel, armazenamento, rede, serviços e segurança.
- [LPIC-3: Mixed Environments](https://www.lpi.org/pt-br/our-certifications/lpic-3-300-overview/) — Topo da trilha LPI, com especializações (ambientes mistos, segurança, virtualização, alta disponibilidade).
- [LFCS — Linux Foundation Certified System Administrator](https://training.linuxfoundation.org/certification/linux-foundation-certified-sysadmin-lfcs/) — Prova 100% prática em terminal da Linux Foundation, muito valorizada em DevOps. 🇺🇸
- [LFCA — Linux Foundation Certified IT Associate](https://training.linuxfoundation.org/certification/certified-it-associate/) — Certificação de entrada da Linux Foundation: fundamentos de Linux, nuvem e DevOps. 🇺🇸
- [CompTIA Linux+ (V8)](https://www.comptia.org/en-us/certifications/linux/) — Certificação neutra da CompTIA, renovada em 2025 com foco em automação, containers e segurança. 🆕 🇺🇸
- [RHCSA — Red Hat Certified System Administrator](https://www.redhat.com/pt-br/services/certification/rhcsa) — Prova prática da Red Hat, referência no mercado corporativo brasileiro.
- [Certificações Red Hat (catálogo, incl. RHCE)](https://www.redhat.com/pt-br/services/certifications) — Página oficial em português com toda a trilha Red Hat: RHCSA, RHCE, OpenShift e Ansible.
- [Guia de Certificações (Guia Dev Brasil)](https://github.com/arthurspk/guiadecertificacoes) — Guia irmão com o panorama de certificações de TI, incluindo Linux e nuvem.

## 💼 Carreira e vagas
Linux é requisito em vagas de infraestrutura, suporte técnico, DevOps/SRE, segurança, dados e back-end. Cargos comuns no Brasil: analista de suporte, administrador de sistemas (sysadmin), engenheiro de infraestrutura/cloud, DevOps/SRE e analista de segurança. Dica: nos repositórios de vagas do GitHub abaixo, pesquise por "Linux", "sysadmin" ou "DevOps" nas issues abertas.
- [2025 Stack Overflow Developer Survey](https://survey.stackoverflow.co/2025/) — Linux segue como o sistema mais usado por desenvolvedores profissionais no mundo. 🆕 🇺🇸
- [2024 State of Tech Talent Report (Linux Foundation)](https://www.linuxfoundation.org/research/open-source-jobs-report-2024) — Relatório da Linux Foundation sobre demanda por habilidades em Linux, nuvem e open source. 🆕 🇺🇸
- [Programathor — vagas Linux](https://programathor.com.br/jobs-linux) — Vagas de tecnologia no Brasil que pedem Linux.
- [Programathor — vagas DevOps](https://programathor.com.br/jobs-devops) — Vagas de DevOps/SRE, onde Linux é requisito básico.
- [GeekHunter](https://www.geekhunter.com/pt) — Plataforma brasileira onde empresas fazem propostas a profissionais de tecnologia.
- [Coodesh](https://coodesh.com/) — Vagas tech no Brasil com processos seletivos padronizados.
- [Remotar](https://remotar.com.br/) — Vagas 100% remotas para brasileiros.
- [backend-br/vagas](https://github.com/backend-br/vagas) — Vagas de back-end e infraestrutura publicadas como issues no GitHub — pesquise por "Linux".
- [CangaceirosDevels/vagas_de_emprego](https://github.com/CangaceirosDevels/vagas_de_emprego) — Vagas de tecnologia no GitHub, com muitas de infraestrutura e suporte.
- [RemoteOK — vagas Linux](https://remoteok.com/remote-linux-jobs) — Vagas remotas internacionais com Linux. 🇺🇸
- [Tech Interview Handbook](https://www.techinterviewhandbook.org/) — Preparação completa para entrevistas técnicas. 🇺🇸
- [Guia de Shell Script (Guia Dev Brasil)](https://github.com/arthurspk/guiadeshellscript) — Próximo passo natural: automatize tudo o que aprendeu no terminal.
- [Guia de Redes (Guia Dev Brasil)](https://github.com/arthurspk/guiaderedes) — Redes de computadores — a outra metade do trabalho de quem administra Linux.
- [Guia de Docker (Guia Dev Brasil)](https://github.com/arthurspk/guiadedocker) — Containers são Linux: siga para o Docker quando o terminal já for confortável.
- [Guia de Cyber Security (Guia Dev Brasil)](https://github.com/arthurspk/guiadecybersecurity) — Para quem quer seguir para segurança — Kali, hardening e CTFs.

## 👥 Comunidades
- [Diolinux Plus](https://plus.diolinux.com.br/) — Fórum brasileiro do Diolinux: dúvidas de instalação, hardware e desktop respondidas rápido.
- [Debian Brasil](https://debianbrasil.org.br/) — Comunidade brasileira do Debian: eventos, tradução e canais de ajuda.
- [r/linuxbrasil](https://www.reddit.com/r/linuxbrasil/) — Subreddit em português sobre Linux.
- [Lista de grupos de tecnologia no Telegram (TI-Brasil)](https://github.com/TI-Brasil/lista-telegram-brasil) — Diretório de grupos brasileiros no Telegram, incluindo Linux, distros e sysadmin.
- [Latinoware](https://latinoware.org/) — Maior congresso de software livre da América Latina, em Foz do Iguaçu.
- [TabNews](https://www.tabnews.com.br/) — Comunidade brasileira de conteúdo técnico criada por Filipe Deschamps.
- [He4rt Developers](https://heartdevs.com/) — Comunidade brasileira open source com Discord ativo.
- [Desenvolvedores Brasil (Discord)](https://discord.com/invite/t3vYGUuK6P) — Comunidade brasileira com canais de infraestrutura, Linux e vagas.
- [Arch Linux Forums](https://bbs.archlinux.org/) — Fórum oficial do Arch — respostas técnicas de altíssimo nível. 🇺🇸
- [Fedora Discussion](https://discussion.fedoraproject.org/) — Fórum oficial do Fedora. 🇺🇸
- [Ubuntu Community Hub](https://discourse.ubuntu.com/) — Discourse oficial da comunidade Ubuntu. 🇺🇸
- [Linux Mint Community](https://community.linuxmint.com/) — Site comunitário do Mint: tutoriais, hardware compatível e ideias. 🇺🇸
- [r/linux](https://www.reddit.com/r/linux/) — O maior subreddit de Linux. 🇺🇸
- [r/linux4noobs](https://www.reddit.com/r/linux4noobs/) — Subreddit para iniciantes — nenhuma pergunta é boba. 🇺🇸
- [Fosstodon](https://fosstodon.org/) — Instância Mastodon da comunidade de software livre. 🇺🇸
- [lore.kernel.org](https://lore.kernel.org/) — Arquivo público das listas de e-mail do kernel — onde o Linux é discutido de verdade. 🇺🇸

## 🚨 Como contribuir
Achou um link quebrado, um curso novo ou uma ferramenta que merece estar aqui? Abra uma issue usando os templates do repositório ou envie um pull request. Critérios: link funcionando, conteúdo legal e gratuito ou claramente marcado como pago, com uma linha de descrição. Detalhes em [CONTRIBUTING.md](./CONTRIBUTING.md).

## 📄 Licença
Este projeto está sob a licença [MIT](./LICENSE). Feito com 💙 por [Arthur Coutinho (@arthurspk)](https://github.com/arthurspk) e pela comunidade do [Guia Dev Brasil](https://github.com/arthurspk/guiadevbrasil).

## 💙 Apoie o projeto
Dê uma ⭐ neste repositório e no [guia principal](https://github.com/arthurspk/guiadevbrasil), compartilhe com quem está começando e siga o projeto nas redes:

[<img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">](https://github.com/arthurspk)
[<img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">](https://www.linkedin.com/in/arthurspk/)
[<img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white" alt="X (Twitter)">](https://x.com/manotoquinho)
[<img src="https://img.shields.io/badge/instagram-%23E4405F.svg?&style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram">](https://www.instagram.com/arthurspk/)
[<img src="https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white" alt="Facebook">](https://www.facebook.com/seixasqlc/)
