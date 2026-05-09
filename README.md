# SQLCipher PHP 8.2 TS x64 Windows Builder

Builds `php_pdo_sqlite.dll` compiled against SQLCipher (AES-256 encrypted SQLite)
for use with PHP 8.2 Thread Safe x64 on Windows.

## Target specs
- PHP 8.2.12
- Thread Safe (TS / ZTS)
- x64
- Visual C++ 2019 (VS16)

## How to use

1. Create a new GitHub repository
2. Push this entire folder to it
3. Go to **Actions** tab on GitHub
4. Click **Build SQLCipher PHP 8.2 TS x64 Windows**
5. Click **Run workflow** → keep default SQLCipher tag → click green **Run workflow**
6. Wait ~15 minutes
7. Download the artifact `php_pdo_sqlcipher-php82-ts-x64-vs16`
8. Inside is `php_pdo_sqlcipher.dll` — rename it to `php_pdo_sqlite.dll`
   and replace the one in `YaribillingDesktop\php\ext\`

## Attribution requirement
SQLCipher is BSD-licensed. Add to your app's About screen:
"Uses SQLCipher by Zetetic LLC (https://www.zetetic.net/sqlcipher/)"
