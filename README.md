<!-- GM PHISH -->

<p align="center">
  <img src=".github/misc/logo.png">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Version-2.3.5-green?style=for-the-badge">
  <img src="https://img.shields.io/github/license/Mohanrajx?style=for-the-badge">
  <img src="https://img.shields.io/github/stars/Mohanrajx/GMphish?style=for-the-badge">
  <img src="https://img.shields.io/github/issues/Mohanrajx/GMphish?color=red&style=for-the-badge">
  <img src="https://img.shields.io/github/forks/Mohanrajx/GMphish?color=teal&style=for-the-badge">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Author-G--MOHAN RAJ-blue?style=flat-square">
  <img src="https://img.shields.io/badge/Open%20Source-Yes-darkgreen?style=flat-square">
  <img src="https://img.shields.io/badge/Maintained%3F-Yes-lightblue?style=flat-square">
  <img src="https://img.shields.io/badge/Written%20In-Bash-darkcyan?style=flat-square">
  <img src="https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2FMohanrajx%2FGMphish&title=Visitors&edge_flat=false"/></a>
</p>

<p align="center"><b>A beginners friendly, Automated phishing tool with 30+ templates.</b></p>

##

<h3><p align="center">Disclaimer</p></h3>

<i>Any actions and or activities related to <b>GMphish</b> is solely your responsibility. The misuse of this toolkit can result in <b>criminal charges</b> brought against the persons in question. <b>The contributors will not be held responsible</b> in the event any criminal charges be brought against any individuals misusing this toolkit to break the law.

<b>This toolkit contains materials that can be potentially damaging or dangerous for social media</b>. Refer to the laws in your province/country before accessing, using,or in any other way utilizing this in a wrong way.

<b>This Tool is made for educational purposes only</b>. Do not attempt to violate the law with anything contained here. <b>If this is your intention, then Get the hell out of here</b>!

It only demonstrates "how phishing works". <b>You shall not misuse the information to gain unauthorized access to someones social media</b>. However you may try out this at your own risk.</i>

##

### Features

- Latest and updated login pages.
- Beginners friendly
- Multiple tunneling options
  - Localhost
  - Cloudflared
  - LocalXpose
- Mask URL support 
- Docker support

##

### Installation

- Just, Clone this repository -
  ```
  git clone https://github.com/Mohanrajx/GMphish.git
  ```

- Now go to cloned directory and run `GMphish.sh` -
  ```
  $ cd GMphish
  $ unzip GM-Phishh.zip
  $ cd GM-Phish
  $ bash GMphish.sh
  $ bash GMphish.sh
  ```

- On first launch, It'll install the dependencies and that's it. ***GMphish*** is installed.

##

### Installation (Termux)
You can easily install GMphish in Termux by using tur-repo
```
$ pkg install tur-repo
$ pkg install GMphish
$ GMphish
```
### A Note : 
***Termux discourages hacking*** .. So never discuss anything related to *GMphish* in any of the termux discussion groups.

##

<p align="left">
  <a href="https://shell.cloud.google.com/cloudshell/open?cloudshell_git_repo=https://github.com/Mohanrajx/GMphish.git&tutorial=README.md" target="_blank"><img src="https://gstatic.com/cloudssh/images/open-btn.svg"></a>
</p>

##

### Installation via ".deb" file

- Download `.deb` files from the [**Latest Release**](https://github.com/Mohanrajx/GMphish/releases/latest)
- If you are using ***termux*** then download the `*_termux.deb`

- Install the `.deb` file by executing
  ```
  apt install <your path to deb file>
  ```
  Or
  ```
  $ dpkg -i <your path to deb file>
  $ apt install -f
  ```

##

### Run on Docker

- Docker Image Mirror:
  - **DockerHub** : 
    ```
    docker pull Mohanrajx/GMphish
    ```
  - **GHCR** : 
    ```
    docker pull ghcr.io/Mohanrajx/GMphish:latest
    ```

- By using the wrapper script [**run-docker.sh**](https://raw.githubusercontent.com/Mohanrajx/GMphish/master/run-docker.sh)

  ```
  $ curl -LO https://raw.githubusercontent.com/Mohanrajx/GMphish/master/run-docker.sh
  $ bash run-docker.sh
  ```
- Temporary Container

  ```
  docker run --rm -ti Mohanrajx/GMphish
  ```
  - Remember to mount the `auth` directory.

##

<details>
  <summary><h3>Dependencies</h3></summary>

<b>GMphish</b> requires following programs to run properly - 
- `git`
- `curl`
- `php`

> All the dependencies will be installed automatically when you run **GMphish** for the first time.
</details>

<details>
  <summary><h3>Tested on</h3></summary>

- **Ubuntu**
- **Debian**
- **Arch**
- **Manjaro**
- **Fedora**
- **Termux**

