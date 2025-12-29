# 🍨 Main-Plus 🍨

[![Excavator](https://github.com/Scoopforge/Main-Plus/actions/workflows/ci.yml/badge.svg)](https://github.com/Scoopforge/Main-Plus/actions/workflows/ci.yml)
[![license](https://img.shields.io/github/license/Scoopforge/Main-Plus)](https://github.com/Scoopforge/Main-Plus/blob/master/LICENSE)
[![code size](https://img.shields.io/github/languages/code-size/Scoopforge/Main-Plus.svg)](https://img.shields.io/github/languages/code-size/Scoopforge/Main-Plus.svg)
[![repo size](https://img.shields.io/github/repo-size/Scoopforge/Main-Plus.svg)](https://img.shields.io/github/repo-size/Scoopforge/Main-Plus.svg)

A Bucket for the Best Windows Package Manager [Scoop](https://github.com/ScoopInstaller/Scoop): An Enhancement for the Official CLI Bucket.

> If you would like to be a co-maintainer, feel free to tell me in the Discussion.

Enjoy the fun of command line!

## 🏃 To Start

For ones familiar with Scoop:

```powershell
scoop bucket add main-plus https://github.com/Scoopforge/Main-Plus
```

## 🚲 Install Scoop

### 💻 Step 1: Enable remote policy in PowerShell

```powershell
Set-ExecutionPolicy RemoteSigned -scope CurrentUser
```

### ⚙️ Step 2: Download and install Scoop

```powershell
irm get.scoop.sh -outfile 'install.ps1'
.\install.ps1 -ScoopDir ['Scoop_Path'] -ScoopGlobalDir ['GlobalScoopApps_Path'] -NoProxy
# for example
.\install.ps1 -ScoopDir 'C:\Scoop' -ScoopGlobalDir 'C:\Program Files' -NoProxy
```

> If you skip this step, all user installed Apps and Scoop itself will live in `c:/users/user_name/scoop`.

### 📖 Step 3: Glance at quick-start by `scoop help`

For more information, please visit Scoop official site at 👉 <https://scoop.sh/> 👈

## 🚗 Install Apps from this bucket

### 🚋 Step 1: Install Aria2 to accelerate downloading

```powershell
scoop install aria2
```

### 🎫 Step 2: Install Git to add new repositories

```powershell
scoop install git
```

### ✈️ Step 3: Add this wonderful bucket and update, mua~ 💋

```powershell
scoop bucket add main-plus https://github.com/Scoopforge/Main-Plus
scoop update
```

### 🚀 Step 4: Install CLI

```powershell
scoop install <cli_name>
```

## 📝 Trivial

### Tweaking Parameters of Aria2

```powershell
scoop config aria2-enabled true
scoop config aria2-retry-wait 4
scoop config aria2-split 16
scoop config aria2-max-connection-per-server 16
scoop config aria2-min-split-size 4M
```

## ⭐️ Summary

|                                   App                                   | Language | Auto-Update ? |
|:-----------------------------------------------------------------------:|:--------:|:-------------:|
|          [cargo-dist](https://github.com/axodotdev/cargo-dist)          |   Rust   |       ✓       |
|     [cargo-update](https://github.com/nabijaczleweli/cargo-update)      |   Rust   |       ✓       |
|             [chatgpt-cli](https://github.com/j178/chatgpt)              |    Go    |       ✓       |
|            [choose](https://github.com/theryangeary/choose)             |   Rust   |       ✓       |
|                   [commix](https://commixproject.com)                   |   Rust   |       ✓       |
|          [cryptomator-cli](https://github.com/cryptomator/cli)          |   Rust   |       ✓       |
|          [cxx2flow](https://github.com/Enter-tainer/cxx2flow)           |   Rust   |       ✓       |
| [excalidraw-converter](https://github.com/sindrel/excalidraw-converter) |    Go    |       ✓       |
|                [flow-control](https://flow-control.dev)                 |   Zig    |       ✓       |
|            [fresh-editor](https://github.com/sinelaw/fresh)             |   Rust   |       ✓       |
|               [gauth](https://github.com/pcarrier/gauth)                |    Go    |       ✓       |
|         [json-tui](https://github.com/ArthurSonzogni/json-tui)          |   C++    |       ✓       |
|              [lazyssh](https://github.com/Adembc/lazyssh)               |    Go    |       ✓       |
|        [ltex-ls-plus](https://github.com/ltex-plus/ltex-ls-plus)        |  Kotlin  |       ✓       |
|            [micromamba](https://github.com/mamba-org/mamba)             |   C++    |       ✓       |
|               [nebula](https://github.com/slackhq/nebula)               |    Go    |       ✓       |
|        [neocmakelsp](https://github.com/neocmakelsp/neocmakelsp)        |   Rust   |       ✓       |
|          [n-m3u8dl-re](https://github.com/nilaoda/N_m3u8DL-RE)          |    C#    |       ✓       |
|               [pixi](https://github.com/prefix-dev/pixi)                |   Rust   |       ✓       |
|                         [qlty](https://qlty.sh)                         |   Rust   |       ✓       |
|                 [rumdl](https://github.com/rvben/rumdl)                 |   Rust   |       ✓       |
|             [sendme](https://github.com/n0-computer/sendme)             |   Rust   |       ✓       |
|             [serpl](https://github.com/yassinebridi/serpl)              |   Rust   |       ✓       |
|           [shiroa](https://github.com/Myriad-Dreamin/shiroa)            |   Rust   |       ✓       |
|              [sttr](https://github.com/abhimanyu003/sttr)               |    Go    |       ✓       |
|            [tex-fmt](https://github.com/WGUNDERWOOD/tex-fmt)            |   Rust   |       ✓       |
|             [typship](https://github.com/sjfhsjfh/typship)              |   Rust   |       ✓       |
|         [wthrr](https://github.com/ttytm/wthrr-the-weathercrab)         |   Rust   |       ✓       |
|               [yutu](https://github.com/eat-pray-ai/yutu)               |    Go    |       ✓       |
