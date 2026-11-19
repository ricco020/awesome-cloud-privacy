# Awesome Cloud Privacy [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Curated list of privacy-respecting cloud storage providers, end-to-end encryption tools, self-host options, jurisdiction analysis, and audit reports.

Companion editorial site: **[Priviy](https://www.priviy.com/)** — independent reviews of cloud privacy providers.

## Contents

- [End-to-end encrypted providers](#end-to-end-encrypted-providers)
- [Zero-knowledge providers](#zero-knowledge-providers)
- [Self-host alternatives](#self-host-alternatives)
- [Encryption layers (any provider)](#encryption-layers-any-provider)
- [Jurisdiction & legal analysis](#jurisdiction--legal-analysis)
- [Audits & transparency reports](#audits--transparency-reports)
- [File-sharing tools](#file-sharing-tools)
- [Password & secrets in the cloud](#password--secrets-in-the-cloud)
- [Backup tools (E2E)](#backup-tools-e2e)
- [Communities](#communities)
- [References](#references)

## End-to-end encrypted providers

- [Proton Drive](https://proton.me/drive) — Swiss, open-source clients, E2E by default.
- [Tresorit](https://tresorit.com/) — Swiss, business-focused, strong compliance suite.
- [Sync.com](https://www.sync.com/) — Canadian, E2E, generous free tier.
- [Mega.io](https://mega.io/) — NZ, E2E, controversial founder but tech audited.
- [Filen.io](https://filen.io/) — EU (Germany), open-source clients.
- [Internxt](https://internxt.com/) — Spain, post-quantum-ready, lifetime pricing.
- [pCloud Crypto](https://www.pcloud.com/encrypted-cloud-storage.html) — Switzerland, opt-in E2E vault (add-on).

## Zero-knowledge providers

- [Tresorit](https://tresorit.com/) — verified zero-knowledge with key escrow option.
- [Sync.com](https://www.sync.com/) — full zero-knowledge architecture.
- [SpiderOak One](https://spideroak.com/one/) — pioneer zero-knowledge backup.
- [IceDrive](https://icedrive.net/) — Twofish encryption, zero-knowledge tier.
- [Internxt](https://internxt.com/) — zero-knowledge with open-source verification.

## Self-host alternatives

- [Nextcloud](https://nextcloud.com/) — full self-host suite (files, calendar, talk, etc.).
- [Seafile](https://www.seafile.com/) — performant E2E sync, open-source.
- [OwnCloud Infinite Scale](https://owncloud.com/infinite-scale/) — Go-based modern rewrite.
- [Garage](https://garagehq.deuxfleurs.fr/) — S3-compatible distributed storage.
- [MinIO](https://min.io/) — high-performance S3 self-host.
- [Syncthing](https://syncthing.net/) — P2P sync without central server.

## Encryption layers (any provider)

- [Cryptomator](https://cryptomator.org/) — open-source client-side encryption for any cloud.
- [rclone crypt](https://rclone.org/crypt/) — encryption backend with cloud-agnostic config.
- [gocryptfs](https://github.com/rfjakob/gocryptfs) — Go encrypted overlay filesystem.
- [age](https://github.com/FiloSottile/age) — modern simple file encryption tool.

## Jurisdiction & legal analysis

- Editorial: [E2E vs zero-knowledge cloud storage 2026 (FR)](https://www.priviy.com/fr/blog/e2e-vs-zero-knowledge-cloud-storage-2026).
- Editorial: [E2E vs zero-knowledge cloud storage 2026 (EN)](https://www.priviy.com/en/blog/e2e-vs-zero-knowledge-cloud-storage-2026).
- [Five Eyes / Fourteen Eyes overview (Wikipedia)](https://en.wikipedia.org/wiki/UKUSA_Agreement).
- [CLOUD Act explained — EFF](https://www.eff.org/issues/cloud-act).
- [GDPR & cloud storage — ENISA](https://www.enisa.europa.eu/publications/).
- [Swiss data protection law — FDPIC](https://www.edoeb.admin.ch/).

## Audits & transparency reports

- [Tresorit security audit reports](https://tresorit.com/security).
- [Proton transparency reports](https://proton.me/blog/transparency-report).
- [Mega source code review (2022, Five Eyes attack)](https://mega.io/security).
- [Tutanota security audit](https://tuta.com/security/).

## File-sharing tools

- [OnionShare](https://onionshare.org/) — Tor-anonymous one-shot file sharing.
- [Bitwarden Send](https://bitwarden.com/products/send/) — small files + secrets.
- [Wormhole.app](https://wormhole.app/) — Magic Wormhole web port.

## Password & secrets in the cloud

- [Bitwarden](https://bitwarden.com/) — open-source password manager (cloud or self-host).
- [Vaultwarden](https://github.com/dani-garcia/vaultwarden) — unofficial Bitwarden server in Rust.
- [Proton Pass](https://proton.me/pass) — Swiss password manager E2E.
- [KeePassXC](https://keepassxc.org/) — local-first password DB.

## Backup tools (E2E)

- [Restic](https://restic.net/) — encrypted, deduplicated backups (any backend).
- [Borg Backup](https://www.borgbackup.org/) — efficient deduplicating archiver.
- [Duplicacy](https://duplicacy.com/) — fast lock-free deduplication.
- [Arq](https://www.arqbackup.com/) — Mac/Windows GUI to any cloud (E2E).
- [Kopia](https://kopia.io/) — modern Go-based encrypted backup.

## Communities

- [r/privacy](https://www.reddit.com/r/privacy/).
- [r/PrivacyToolsIO](https://www.reddit.com/r/PrivacyToolsIO/) → moved to [Privacy Guides](https://www.privacyguides.org/).
- [r/selfhosted](https://www.reddit.com/r/selfhosted/) — for self-host alternatives.
- [r/cryptography](https://www.reddit.com/r/cryptography/).

## References

- [Privacy Guides](https://www.privacyguides.org/en/) — independent recommendations.
- [PRISM Break](https://prism-break.org/en/) — escape mass-surveillance services.
- [EFF — Surveillance Self-Defense](https://ssd.eff.org/).
- [NIST SP 800-209 — Security Guidelines for Storage Infrastructure](https://csrc.nist.gov/publications/detail/sp/800-209/final).

## Contributing

PRs welcome. Providers must publish their encryption model (whitepaper or technical docs) and have at least one third-party audit OR open-source clients. Marketing-heavy entries rejected.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)
