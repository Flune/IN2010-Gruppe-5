# Uke 1 - Big O notasjon og Binærsøk :)

Denne uka gikk vi gjennom O notasjon og Binærsøk! Gjerne gå ukas [slides](https://github.com/amaduswaray/IN2010-Gruppe-6/blob/main/Uke%2001/IN2010%20Uke%201.pdf) 🤩

### Algoruthms of the week
* Biærsøk

#### Viktige Datastrukturer
* Stack
* Set
* Map
* (Optional) Lenke-liste


#### O-Notasjon(Big O)

Q: Hvor mange steg trenger man for å løse en algoritme? In worst case.

#### *Lifehack regler*
* Når det er ledd mellom plusstegn, så kan man ta hensyn til det leddet som vokser raskest:
  * Eksempel: O(n^3 + n^2 + n) = O(n^3) fordi n^3 vokser raskest når n øker :)
 

* Konstanter og koffesienter kan man se bort ifra, eller redusere ned til 1
  * Eksempel 1: O(50n) = O(1n) = O(n)
  * Eksempel 2: O(1000) = O(1)

* Variabler kan ganges sammen for å gjøre det enklere å se hva som vokser raskest
  * Eksempel: O( (n+15)*(n+20) ) = O(n^2 + 20n + 15n + 15*20) = O(n^2) ettersom at n^2 vokser raskest
  * Dette eksempelet kan også løses ved å se bort fra konstantene, ettersom at n vokser raskest i begge parantesene. Da ser løsningen slik ut:
    * O( (n+15) * (n+20) )= O(n * n) = O(n^2)


#### *Formulering*
* Konstant tid = O(1)
* Lineær tid = O(n)
* Logaritmisk tid = O(log(n))
* Lineærlogaritmisk tid = O(nlog(n))
* Kvadratisk tid = O(n^2)

Når man jobber flere inputs og inputsstørrelser som er uavhengig av hverandre, så får man flere variabler som m og n. Da kan man representere kjøretidskompleksiteten med hensyn til disse variablene
* Eskempel: O(m + n) og O(m * n)
* OBS! På oppgaver vil man ofte oppgi svar men kun én variabel, så ved bruk av Lifehack reglene så kan man komme i mål ;)

# Ukes og Gruppe Oppgaver:

### Big O

Simplifiser Big O ligningene:
* O(n^3 + 50n^2 + 10000) 
* O((n + 30) * (n + 5))
* O( n*log(n) + log(n)*log(n))
* O(n + n + n + n + n + n) 


###### Big O på kode

Prøv deg på disse enkle oppgave!

<img width="479" alt="Screen Shot 2022-08-31 at 2 16 42 PM" src="https://user-images.githubusercontent.com/86655546/187676321-980ac50c-4fff-478b-a451-4a73dccc9e71.png">


* [Begynner](https://github.com/sergiosja/IN2010-Gruppe-6/blob/main/Uke%2001/Big%20O/bigo_easy.py)
* [Intermedite](https://github.com/sergiosja/IN2010-Gruppe-6/blob/main/Uke%2001/Big%20O/bigo_intermediate.py)



