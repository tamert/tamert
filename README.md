<a href="https://github.com/tamert/tamert">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="dark_mode.svg">
    <img alt="tamert's GitHub Profile README" src="light_mode.svg">
  </picture>
</a>

## Notlar

- GitHub profilinde görünmesi için repo adının kullanıcı adınla aynı olması gerekir: `tamert/tamert`.
- Otomatik güncelleme `.github/workflows/build.yaml` ile çalışır.
- Gerekli ayarlar (Repo Settings → Secrets and variables → Actions):
  - `ACCESS_TOKEN` (önerilir): Fine-grained PAT (repo/okuma izinleri). Yoksa `GITHUB_TOKEN` ile deniyor.
  - `USER_NAME` (opsiyonel): Varsayılan `tamert`.
  - Opsiyonel profil alanları: `PROFILE_TITLE`, `PROFILE_OS`, `PROFILE_HOST`, `PROFILE_KERNEL`, `PROFILE_IDE`, `PROFILE_LANG_PROG`, `PROFILE_LANG_COMP`, `PROFILE_LANG_REAL`, `PROFILE_HOBBY_SOFT`, `PROFILE_HOBBY_HARD`, `PROFILE_WEBSITE`, `PROFILE_LINKEDIN`, `PROFILE_DISCORD`, `PROFILE_EMAIL`.
