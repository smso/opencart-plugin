<h2>SMSO Opencart 3.x</h2>

<h3>Functionalitati</h3>
<strong>Modulul ofera urmatoarele functionalitati:</strong>

Trimite un SMS catre client in urma urmatoarelor statusuri de comanda:
<ul>
  <li>comanda plasata cu succes</li>
  <li>comanda in procesare</li>
  <li>comanda livrata</li>
  <li>comanda platita</li>
  <li>comanda anulata</li>
  <li>comanda finalizata</li>
  <li>comanda returnata</li>
  <li>comanda procesata</li>
  <li>comanda expirata</li>
  <li>comanda esuata</li>
  <li>comanda refuzata</li>
  <li>comanda completa</li>
</ul>

Pentru fiecare status de mai sus se poate seta un sablon text care poate sa includa urmatoarele variabile:
<ul>
  <li>numar comanda</li>
  <li>numele clientului</li>
  <li>prenumele clientului</li>
  <li>totalul comenzii</li>
  <li>metoda de livrare</li>
  <li>data comenzii.</li>
</ul>

Se pot activa sau dezactiva anumite statusuri.

Dupa ce se seteaza SMSO TOKEN si se salveaza setarile se pot vedea numerele de telefon de pe care se poate trimite SMS-urile si se poate selecta unul dintre ele.

Instalare cat si dezinstalarea modulului este rapida din interfata de admin Opencart.

Interfata de configurare a modului este intuitiva si simpla.


<h3>Instalare</h3>
Modulul se instaleaza cu ajutorul arhivei ZIP prin intermediul adminului in sectiunea Extensii > Installer apoi butonul Upload, se selecteaza apoi arhiva ZIP din PC si apoi se instaleaza.<br/>
Dupa instalare modulul se va regasi in lista de module din Extensii > Extensii > si apoi filtrare la tipul de extensie dupa Module.<br/>
De asemenea din listarea de module din Opencart se poate dezactiva, dezinstala, activa sau configura.


<h3>Configurare</h3>
Pentru activarea modulul va trebui sa intrati in contul aplicatiei SMSO https://app.smso.ro/ de unde veti lua TOKEN-ul pe care il adaugati in campul TOKEN.<br/>
Dupa aceasta va trebui sa salvati, iar daca tokenul este valid vi se vor afisa in campul Sender list, numerele de telefon de pe care puteti sa trimiteti SMS-uri precum si costul fiecaruia.<br/>
Urmatorul pas este sa activati sau sa dezactivati statusurile pentru care se vor trimite SMS-urile si sa modificati textele.<br/>
La final va fi nevoie sa bifati campul Activate pentru a incepe trimiterea de SMS-uri.<br/>
La final se va apasa pe butonul Save pentru a salva toate informatiile.
