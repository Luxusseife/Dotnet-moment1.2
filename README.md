# Moment 1.2 - Skapa webbplats med Blazor WebAssembly
Min lösning på detta moment är en webbplats om äpplen, kallad Äppelriket. 

## Startsidan
Här ses en bild på äpplen. Här renderas min egenskapade komponent _AppleComponent_ som randomiserar och visar en slumpmässig bild från assets-mappen vid sidladdning. 

## Konvertering
Här kan besökaren konvertera olika mått, från meter till fot och km/h till miles/hour. Detta görs genom att man anger mått och vid klick på knappen körs en beräkningsmetod. Detta kan göras då **@bind** används för måtten angivna i inputfältet. 

## JSON 
Här visas "äppelkort" i en lista, hämtade med HTTP-anrop från en intern JSON-fil med olika äppelsorter. En modell har skapats som motsvarar objektstrukturen i äppelarrayen, vilken loopas igenom i en foreach och skrivs ut som enskilda li-element.

_Skapad av Jenny Lind, jeli2308._