<!-- Red-phisher -->

<p align="center">
  <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT6IP1Z6Q-3DXwJ-YtRZwW4dlqR-NfCXunZ-WeyNFnwxlbhQD0Z8vmgBOQ&s=10" alt="Red-phisher">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Tool-Red--phisher-red?style=for-the-badge&logo=gnubash">
  <img src="https://img.shields.io/badge/Version-2.3.5-green?style=for-the-badge">
  <img src="https://img.shields.io/badge/License-GPL%20v3-blue?style=for-the-badge">
  <img src="https://img.shields.io/badge/Platform-Termux%20%7C%20Linux-darkcyan?style=for-the-badge">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Author-rakib224-blue?style=flat-square">
  <img src="https://img.shields.io/badge/Open%20Source-Yes-darkgreen?style=flat-square">
  <img src="https://img.shields.io/badge/Written%20In-Bash-darkcyan?style=flat-square">
</p>

<p align="center"><b>A beginners friendly, Automated phishing tool with 30+ templates.</b></p>

##

<h3><p align="center">Disclaimer</p></h3>

<i>Any actions and or activities related to <b>Red-phisher</b> is solely your responsibility. The misuse of this toolkit can result in <b>criminal charges</b> brought against the persons in question. <b>The contributors will not be held responsible</b> in the event any criminal charges be brought against any individuals misusing this toolkit to break the law.

<b>This toolkit contains materials that can be potentially damaging or dangerous for social media</b>. Refer to the laws in your province/country before accessing, using, or in any other way utilizing this in a wrong way.

<b>This Tool is made for educational purposes only</b>. Do not attempt to violate the law with anything contained here. <b>If this is your intention, then Get the hell out of here</b>!

It only demonstrates "how phishing works". <b>You shall not misuse the information to gain unauthorized access to someones social media</b>. However you may try out this at your own risk.</i>

##

### Features

- Latest and updated login pages.
- Beginners friendly
- Multiple tunneling options
  - Localhost
  - Cloudflared (auto install with 3-tier fallback)
  - LocalXpose
- Mask URL support
- Auto install missing packages (pkg / pip)
- Live download progress
- Auto clean terminal (deep clear)
- Docker support

##

### Installation

> **📋 Copy the commands below and paste them into your terminal (Termux / Linux).**

#### 🟢 One-line Installation (Recommended)

```bash
git clone --depth=1 https://github.com/rakib224/Red-phisher.git && cd Red-phisher && bash zphisher.sh
```

#### 🟢 Step by Step Installation

<h3>Step 1 — Clone Repository</h3>

```bash
git clone --depth=1 https://github.com/rakib224/Red-phisher.git
```

<h3>Step 2 — Open Folder</h3>

```bash
cd Red-phisher
```

<h3>Step 3 — Run Red-phisher</h3>

```bash
bash zphisher.sh
```

- On first launch, It'll install all dependencies automatically. ***Red-phisher*** is ready to use.

##

### Installation (Termux)

```bash
# Update Termux packages
pkg update && pkg upgrade -y

# Install git (if not installed)
pkg install git -y

# Clone the repository
git clone --depth=1 https://github.com/rakib224/Red-phisher.git

# Enter the directory
cd Red-phisher

# Run Red-phisher
bash zphisher.sh
```

### A Note :
***Termux discourages hacking*** .. So never discuss anything related to *Red-phisher* in any of the termux discussion groups. For more check : [wiki](https://wiki.termux.com/wiki/Hacking)

##

### Installation via ".deb" file

- Download `.deb` files from the [**Latest Release**](https://github.com/rakib224/Red-phisher/releases/latest)
- If you are using ***termux*** then download the `*_termux.deb`

- Install the `.deb` file by executing

```bash
apt install <your path to deb file>
```

Or

```bash
dpkg -i <your path to deb file>
apt install -f
```

##

### Run on Docker

- Docker Image Mirror:
  - **DockerHub** :
    ```bash
    docker pull rakib224/red-phisher
    ```
  - **GHCR** :
    ```bash
    docker pull ghcr.io/rakib224/Red-phisher:latest
    ```

- By using the wrapper script [**run-docker.sh**](https://raw.githubusercontent.com/rakib224/Red-phisher/master/run-docker.sh)

  ```bash
  curl -LO https://raw.githubusercontent.com/rakib224/Red-phisher/master/run-docker.sh
  bash run-docker.sh
  ```

- Temporary Container

  ```bash
  docker run --rm -ti rakib224/red-phisher
  ```
  - Remember to mount the `auth` directory.

##

### 🚀 Future Updates & Roadmap

**Red-phisher** is an actively maintained project and will continue to receive upgrades in the future. Here's what's planned ahead:

- 🆕 New and updated phishing templates
- 🌐 Additional tunneling services & better Cloudflared integration
- ⚡ Faster auto-install for missing packages (pkg / pip)
- 🐛 Regular bug fixes and security patches
- 🎨 UI / UX improvements in the terminal menu
- 🐳 Improved Docker & .deb packaging

To stay up-to-date with the latest version, simply run this inside the project folder:

```bash
git pull
```

Or click the ⭐ **Star** and 👀 **Watch** button on this repository to get notified whenever a new release is published.

Have a feature request or found a bug? Open an [issue](https://github.com/rakib224/Red-phisher/issues) or send a [pull request](https://github.com/rakib224/Red-phisher/pulls) — contributions are always welcome.

##

<details>
  <summary><h3>Dependencies</h3></summary>

<b>Red-phisher</b> requires following programs to run properly -
- `git`
- `curl`
- `php`
- `unzip`

> All the dependencies will be installed automatically when you run **Red-phisher** for the first time.
</details>

<details>
  <summary><h3>Tested on</h3></summary>

- **Ubuntu**
- **Debian**
- **Arch**
- **Manjaro**
- **Fedora**
- **Termux**
</details>

##

<h3 align="center"><i>:: Workflow ::</i></h3>
<p align="center">
<img src=".github/misc/workflow.gif"/>
</p>

##

### Find Me on:

<p align="left">
  <a href="https://github.com/rakib224" target="_blank"><img src="https://img.shields.io/badge/Github-rakib224-blue?style=for-the-badge&logo=github"></a>
</p>

### *Thanks to all contributors*:

<table>
  <tr align="center">
    <td><a href="https://github.com/1RaY-1"><img src="https://avatars.githubusercontent.com/u/78962948?s=100" /><br /><sub><b>1RaY-1</b></sub></a></td>
    <td><a href="https://github.com/adi1090x"><img src="https://avatars.githubusercontent.com/u/26059688?s=100" /><br /><sub><b>Aditya Shakya</b></sub></a></td>
    <td><a href="https://github.com/AliMilani"><img src="https://avatars.githubusercontent.com/u/59066012?s=100" /><br /><sub><b>Ali Milani</b></sub></a></td>
    <td><a href="https://github.com/KasRoudra"><img src="https://avatars.githubusercontent.com/u/78908440?s=100" /><br /><sub><b>KasRoudra</b></sub></a></td>
    <td><a href="https://github.com/MoisesTapia"><img src="https://avatars.githubusercontent.com/u/28166400?s=100" /><br /><sub><b>Moises Tapia</b></sub></a></td>
    <td><a href="https://github.com/E343IO"><img src="https://avatars.githubusercontent.com/u/74646789?s=100" /><br /><sub><b>Mr.Derek</b></sub></a></td>
    <td><a href="https://github.com/BDhackers009"><img src="https://avatars.githubusercontent.com/u/67186139?s=100" /><br /><sub><b>Mustakim Ahmed</b></sub></a></td>
    <td><a href="https://github.com/Yisus7u7"><img src="https://avatars.githubusercontent.com/u/64093255?s=100" /><br /><sub><b>Yisus7u7</b></sub></a></td>
  </tr>
</table>

<!-- // -->
