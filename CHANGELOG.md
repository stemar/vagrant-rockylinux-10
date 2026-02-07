# Changelog

## 1.1.0 - 2026-02-07

### Added

- Added `config/php.ini` that will be located in `/var/www` to override Apache's `php.ini`
- Added `PHPINIDir` and `SetEnv PHP_INI_SCAN_DIR` in `config/virtualhost.conf`
- New `PHP_VERSION` is handled in `provision.sh`

### Changed

- Modified alias `ll` in `config/bashrc`
- Updated `README.md`

### Removed

- Deleted `config/php.ini.htaccess`
    - `.htaccess` is no longer used to override Apache's `php.ini`
- Removed `:php_error_reporting` from `settings.yaml`
- Removed `PHP_ERROR_REPORTING` from `Vagrantfile`
- Removed `PHP_ERROR_REPORTING_INT` and its handling from `provision.sh`

## 1.0.2 - 2026-01-19

### Added

- Added Ruby gem `irb`.

### Changed

- Changed Adminer theme.
- Made Ruby installation by default.
- Replaced download and make with `dnf install`.

### Removed

- Deleted `config/gemrc` file.
- Removed rbenv and bundler.

## 1.0.0 - 2026-01-15

_First release_
