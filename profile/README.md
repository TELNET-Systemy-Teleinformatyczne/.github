## Konwencje 

### Nazwy repozytorium

Format kebab-case, małe litery, język angielski: `nazwa-firmy-nazwa-projektu` np. `telnet-project`. 

W przypadku rozdzielenia na serwer i klienta dopisać `server` lub `client` na końcu nazwy np. `telnet-project-server` oraz `telnet-project-client`.

### Tworzenie repozytorium

Zasada: jedno repozytorium, jedno .NET solution.

Do .NET solution dodajemy projekty które współdzielą środowisko, np. działają na tej samej wersji serwera COMARCH ERP XL, np. dodatki Hydry i programy korzystające z jego API.

