# Belgrade Open - Sistem za prodaju teniskih karata

Ovaj projekat predstavlja Full-Stack Web aplikaciju za online prodaju i upravljanje kartama za teniski turnir **Belgrade Open**. Projekat je razvijen kao deo akademskih aktivnosti na Fakultetu organizacionih nauka (FON).

## Tehnologije

Projekat je realizovan korišćenjem modernih tehnologija:
*   **Backend:** Laravel (PHP) - REST API
*   **Frontend:** React (JavaScript)
*   **Baza podataka:** MySQL (XAMPP)

## Struktura Projekta

Aplikacija je organizovana kao monorepo sa jasno razdvojenim slojevima:
*   `/backend` - Laravel API, migracije i seederi.
*   `/frontend` - React aplikacija za korisnički interfejs.

## Podešavanje i Pokretanje

### 1. Backend (Laravel)
Uđite u folder gde se nalazi `artisan` fajl i pokrenite:
```bash
composer install
php artisan migrate --seed
php artisan serve

### 2. Frontend (React)
Uđite u folder gde se nalazi package.json i pokrenite:
```bash
npm install
npm start