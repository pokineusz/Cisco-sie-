W ramach przygotowanych ćwiczeń skonfigurowałem sieć komputerową, obejmującą router, switche, punkt dostępowy (AP), a także urządzenia końcowe (w tym serwery). Przedstawiam poniżej zestaw głównych działań i ustawień:
1.	Zabezpieczenie dostępu konsolowego
-	Na routerze i wszystkich switchach skonfigurowałem hasło konsolowe „12345”. Zapewnia ono podstawową ochronę przed nieautoryzowanym dostępem.
2.	Adresacja IPv4 i IPv6
- Wszystkie urządzenia w sieci zostały przypisane do adresów statycznych IPv4 oraz IPv6 zgodnie z założonym podziałem sieci.
3.	Serwer HTTP i strona internetowa
-	Na serwerze HTTP uruchomiłem prostą stronę internetową, aby sprawdzić komunikację w obrębie sieci oraz testować zapytania przy użyciu protokołu HTTP.
4.	Konfiguracja serwera DNS
-	Serwer DNS został skonfigurowany do obsługi zapytań o nazwę domeny dla postawionej strony WWW. W ten sposób użytkownicy mogą łączyć się z serwerem HTTP, używając nazwy domeny.
5.	Serwer DHCP
-	W celu automatycznego przydzielania adresów IP dla gości skonfigurowałem serwer DHCP. Dzięki temu urządzenia gości nie muszą być ręcznie adresowane.
6.	Punkt dostępowy dla urządzeń mobilnych
-	AP został skonfigurowany w sieci, aby zapewnić łączność bezprzewodową dla gości.
-	Skonfigurowano podstawowe bezpieczeństwo, aby ograniczyć dostęp osobom niepożądanym (dostęp przez WPA2-PSK).
7.	Dostęp zdalny do urządzeń
-	Router jest dostępny zdalnie poprzez SSH 
-	Switche obsługują zdalne połączenia Telnet/SSH
-	W obydwu przypadkach login: admin, hasło: 12345
