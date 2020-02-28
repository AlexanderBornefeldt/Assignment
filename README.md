# CEGO-assignment
Assignment til CEGO's jobopslag til stillingen som studenterprogrammør

Min løsning tager udgangspunkt i tabellen "users" fra opgavebeskrivelsens repo og er lavet ved brug af JavaScript, Node.js og MySQL.

Løsningen forbinder JavaScript filen til SQL databasen ved brug af Node.js's SQL modul.

Løsningen tilføjer en primary key til kolonnen "id" for at sikre data integrity og undgå fremtidige data duplikeringer, hvorefter det nuværende data i tabellen tjekkes for duplikeringer.
Herefter henter den samtlige data fra tabellen og gemmer dem i .txt fil kaldet "Output".
Til sidst slettes alt data fra tabellen. Dog eksisterer tabellen stadig, bare tom for data.

Løsningen kan f.eks. testes i command-line ved fra filens directory at skrive: "node CEGO-assignment.js".
