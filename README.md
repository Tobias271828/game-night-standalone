# Game Night – standalone version

Browser games for game nights with friends (Trombone, Who am I?, four-player chess, Four in a Row) on any
PHP web space – without a database, accounts or third-party services. User interface in German and English.

This repository only hosts the **ready-to-use standalone package**. Source code, documentation, issues and
the Grav plugin are in **[grav-plugin-game-night](https://github.com/Tobias271828/grav-plugin-game-night)**.

## Installation

Requirements: PHP ≥ 8.0 and a writable folder; Apache is recommended.

1. Download `game-night-standalone-<version>.zip` from the [releases](../../releases) and unpack it to your
   web space (e.g. as the document root of a subdomain).
2. Copy `config.example.php` to `config.php` and adjust it. Ideally set `data_dir` to a folder outside the
   web root; otherwise `data/.htaccess` protects it (Apache only).
3. **Updates:** replace `core/`, `assets/` and `index.php` – `config.php` and your data stay untouched.

More details (options, security, running a public instance) are in the
[README of the main repository](https://github.com/Tobias271828/grav-plugin-game-night#standalone).

## License

MIT – see the [main repository](https://github.com/Tobias271828/grav-plugin-game-night/blob/main/LICENSE).
