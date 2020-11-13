# erp_inventory_entries

ZAŁOŻENIA:

- rodzaje transakcji:
   -- przyjęcia od dostawcy - 1.OBJ
   -- przyjęcia z produkcji - 1.OBJ
   -- wyjście do klienta - wysyłka - 2.OBJ
   -- wyjście na produkcję - 2.OBJ
  
   -- faktura zakupu 3.OBJ
   -- faktura sprzedaży 4.OBJ
  
 - produkty:
   5 rodzajów raw materials 5.OBJ
   2 rodzaje finished products 6.OBJ
   
  - magazyn:
     -- stany magazynu - 7.OBJ.
     
   - transakcje księgowe
     -- lista ze stosem transakcji
     
  - konta księgowe - KLASA
    -- konto przyjęć - KLASA POCHODNA 
    -- konto wyjść - KLASA POCHODNA
    -- balance sheet?
