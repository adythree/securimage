# adythree/securimage

Fork dari [dapphp/securimage](https://github.com/dapphp/securimage) yang sudah abandoned.
Maintained oleh Sofyan Adiyatma (adythree).

## Info repo
- **GitHub:** https://github.com/adythree/securimage
- **Packagist:** https://packagist.org/packages/adythree/securimage
- **Branch aktif:** `nextgen` (default)
- **Local:** `~/code/github/securimage/`

## Alur maintenance
1. Edit file di branch `nextgen`
2. Commit + push: `git push origin nextgen`
3. Tag versi baru: `git tag v4.0.x && git push origin v4.0.x`
4. Packagist auto-detect tag baru via webhook

## Versioning
- `v4.0.3` — PHP 8.3 fix: `GdImage` type hint, missing properties (`$gdnoisecolor`, `$code_entered`, `$correct_code`, `$namespace`)

## Dipakai oleh project
Semua project adythree framework — lihat `dd.php/composer.json` di masing-masing project.
Ganti `dapphp/securimage` → `adythree/securimage` sudah selesai di semua project (2026-06-10).

## Kontak
sofyan.adiyatma@gmail.com
