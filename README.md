# Architecture-driven Software Development

Jest to propozyzcja wykorzystania Architecture-driven software development w rozwoju aplikacji Frontend

## Wstęp

Każda strona internetowa cechuje się wykorzystaniem tych samych elementów jak:

- Nagłówek (Header)
- Główna treść (Main Content)
- Pasek boczny (Sidebar)
- Stopka (Footer)

Czy innych dodatkowych elementów :
- Formularze
- Przyciski
- Elementy nawigacyjne (Breadcrumbs)
- Elementy multimedialne
- Modele i Pop-Upy
- Karuzele (Slidery)
- Card Elements (Karty) - Proste Kontenery zawierające informacje.
- Sekcje i Kontenery
- Tabelki
- Listy
- Zakładki (Tabs)
- Pasek postępu
- Pola Tekstowe, Pola wyboru
- Komunikaty o błędach
- Ikony
- Paginacja
- itd.

Każdy z tych elementów mógłby być przedstawiony jako abstrakcyjny element pod postacią diagramu. 

![architecture-drive-design](https://github.com/RezixDev/architektura-frontend/assets/128291517/69e7ab69-75be-4ee8-b19b-c504ff728f30)

Tym sposobem posiadamy generalny obraz tego jakie elementy będą potrzebne nam do stworzenia naszej strony internetowej i na podstawie których będziemy w stanie niezależnie od Frameworka stworzyć potrzebne nam komponenty. 

Tym sposobem też unikniemy problemu, że posiadamy dwa podobne komponenty, które robią to samo.

Dzięki temu będzie również nas projekt bardziej dostosowany pod regułę DRY

https://pl.wikipedia.org/wiki/DRY

Jeżeli byśmy na podstawie takiej Architektury stworzyli komponenty pod danego Frameworka, to osiągniemy również możliwość ponownego użycia tych samych elementów w innych projektach.

Taki Workflow wymaga również tworzenia modułów CSS do stylizacji komponentów, aby zachować możliwość wymienialnego Designu. 

Ogólna zasada jest taka, że:

Nasza aplikacja składa się z:
- Modułów
  - które posiadają Componenty
    - które są wystylizowane w modułach CSS 
