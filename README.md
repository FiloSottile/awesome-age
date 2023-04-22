# Awesome age

<p align="center">
    <picture>
        <source media="(prefers-color-scheme: dark)" srcset="https://github.com/FiloSottile/age/blob/main/logo/logo_white.svg">
        <source media="(prefers-color-scheme: light)" srcset="https://github.com/FiloSottile/age/blob/main/logo/logo.svg">
        <img alt="The age logo, an wireframe of St. Peters dome in Rome, with the text: age, file encryption" width="600" src="https://github.com/FiloSottile/age/blob/main/logo/logo.svg">
    </picture>
</p>

A collection of projects and resources in the age file encryption ecosystem.

* [Implementations](#implementations)
* [Plugins](#plugins)
* [GUIs](#guis)
* [Tools](#tools)
* [Integrations](#integrations)
* [Articles](#articles)
* [Users](#users)
* [Development](#development)

For more, explore [the *age-encryption* GitHub topic](https://github.com/topics/age-encryption)!

⭐️ Featured or official — 🧪 Beta or experimental

## Implementations

* ⭐️ [age](https://filippo.io/age) — CLI and Go reference implementation, with native keys, SSH keys, passphrase, and plugin support.

* ⭐️ [rage](https://str4d.xyz/rage) — Rust implementation, fully interoperable and feature complete.

* 🧪 [github.com/str4d/wage](https://github.com/str4d/wage) — WASM package powered by rage.

## Plugins

* ⭐️ [age-plugin-yubikey](https://github.com/str4d/age-plugin-yubikey) — YubiKey (and other PIV tokens) plugin.

## GUIs

* ⭐️ [Winage](https://winage.spiegl.dev/) — Contextual menu driven Windows GUI.

* 🧪 [rage-encry.pt](https://rage-encry.pt/) — In-browser encryption/decryption tool powered by wage.

## Tools

* ⭐️ [passage](https://github.com/FiloSottile/passage) — Fork of password-store that uses age in place of gpg.

* [PaperAge](https://github.com/matiaskorhonen/paper-age) — Easy and secure paper backups of secrets.

## Integrations

## Articles

* [age and Authenticathed Encryption](https://words.filippo.io/dispatches/age-authentication/)

* [KEMs and Post-Quantum age](https://words.filippo.io/dispatches/post-quantum-age/)

* [My age+YubiKeys Password Management Solution](https://words.filippo.io/dispatches/passage/)

* [gitattributes age encrypt](https://seankhliao.com/blog/12020-09-24-gitattributes-age-encrypt/) — Encrypting and decrypting files with gitattributes.

## Users

* [Logseq](https://web.archive.org/web/20230422154136/https://twitter.com/logseq/status/1587905208667230209)

## Development

* ⭐️ [age-encryption.org/v1](https://age-encryption.org/v1) — The official file format specification.

* [c2sp.org/CCTV/age](https://c2sp.org/CCTV/age) — Comprehensive implementation-agnostic test suite of over 100 vectors.

* 🧪 C2SP/C2SP#5 — age-plugin spec (draft)
