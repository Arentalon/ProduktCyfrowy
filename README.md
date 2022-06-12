# cms
Komenda na wykonanie migracji (najlepiej wykonać po każdej aktualizacji z gita, potrzebna gdy pojawia się nowa migracja w katalogu migrations)

php bin/console doctrine:migrations:migrate

Czyszczenie cache'a (może się przydać, np zamiast composer install jak odświeżasz projekt w przeglądarce)

php bin/console cache:clear
