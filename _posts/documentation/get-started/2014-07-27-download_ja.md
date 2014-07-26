---
layout: post
title: Download
categories: docs docs-get-started
permalink: download_ja.html
---

**ノート** バイナリパッケージは、自由に利用することが可能です。バイナリパッケージのプラットフォームを準備するために申請を行う必要はありません。パッケージの開発者たちは全てのリリースされているソースに目を向け、バイナリパッケージが利用可能になるために最善の努力を行っています。

**ノート** 

ダウンロードサービスは、[Bitbucket](https://bitbucket.org/ariya/phantomjs/downloads)のから提供されています。前回リリースバージョンは、[Google Code Project Hosting](http://code.google.com/p/phantomjs/downloads/)からダウンロードをすることが可能です。

## Windows

[phantomjs-1.9.7-windows.zip](https://bitbucket.org/ariya/phantomjs/downloads/phantomjs-1.9.7-windows.zip) (6.7 MB) からダウンロードを行い、解凍してください。

解凍された `phantomjs.exe` から使用することができます。

**ノート**: For this static build, the binary is self-contained with no external dependency. It will run on a fresh install of Windows XP or later versions. There is no requirement to install Qt, WebKit, or any other libraries.

## Mac OS X

Download [phantomjs-1.9.7-macosx.zip](https://bitbucket.org/ariya/phantomjs/downloads/phantomjs-1.9.7-macosx.zip) (9.0 MB) and extract (unzip) the content.

The binary `bin/phantomjs` is ready to use.

**Note**: For this static build, the binary is self-contained with no external dependency. It will run on a fresh install of Snow Leopard or later versions. There is no requirement to install Qt or any other libraries.

**Alternative** installation using Homebrew:

<pre>brew update &amp;&amp; brew install phantomjs</pre>

**Alternative** installation using MacPorts:

<pre>sudo port selfupdate &amp;&amp; sudo port install phantomjs</pre>

## Linux

For 64-bit system, download [phantomjs-1.9.7-linux-x86_64.tar.bz2](https://bitbucket.org/ariya/phantomjs/downloads/phantomjs-1.9.7-linux-x86_64.tar.bz2) (12.6 MB).

For 32-bit system, download [phantomjs-1.9.7-linux-i686.tar.bz2](https://bitbucket.org/ariya/phantomjs/downloads/phantomjs-1.9.7-linux-i686.tar.bz2) (12.9 MB).

This package is built on CentOS 5.8. It should run successfully on Lucid or more modern systems (including other distributions). There is no requirement to install Qt, WebKit, or any other libraries. It is however expected that some base libraries necessary for rendering ([FreeType](http://www.freetype.org/), [Fontconfig](http://www.freedesktop.org/wiki/Software/fontconfig)) and the basic font files are available in the system.

To install the dependencies on Red Hat based systems:
<pre>sudo yum install fontconfig freetype libfreetype.so.6 libfontconfig.so.1 libstdc++.so.6</pre>

Alternatively (for Unix-like systems), install the distribution-specific package using the native package manager (`apt-get` for Ubuntu and Debian, `pacman` for Arch Linux, `pkg_add` for OpenBSD, etc). **Warning**: The distribution-specific package may not always be on the latest stable version.

For older systems, please compile PhantomJS from source (see below).

## Source Code

Download [phantomjs-1.9.7-source.zip](https://bitbucket.org/ariya/phantomjs/downloads/phantomjs-1.9.7-source.zip) (38.8 MB) and follow the [build instructions]({{ site.url }}/build.html).

## Checksums

To verify the integrity of the downloaded files, use the following checksums.

### MD5 Checksums

    9c1426eef5b04679d65198b1bdd6ef88 phantomjs-1.9.7-linux-i686.tar.bz2
    f278996c3edd0e8d8ec4893807f27d71 phantomjs-1.9.7-linux-x86_64.tar.bz2
    b8621939c7e84b17df31af215882f280 phantomjs-1.9.7-macosx.zip
    5d308d2db7d8b494f99dbb5664447547 phantomjs-1.9.7-source.zip
    706f4171a941dddd429dc935cb0ef7fa phantomjs-1.9.7-windows.zip

### SHA-256 Checksums

    2a49bb20ee4b71b8ac1837857a4dddd52f3217d1356afe58e17c5a4e4829cdb9  phantomjs-1.9.7-linux-i686.tar.bz2
    473b19f7eacc922bc1de21b71d907f182251dd4784cb982b9028899e91dcb01a  phantomjs-1.9.7-linux-x86_64.tar.bz2
    72731f8ff68db17ecb5f6c78bf036adb429317b9bdbe69e2f5f60514fa7e4a6f  phantomjs-1.9.7-macosx.zip
    0f6c50ff24c1c4a8ccd7fedef62feef5e45195c7ba5ef6c84434448544877ff3  phantomjs-1.9.7-source.zip
    5b2b1c87902fa67f23ae7b9c5f7652d1a4d81b41dc9f260b23e0f6335aa4a65e  phantomjs-1.9.7-windows.zip
