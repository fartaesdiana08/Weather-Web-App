# Weather-Web-App

Site-ul aplicației web: 
https://fartaesdiana08.github.io/

Link prezentare aplicație:
https://youtu.be/6v_2N3el57k


Introducere

Această documentație descrie o aplicație web care afișează vremea curentă într-o anumită locație, folosind două servicii în cloud: OpenWeather API și Google Maps API. Utilizatorii pot căuta o anumită locație și vor primi informații despre vremea curentă în acel loc.
O astfel de aplicație web ar fi utilă pentru persoanele care doresc să afle informații despre condițiile meteorologice dintr-o anumită locație în timp real.
Un API (Application Programming Interface) este un set de reguli și protocoale care permit interacțiunea între diferite aplicații software sau componente ale acestora. API-ul definește modul în care două sau mai multe aplicații pot comunica, schimba date și colabora pentru a realiza o anumită funcționalitate sau obiectiv.
De exemplu, un API poate permite o aplicație web să acceseze datele unui sistem de baze de date, să obțină informații de la un serviciu web sau să comunice cu o altă aplicație software. În general, API-urile sunt proiectate pentru a fi ușor de utilizat, astfel încât dezvoltatorii să poată crea aplicații care se integrează cu alte sisteme sau servicii existente, fără a fi nevoie să dezvolte totul de la zero.

OpenWeather API

OpenWeather API este un serviciu care furnizează date despre condițiile meteorologice curente și prognoze pe termen scurt pentru orice locație de pe glob. Aceste informații includ temperatura actuală, viteza vântului, presiunea atmosferică, umiditatea și condițiile meteorologice precum ploaie, zăpadă sau nori. Acesta furnizează date în timp real și prognoze pe termen scurt și lung pentru diferite aspecte ale vremii, cum ar fi temperatura, viteza vântului, umiditatea, presiunea atmosferică, nivelul precipitațiilor, condițiile de nori, raze UV și multe altele.
OpenWeather API poate fi utilizat pentru o varietate de scopuri, inclusiv dezvoltarea de aplicații pentru a afișa condițiile meteorologice curente și prognozele pe termen scurt, a monitoriza condițiile meteorologice pentru a lua decizii de afaceri, a planifica evenimente în aer liber sau a îmbunătăți siguranța în trafic. Serviciul este disponibil gratuit pentru utilizatorii care doresc să afișeze date meteorologice pentru un număr limitat de locații și cu cereri limitate pe minut, dar sunt disponibile și planuri de plată cu mai multe opțiuni și funcționalități, pentru utilizatorii care au nevoie de un acces extins la date.
OpenWeather API oferă o serie de funcții și metode pentru a permite dezvoltatorilor să obțină datele meteorologice dorite și să le integreze în aplicațiile lor, inclusiv o interfață API RESTful, SDK-uri pentru diferite limbaje de programare și o documentație detaliată. De asemenea, serviciul este ușor de utilizat și este susținut de o comunitate mare de dezvoltatori, astfel încât este ușor de găsit ajutor și resurse pentru a construi aplicații care utilizează OpenWeather API.

Google Maps API

Google Maps API, pe de altă parte, este un serviciu care furnizează informații despre locații specifice și permite utilizatorilor să vizualizeze hărți detaliate și să obțină indicații rutiere și transport public.
Google Maps API este o platformă de programare oferită de Google, care permite dezvoltatorilor să integreze hărți și informații geografice în aplicațiile lor web și mobile. Acesta oferă o serie de funcții și metode pentru a permite dezvoltatorilor să creeze aplicații personalizate bazate pe hărți, care pot fi utilizate într-o varietate de domenii, cum ar fi turismul, navigația, logistică, afaceri și multe altele.
Google Maps API include un set de interfețe de programare a aplicațiilor (API-uri) care permit dezvoltatorilor să acceseze și să afișeze hărți, să adauge adnotări și informații suplimentare, să ofere instrucțiuni de navigare și să integreze informații de locație în aplicațiile lor. API-ul este ușor de utilizat și oferă o varietate de funcționalități și instrumente pentru a crea aplicații personalizate pe baza hărților Google.
Google Maps API este disponibil în mai multe planuri, de la un plan gratuit care oferă un acces limitat la un număr redus de cereri pe zi, până la planuri plătite care permit dezvoltatorilor să acceseze o cantitate mai mare de date și funcționalități avansate.

 
Descriere problema

Problema pe care o rezolvă această aplicație este aceea că utilizatorii pot accesa rapid și ușor informații despre vremea curentă într-o anumită locație, fără a fi nevoie să căute manual aceste informații. De asemenea, aplicația afișează și o hartă a locației căutate, pentru o experiență mai interactivă și intuitivă.

 	În combinarea celor două servicii, aplicația web ar putea afișa condițiile meteorologice actuale pentru o locație specifică, pe baza coordonatelor geografice obținute prin intermediul Google Maps API. De asemenea, utilizatorii ar putea să își introducă manual locația dorită sau să utilizeze funcția de localizare a dispozitivului lor pentru a afla informații despre vremea din zona în care se află.
Astfel, această aplicație web ar putea fi utilă pentru a planifica activități în aer liber, pentru a pregăti echipamentul potrivit pentru condițiile meteorologice sau pur și simplu pentru a afla cum va fi vremea înainte de a pleca de acasă.

	Linkul către repository-ul cu codul sursă: 
https://github.com/fartaesdiana08/Weather-Web-App

Site-ul aplicației web: 
https://fartaesdiana08.github.io/

Link prezentare aplicație:
https://youtu.be/6v_2N3el57k



Pentru publicarea aplicației web, am ales un furnizor de servicii de găzduire web numit GitHub Pages. Acesta permite utilizatorilor să publice site-uri web statice, cum ar fi site-uri personale, proiecte open-source și documentație. Site-urile web sunt publicate prin intermediul unui repository GitHub, care conține toate fișierele necesare pentru a afișa site-ul web, inclusiv fișierul HTML principal, imagini, fișiere CSS și JavaScript.
 

 
Descriere API

API-urile folosite pentru realizarea acestui proiect, atât OpenWeather API, cât și Google Maps API sunt exemple de API-uri de servicii cloud. Acestea sunt API-uri care oferă acces la resurse și funcționalități oferite de servicii cloud, precum stocarea de date, procesarea de informații, autentificarea utilizatorilor sau servicii de analiză a datelor.
API-urile de servicii cloud sunt foarte populare în dezvoltarea de aplicații web și mobile, deoarece acestea oferă dezvoltatorilor o serie de avantaje, cum ar fi scalabilitatea, securitatea, ușurința de utilizare și o serie de servicii pre-construite pe care dezvoltatorii le pot integra în aplicațiile lor. Prin intermediul acestor API-uri, dezvoltatorii pot beneficia de resurse și funcționalități avansate fără a fi necesar să își construiască propriile soluții.

Această aplicație utilizează două API-uri în cloud, pentru a obține informații despre vreme și locație:

•	OpenWeather API: Un API care oferă informații despre vremea curentă și previziuni meteo pentru orice locație de pe glob.

•	Google Maps API: Un API care oferă informații geografice despre locații, inclusiv coordonatele geografice și denumirile străzilor.


Un endpoint este o adresă URL (Uniform Resource Locator) specifică către care poate fi trimisă o cerere prin intermediul unei aplicații sau a unui serviciu web pentru a obține o anumită acțiune sau un set de date. API-ul expune două endpoint-uri:

•	/weather: folosit pentru a obține informații despre vremea curentă pentru o anumită locație, utilizând OpenWeather API.

•	/location: folosit pentru a obține coordonatele geografice ale unei anumite locații, utilizând Google Maps API.


Flux de date

Utilizatorii accesează aplicația web prin intermediul unui browser web. Pe pagina web, utilizatorii pot introduce o locație prin intermediul unui câmp de căutare. După ce utilizatorii introduc o locație și apasă butonul de căutare, aplicația face o solicitare HTTP către OpenWeather API pentru a obține informații despre vremea curentă în acea locație. Apoi, aplicația utilizează Google Maps API pentru a obține coordonatele geografice ale locației introduse și pentru a afișa o hartă a locației respective. Informațiile despre vremea curentă și harta locației sunt afișate pe pagina web.

1.	Exemple de request / response

Aplicația web efectuează un request HTTP GET către API-ul OpenWeatherMap și primește un răspuns în format JSON. Request-ul HTTP GET este trimis prin intermediul metodei $.ajax() din biblioteca jQuery, având următoarele parametri:
•	url: adresa URL a API-ului OpenWeatherMap
•	data: obiectul de date care conține informații suplimentare despre request, inclusiv locația și cheia de autentificare a API-ului
•	type: tipul de request, în acest caz HTTP GET
•	dataType: tipul de date așteptat în răspuns, în acest caz JSON

Răspunsul primit de la API-ul OpenWeatherMap este un obiect JSON care conține informații despre condițiile meteo curente pentru locația specificată. Datele sunt procesate în funcția success() și afișate în pagină prin intermediul elementelor HTML.
În general, request-ul și răspunsul sunt două părți separate ale unui proces de comunicare între client și server, prin intermediul protocolului HTTP. Request-ul este trimis de client la server, cerând anumite informații sau acțiuni, iar serverul răspunde cu datele solicitate sau cu un mesaj de eroare, dacă este cazul.

2.	Metode HTTP

•	GET /weather: folosit pentru a obține informații despre vremea curentă pentru o anumită locație.
•	GET /location: folosit pentru a obține coordonatele geografice ale unei anumite locații.


 
 
Referințe

https://openweathermap.org/api 
https://developers.google.com/maps/documentation/ 
