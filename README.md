# MIPS_projekat

"Stefan Erić" enkodira se kao niz impulsa i pauza koristeći sledeće parametre:

Ime i prezime ima ukupno 6 suglasnika (4 + 2) i 4 samoglasnika, što čini oznaku "port B".
Ukupan broj slova u imenu i prezimenu je 10. PIN se izračunava kao ostatak pri deljenju sa 6, što daje PIN 4 (PB4).
Širina impulsa tokom ponavljanja ciklusa za ime iznosi 6 ms, dok širina pauze iznosi 4 ms.
Nakon 6 ponavljanja ciklusa za ime, prelazimo na prezime, gde se širina impulsa smanjuje na 4 ms, a pauza se povećava na 6 ms.
Ovaj novi raspored impulsa i pauza ostaje nepromenjen tokom 4 ponavljanja ciklusa za prezime.
U konačnom rezultatu, "Stefan Erić" generiše niz impulsa i pauza koji odražava kombinaciju suglasnika i samoglasnika, PIN oznaku, kao i promene u trajanju impulsa i pauza tokom ponavljanja ciklusa za ime i prezime.
