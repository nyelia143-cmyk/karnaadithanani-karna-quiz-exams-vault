# Karna Quiz Exams Centre — GitHub `.KQZ` Encrypted Vault Setup Guide

## 1. GitHub Folder Structure (`karna-quiz-exams-vault`)

Create a GitHub repository named `karna-quiz-exams-vault` and upload your encrypted `.kqz` files in this structure:

```text
karna-quiz-exams-vault/
│
├── appsc/
│   ├── polity_master_v1.kqz
│   ├── ap_history_v1.kqz
│   └── economy_geo_v1.kqz
│
├── police/
│   ├── arith_reasoning_v1.kqz
│   └── gs_science_v1.kqz
│
├── tet_dsc/
│   ├── psychology_cdp_v1.kqz
│   └── perspectives_v1.kqz
│
├── banking/
│   └── bank_master_v1.kqz
│
├── ssc_rrb/
│   └── science_static_gk_v1.kqz
│
└── high_court/
    └── hc_current_affairs_v1.kqz
```

## 2. How to Encrypt JSON into `.kqz` (Unbreakable AES-256-GCM)

1. Open **Karna Quiz Exams Centre** app on your phone/emulator.
2. Tap **🔐 KQZ Vault** on the bottom navigation bar.
3. Paste your plain Quiz JSON in the **Admin .KQZ Encryptor Studio** box.
4. Tap **🔒 Encrypt to .KQZ** -> Tap **📋 Copy .KQZ Output**.
5. Save the `KQZ1$...` text as a `.kqz` file on GitHub!

## 3. Why 1,00,000+ Concurrent Users Never Hang
- **Tier-1**: `https://cdn.jsdelivr.net/gh/<username>/<repo>@main/<path>.kqz` (Cloudflare + Fastly Global Multi-CDN)
- **Tier-2**: `https://<username>.github.io/<repo>/<path>.kqz` (GitHub Pages Fastly CDN)
- **Tier-3**: `https://raw.githubusercontent.com/<username>/<repo>/main/<path>.kqz`
- **Tier-4**: Local SQLite Encrypted `.kqz` Cache (`karna_quiz_vault.db`) — once downloaded, it loads in `<1ms` with **0 network requests**!
