# 🍨 Main-Plus 🍨

[![Excavator](https://github.com/Scoopforge/Main-Plus/actions/workflows/ci.yml/badge.svg)](https://github.com/Scoopforge/Main-Plus/actions/workflows/ci.yml)
[![license](https://img.shields.io/github/license/Scoopforge/Main-Plus)](https://github.com/Scoopforge/Main-Plus/blob/master/LICENSE)
[![code size](https://img.shields.io/github/languages/code-size/Scoopforge/Main-Plus.svg)](https://img.shields.io/github/languages/code-size/Scoopforge/Main-Plus.svg)
[![repo size](https://img.shields.io/github/repo-size/Scoopforge/Main-Plus.svg)](https://img.shields.io/github/repo-size/Scoopforge/Main-Plus.svg)

A Bucket for the Best Windows Package Manager [Scoop](https://github.com/ScoopInstaller/Scoop): An Enhancement for the Official CLI Bucket.

> If you would like to be a co-maintainer, feel free to tell me in the Discussion.

For ones familiar with Scoop:

```powershell
scoop bucket add main-plus https://github.com/Scoopforge/Main-Plus
```

Enjoy the fun of command line!

# 🏃 To Start

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

For more information, please visit Scoop official site at 👉 https://scoop.sh/ 👈

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

|                                   App                                   |  Language  | Auto-Update ? |
| :---------------------------------------------------------------------: | :--------: | :-----------: |
|          [cargo-dist](https://github.com/axodotdev/cargo-dist)          |    rust    |       ✓       |
|             [chatgpt-cli](https://github.com/j178/chatgpt)              |     go     |       ✓       |
|          [cxx2flow](https://github.com/Enter-tainer/cxx2flow)           |    rust    |       ✓       |
| [excalidraw-converter](https://github.com/sindrel/excalidraw-converter) |     go     |       ✓       |
|               [gauth](https://github.com/pcarrier/gauth)                |     go     |       ✓       |
|        [ltex-ls-plus](https://github.com/ltex-plus/ltex-ls-plus)        |   kotlin   |       ✓       |
|                 [mado](https://github.com/akiomik/mado)                 |    rust    |       ✓       |
|            [micromamba](https://github.com/mamba-org/mamba)             |    c++     |       ✓       |
|        [neocmakelsp](https://github.com/neocmakelsp/neocmakelsp)        |    rust    |       ✓       |
|          [n-m3u8dl-re](https://github.com/nilaoda/N_m3u8DL-RE)          |     c#     |       ✓       |
|               [pixi](https://github.com/prefix-dev/pixi)                |    rust    |       ✓       |
|         [pscompletions](https://github.com/abgox/PSCompletions)         | powershell |       ✓       |
|                         [qlty](https://qlty.sh)                         |    rust    |       ✓       |
|             [sendme](https://github.com/n0-computer/sendme)             |    rust    |       ✓       |
|             [serpl](https://github.com/yassinebridi/serpl)              |    rust    |       ✓       |
|           [shiroa](https://github.com/Myriad-Dreamin/shiroa)            |    rust    |       ✓       |
|              [sttr](https://github.com/abhimanyu003/sttr)               |     go     |       ✓       |
|            [tex-fmt](https://github.com/WGUNDERWOOD/tex-fmt)            |    rust    |       ✓       |
|          [typstyle](https://github.com/Enter-tainer/typstyle)           |    rust    |       ✓       |
|         [wthrr](https://github.com/ttytm/wthrr-the-weathercrab)         |    rust    |       ✓       |
