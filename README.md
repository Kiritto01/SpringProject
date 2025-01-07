# Spring Web Application - Hello Vistula

Aplikacja **Hello Vistula** to prosty projekt oparty na frameworku Spring, który umożliwia użytkownikowi interakcję z dwoma stronami internetowymi. Projekt demonstruje podstawy korzystania z Springa oraz integrację z Thymeleaf jako silnikiem szablonów. Aplikacja oferuje możliwość wyświetlenia powitania oraz personalizacji wiadomości na podstawie wprowadzonego imienia.

---

## Funkcjonalności

### Strona główna ("/")
Na stronie głównej użytkownik znajdzie prostą wiadomość powitalną:

**"Hello Vistula, in my first Spring controller!"**

### Strona powitalna ("/greeting")
Druga strona umożliwia użytkownikowi podanie swojego imienia poprzez parametr w URL, na przykład:

`http://localhost:8080/greeting?name=Anna`

Aplikacja odpowie spersonalizowanym powitaniem:

**"Hello, Anna!"**

W przypadku braku podania imienia, aplikacja wyświetli domyślną wiadomość:

**"Hello, World!"**

### Obrazek
Strona powitalna zawiera również obrazek, który jest ładowany z zewnętrznego źródła:


---

## Technologie

- **Spring Boot** – główny framework wykorzystywany do tworzenia aplikacji backendowej.
- **Thymeleaf** – silnik szablonów HTML służący do generowania widoków dynamicznych.
- **Java** – język programowania odpowiedzialny za logikę aplikacji.
