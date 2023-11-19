A simple message board application with support for subforums. Each subforum is comprised of threads chaining together messages.

Features:
* Ability to create an account, log in and log out
* A front page listing all boards and their recent activity
* Creating a thread
* Replying to a thread
* Editing and deleting messages
* Search
* Admin and moderation tools
* Hidden boards
* User privileges

For details on usage, see **[MANUAL.md](/MANUAL.md)**.  
For details on implementation, see **[db-layout.md](db-layout.md)** and **[todo.md](todo.md)**

---

Kurssimateriaalista kopioitu alkuperäinen:

\- /!\ EI PÄIVITY - LUE ENGLANNIKSI /!\ -

Keskustelusovellus

Sovelluksessa näkyy keskustelualueita, joista jokaisella on tietty aihe. Alueilla on keskusteluketjuja, jotka muodostuvat viesteistä. Jokainen käyttäjä on peruskäyttäjä tai ylläpitäjä.

Sovelluksen ominaisuuksia:

*    Käyttäjä voi kirjautua sisään ja ulos sekä luoda uuden tunnuksen.
*    Käyttäjä näkee sovelluksen etusivulla listan alueista sekä jokaisen alueen ketjujen ja viestien määrän ja viimeksi lähetetyn viestin ajankohdan.
*    Käyttäjä voi luoda alueelle uuden ketjun antamalla ketjun otsikon ja aloitusviestin sisällön.
*    Käyttäjä voi kirjoittaa uuden viestin olemassa olevaan ketjuun.
*    Käyttäjä voi muokata luomansa ketjun otsikkoa sekä lähettämänsä viestin sisältöä. Käyttäjä voi myös poistaa ketjun tai viestin.
*    Käyttäjä voi etsiä kaikki viestit, joiden osana on annettu sana.
*    Ylläpitäjä voi lisätä ja poistaa keskustelualueita.
*    Ylläpitäjä voi luoda salaisen alueen ja määrittää, keillä käyttäjillä on pääsy alueelle.
