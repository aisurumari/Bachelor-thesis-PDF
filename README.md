# potwierdzenie_odbycia_praktyki_na_podstawie_UoP

Internship acceptance file based on the contract of Frontend Developer with the opinion of the person responsible for my onboarding.

# system_supporting_the_management_of_a_dance_school_MERN_stack

My bachelor thesis PDF file consisting:

• Review of existing solutions on the market

• Description of the tools and technologies used to create the application

• Description of the development environment

• Overview of the system architecture

• Application design divided into functional and non-functional requirements

• Creating an application with separate views for the client, employee and dance school owner.

• User documentation

# Podsumowanie

Celem pracy było zaprojektowanie systemu do zarządzania szkołą nauki tańca. W związku z tym najpierw przeprowadzone zostało badanie ankietowe. Na podstawie wyników ankiety, sformułowane zostały założenia systemu oraz wymagania funkcjonalne i niefunkcjonalne. Następnie opracowany został projekt aplikacji. Według ankietowanych, najważniejsze w takim systemie są: dostępność danych o klientach, widok grafiku/grup zajęć tanecznych, raporty w celu możliwości analizy dotychczasowych strategii zarządzania i marketingu. W celu graficznej reprezentacji systemu wykorzystane zostały diagramy UML, które przedstawiają przypadki użycia, komponenty oraz dwie przykładowe czynności w trakcie korzystania z systemu. 
Na podstawie projektu aplikacji, zaimplementowano wszystkie założone funkcjonalności za pomocą stosu technologicznego MERN do tworzenia aplikacji webowych. Aplikacja została napisana w architekturze client-server, w której system jest podzielony na klienta, czyli interfejs użytkownika, oraz serwer, w którym znajduje się logika biznesowa oraz baza danych. Klient przesyła zapytania do serwera, który udziela odpowiedzi.
Przy pomocy MongoDB powstała baza danych, dzięki której wszystkie dane o klientach i zajęciach grupowych w szkole tańca zostaną zapisane cyfrowo. Przy użyciu framework’a React stworzono cztery wersje aplikacji, w zależności od roli pełnionej w szkole tańca. Poprzez Node.js oraz Express JS utworzono serwer, który pozwala na komunikację ze wszystkimi elementami aplikacji webowej.
Bezpieczeństwo w sieci jest jednym z najważniejszych aspektów, które muszą być brane pod uwagę przy projektowaniu aplikacji internetowych. W dzisiejszych czasach, kiedy przechowywanie danych i przekazywanie ich w sieci staje się coraz bardziej popularne, należy zwrócić szczególną uwagę na ochronę danych, które są przekazywane i pozyskiwane przez użytkowników. Mając na względzie osoby korzystające z aplikacji Leadance, podczas rejestracji i logowania hasła są zaszyfrowane za pomocą biblioteki bcrypt, która zapewnia wysoki poziom bezpieczeństwa. Dzięki temu, w przypadku ewentualnego wycieku danych z aplikacji, hasła użytkowników będą bezpieczne i nie będzie możliwe ich odczytanie.
W kontekście projektu, wykorzystano trzy protokoły: HTTP, SMTP oraz TCP. Pierwszy z nich, czyli HTTP (ang. Hypertext Transfer Protocol) jest wykorzystywany do przesyłania informacji w postaci stron internetowych pomiędzy serwerem a klientem. Protokół ten określa sposób, w jaki informacje są przesyłane, jakie metody są dozwolone oraz w jaki sposób następuje nawiązanie i zakończenie połączenia. Drugim wykorzystanym protokołem jest SMTP (ang. Simple Mail Transfer Protocol), który jest standardowym protokołem internetowym wykorzystywanym do przesyłania poczty elektronicznej. Protokół SMTP określa sposób, w jaki wiadomości e-mail są przekazywane pomiędzy serwerami pocztowymi oraz między klientem poczty a serwerem pocztowym. Trzeci wykorzystany w projekcie protokół to TCP (ang. Transmission Control Protocol). TCP jest protokołem warstwy transportowej, który umożliwia nawiązanie połączenia pomiędzy aplikacjami działającymi na różnych urządzeniach w sieci. Protokół ten jest używany do zapewnienia niezawodnej i poprawnej transmisji danych poprzez dzielenie przesyłanych informacji na mniejsze pakiety i ich numerowanie, a także zapewnianie ich kolejności i potwierdzanie ich odbioru. W projekcie wykorzystano TCP do zapewnienia niezawodnego i bezpiecznego połączenia z bazą danych MongoDB.
Aby ułatwić proces tworzenia aplikacji webowej, wykorzystano łącznie osiem różnych bibliotek. Wśród nich znalazły się m.in. React, który jest popularną biblioteką JavaScript wykorzystywaną do budowania interfejsów użytkownika, oraz React Router, który umożliwia tworzenie dynamicznego routingu w aplikacji webowej. Do komunikacji z serwerem wykorzystano bibliotekę Axios, która pozwala na tworzenie zapytań HTTP w łatwy sposób. Aby ułatwić komunikację z bazą danych MongoDB, wykorzystano bibliotekę mongoose. Do wysyłania maili użyto biblioteki nodemailer. Na rozwiązanie problemów związanych z "CORS" - Cross-Origin Resource Sharing, czyli problemem dostępu do zasobów między różnymi domenami pozwoliła biblioteka cors. Do zabezpieczania haseł wykorzystano bibliotekę bcrypt. Wszystkie wrażliwe informacje takie jak hasła i klucze API przechowywano w pliku konfiguracyjnym .env, a odczyt tych wartości zrealizowano przy pomocy biblioteki dotenv.
Cały projekt składał się z dziewięciu różnych komponentów oraz dziesięciu różnych widoków aplikacji webowej, co pozwoliło na stworzenie intuicyjnego interfejsu użytkownika, który pozwala na łatwe korzystanie z aplikacji i przeglądanie zawartości.
Po stronie wizualnej aplikacji webowej, wybrano nazwę systemu, która nie występuje jako znak towarowy w Urzędzie patentowym - Leadance. Część nazwy „lead” nawiązuje do ważnego elementu w tańcu towarzyskim – prowadzenia. Słowo nawiązuje również do „kierowania” w odniesieniu do zespołu lub pracowników. Natomiast angielskie słowo „dance” jest tłumaczone jako taniec. Dzięki takiej nazwie aplikacji webowej, przedsiębiorca posiadający szkołę tańca wie, że system jest skierowany właśnie dla niego. Następnie na podstawie tej nazwy stworzono logo i ustalono kolorystykę warstwy wizualnej. Jak wskazały badania, kolory wpływają na emocje i zachowania odbiorców[27]. Kolor niebieski odnosi się w psychologii kolorów do zaufania, profesjonalizmu, mądrości i prawdy [28].

# Możliwość rozwoju aplikacji

Aplikacja webowa Leadance ma szerokie perspektywy rozwoju. Przede wszystkim warstwa wizualna jest utworzona w zakresie podstawowym. Mogłaby być ulepszona przy pomocy zaprojektowanych makiet UX. Aplikacja stałaby się wtedy bardziej przyjazna dla użytkownika.
Następną możliwością rozwoju jest wprowadzenie płatności internetowych za zajęcia tańca. Klienci mogliby paroma kliknięciami opłacić swój karnet i mieć te dane na wyciągnięcie ręki w aplikacji. Co więcej, kolejnym krokiem rozwoju mogło by być stworzenie jej odpowiednika w wersji mobilnej dla klientów oraz pracowników i właścicieli szkół tańca. W obecnych czasach, smartfon stał się mniejszą wersją laptopa lub komputera stacjonarnego. Aplikacja mobilna ułatwiłaby dostęp do danych, a rezerwację z telefonu można by zrobić w kilka sekund .
Do zarządzania szkołą tańca potrzebne są profile pracowników recepcji oraz właściciela szkoły. Wiele szkół tańca oferuje także zajęcia indywidualne u swoich instruktorów tańca. Osobny panel dla instruktora byłby przydatny w procesie rozwoju aplikacji. Taki pracownik mógłby otrzymywać opłaty za zajęcia przez płatności internetowe lub wpisywać swoją dostępność godzinową w określonych dniach, aby przyjąć kursantów. Ponadto, system mógłby zostać rozszerzony o system wbudowany i posiadać własne oprogramowanie do kart członkowskich i czytników użytych do ich sczytania. Dzięki nim, obecności nie musiałyby być wpisywane do systemu, a klient sam miałby możliwość zaznaczenia udziału w zajęciach grupowych tańca.
Patrząc na aplikację Leadance z szerokiej perspektywy, ma ona wiele ścieżek i możliwości rozwoju. Nie tylko funkcjonalnych, ale też wizualnych. 

