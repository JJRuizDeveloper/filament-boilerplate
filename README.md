## Requirements

- **PHP >= 8.1** (with: `BCMath`, `Ctype`, `Fileinfo`, `JSON`, `Mbstring`, `OpenSSL`, `PDO`, `Tokenizer`, `XML`)
- **Composer**
- **MySQL/MariaDB/PostgreSQL**
- **Web Server**
- **Node.js** y **npm/yarn**

## How To Installyes

### 1. Clone Repository


```bash
git clone https://github.com/jjruizdeveloper/filament-boilerplate
cd filament-boilerplate

```

### 2. Install Dependencies

```bash
composer install
npm install
npm run build
cp .env.example .env
php artisan key:generate
```

## Settings

### 1. Run migrations and kan-ban styling
```bash
php artisan migrate
php artisan filament-kanban:install
```

### 2. Create FilamentPHP admin account
```bash
php artisan hexa:account --create
```