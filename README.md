# ParkingRampa

U radu se opisuje implementacija pojednostavljene rampe za ogranicavanje ulaza na parking. Rampa se sastoji od nekoliko kljucnih elemenata, ukljucujuci parking taster, parking rampu, potenciometar i IC senzor.
Parking taster omogucava vozacu da podigne rampu pritiskom na taster, što omogucava prolaz automobila. Istovremeno, generira se potvrda o ulasku sa zabilježenim vremenom ulaska. 
Parking rampa se podiže i spušta pomocu DC motora visoke snage. Motor se okrece u jednom smjeru kako bi se rampa podigla, dok se u drugom smjeru rampa spušta. 
Za mjerenje pozicije (ugla) rampe koristi se potenciometar koji ima linearnu promjenu otpora. 
Ovisno o položaju rampe, potenciometar mjeri odredenu vrijednost otpora, što omogucava odredivanje ugla nagiba rampe. Infracrveni senzor provjerava prisutnost vozila ispod rampe. 
To sprjecava neželjeno spuštanje rampe ako vozilo još nije prošlo.
Implementacija ovih elemenata omogucava efikasno upravljanje rampom za ogranicavanje ulaza na parking, osiguravajuci siguran i kontroliran pristup automobilima. 
