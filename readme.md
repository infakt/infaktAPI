# Readme

### Import
Zaimportuj plik Infakt - API Documentation.postman_collection.json do Postmana. <br>
Zaimportuj plik infakt.postman_environment.json do Postmana. 
 

Do zmiennych środowiskowych w Postmanie dla api_key podaj swój unikalny klucz (patrz https://www.infakt.pl/developers/general/#authentication) oraz email - pamiętaj aby zapisać zmiany! 

Projekt w wielu miejscach generuje losowe dane, np. adres, nazwa klienta itp.  

### Ważne: 
 - Dla endpoitu deliver_via_post.json dla invoices potrzebny jest dodatkowy pakiet. <br>
 - Endpoint attachments.json oraz attachment.json w invoices może nic nie zwrócić jeśli do FV nie ma załączników - nie jest to błąd. <br>
 - Endpoint sign.json w corrective invoice jest od 2021 niewspierany. <br>
 - Endpoint vat_taxes.json oraz vat_tax.json od 1 października 2020 jest niewspierany ze względów na obowiązek przesyłania nowych struktur JPK z częścią deklaracyjną do Ministerstwa Finansów - został on zastąpiony saf_v7_file. Jeśli nie posiadałeś do 1.10.2020 żadnych fv spełniajacych warunek wysyłki vat w chwili obecnej elementy nic nie zwrócą. <br>
 - Endpointy związane z fv MOSS od 1 lipca 2021 jest niewspierany ze względu na zmianę fv MOSS na OSS. Jeśli nie posiadałeś do 1.07.2021 żadnych fv MOSS elementy nic nie zwrócą. <br>
