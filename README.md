# CleverAPI
API endpoints til Clever mobil app

Uofficielt API til Clever mobil app
Jeg tager ikke ansvar for funktioner

Indsæt data i den medfølgende enviroment fil
email = din email til Clever login
secretCode = 
1. Log ud af Clever app
2. Tryk på login og indtast din e-mail adresse
3. Du modtager en e-mail fra Clever
4. Fra en computer tryk på 'Bekræft'
5. Der åbner et link med teksten:
> https://clever.dk/finishSignUp?secretCode=EAA....
6. Kopier alt EFTER =-tegnet og indsæt i env filen

Start med at udføre alle HTTP request i 'Authorization mappen' i rækkefølgen 'Step 1', 'Step 2', 'Step 3'

Udfør 'Get charger id' i mappen 'Set variables for charger'

Nu kan du udføre commands i mappen 'API endpoints'

Når du først har gennemgået Authorization én gang behøver du ikke at gøre det igen.

Har du endpoints der mangler så skriv endelig, så vi kan få dem tilføjet.

Happy Coding!
