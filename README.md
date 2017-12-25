# MeOS-Live

Dette er en samling af forskellige løsninger til visning af resultater m.v.
fra orienteringsløb afviklet med løbsprogrammet MeOS.

Ideen er at disse resultater vises på en større skærm på stævnepladsen, således
at startlister og resultatformidling bliver elektronisk.

Overordnet er løsningen baseret på PHP sider placeret på en webserver. Disse sider henter
data i MeOS løbsdatabasen (MySQL) og præsenterer dem i en browser.

Løsningen indeholder følgende features i seneste version:
1   Visning af information fra filen /info/index.html
    Kan f.eks. bruges til at fremhæve oplysninger fra instruktionen
2a  Rullende startlister
    Skærmen opdeles i 2 kolonner, der kan vise forskellige klasse startlister
    Viser:
2b  Rullende resultater - foreløbige
    Resultat baseret på målstempling, der kontrolleres altså ikke for fejlklip. Forudsætter at der er en radiopost på målposten.
    Viser:
2c  Rullende resultater
    Skærmen opdeles i 2 kolonner, der kan vise forskellige klasse resultater
    Viser:
3   Stafet, formelding
    Viser løbere der passerer en given radiopost
4   Divisionsmatch - oversigt
    Skærmen opdeles i 2-3 kolonner hvor der i hver kolonne vises det samlede matchresultat
5   Divisionsmatch - resultat
    Skærmen viser alle resultater fra een match


PRODUKTION/VERSION_105
----------------------
Baseret på afvikling fra XAMPP
Beskrivelse af webserver/MySQL setup i /webserver/readme.txt

Ny INDEX.PHP lavet

Ændrede/tilføjede features:
2a  Rullende startlister
    Disse indeholder nu også et evt. startnummer
2b  Rullende resultater - foreløbige
    Liste, der viser et foreløbigt resultat baseret på målstempling, der kontrolleres altså ikke for fejlklip.
    Listen tænkes brugt når der er lang mellem mål og stævnecenter med aflæsning, det forudsættes at der er en radiopost på målposten.
2c  Rullende resultater
    (tidligere 2b)


PRODUKTION/VERSION_100
----------------------
Første version i GitHub, porteret fra ZIP og Dropbox deling.
Baseret på afvikling på f.eks. USBWebserver

Følgende features findes:
1   Visning af information fra filen /info/index.html
    Kan f.eks. bruges til at fremhæve oplysninger fra instruktionen
2a  Rullende startlister
    Skærmen opdeles i 2 kolonner, der kan vise forskellige klasse startlister
2b  Rullende resultater
    Skærmen opdeles i 2 kolonner, der kan vise forskellige klasse resultater
3   Stafet, formelding
    Viser løbere der passerer en given radiopost
4   Divisionsmatch - oversigt
    Skærmen opdeles i 2-3 kolonner hvor der i hver kolonne vises det samlede matchresultat
5   Divisionsmatch - resultat
    Skærmen viser alle resultater fra een match
