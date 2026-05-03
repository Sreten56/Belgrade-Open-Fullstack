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
Da biste pokrenuli projekat lokalno, pratite ove korake:

### 1. Backend (Laravel)
Pozicionirajte se u folder gde se nalazi artisan fajl (obično /backend ili dublje, zavisno od tvoje strukture) i pokrenite sledeće komande:
#### Instalacija PHP zavisnosti
composer install
#### Kreiranje tabela i popunjavanje baze demo podacima
php artisan migrate --seed
#### Pokretanje lokalnog razvojnog servera
php artisan serve

### 2. Frontend (React)
Otvorite novi terminal, pozicionirajte se u folder gde se nalazi package.json (obično /frontend) i pokrenite:
#### Instalacija Node.js paketa
npm install
#### Pokretanje React aplikacije
npm start