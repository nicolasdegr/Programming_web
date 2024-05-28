## README

### API - CampingSiteAPI

**Beschrijving:**
De API is een backend-service voor een campingreserveringssysteem. Het biedt endpoints voor het beheren van campings, gebruikers, boekingen en recensies.

**Belangrijkste Endpoints:**

1. **Gebruikersbeheer:**
   - **Registreren:** POST `/user/register`
   - **Inloggen:** POST `/user/login`
   - **Profiel ophalen:** GET `/user/profile`

2. **Campings beheren:**
   - **Alle campings ophalen:** GET `/campground/all`
   - **Camping details ophalen:** GET `/campground/detailByName`
   - **Camping toevoegen (admin):** POST `/campground/admin/add`
   - **Camping bijwerken (admin):** PUT `/campground/admin/update`
   - **Camping verwijderen (admin):** DELETE `/campground/admin/delete`

3. **Boekingen beheren:**
   - **Boeking maken:** POST `/booking/create`
   - **Boekingsdetails ophalen:** GET `/booking/detail`
   - **Boeking annuleren:** DELETE `/booking/cancel`

4. **Recensies beheren:**
   - **Recensie toevoegen:** POST `/review/add`
   - **Alle recensies ophalen:** GET `/admin/reviews`
   - **Recensie verwijderen:** DELETE `/review/delete`

### Vue Applicatie - AdventureBase Booking

**Beschrijving:**
De Vue-applicatie is de frontend-interface voor gebruikers om campings te verkennen, reserveringen te maken en recensies in te dienen. Het biedt ook een beheerdersdashboard voor het beheren van campings en gebruikers.

**Belangrijkste Functionaliteiten:**

1. **Gebruikersfunctionaliteit:**
   - **Registreren:** Gebruikers kunnen zich registreren via het registratieformulier.
   - **Inloggen:** Gebruikers kunnen inloggen om toegang te krijgen tot hun profiel en boekingen.
   - **Campings verkennen:** Gebruikers kunnen alle beschikbare campings bekijken en filteren op locatie, prijs en voorzieningen.
   - **Boekingen beheren:** Gebruikers kunnen nieuwe boekingen maken en bestaande boekingen bekijken.
   - **Recensies indienen:** Gebruikers kunnen recensies indienen voor bezochte campings.

2. **Beheerdersfunctionaliteit:**
   - **Campings beheren:** Beheerders kunnen campings toevoegen, bijwerken en verwijderen.
   - **Gebruikers beheren:** Beheerders kunnen gebruikersinformatie bekijken en beheren.
   - **Recensies beheren:** Beheerders kunnen alle recensies bekijken en indien nodig verwijderen.

**Belangrijkste Pagina's:**

1. **Homepagina:** Overzicht van alle campings.
2. **Registratiepagina:** Formulier voor nieuwe gebruikersregistratie.
3. **Loginpagina:** Formulier voor gebruikerslogin.
4. **Profielpagina:** Gebruikersprofielinformatie en mogelijkheid om gegevens bij te werken.
5. **Boekingspagina:** Mogelijkheid om nieuwe boekingen te maken en bestaande boekingen te bekijken.
6. **Recensiepagina:** Formulier voor het indienen van recensies.
7. **Beheerdersdashboard:** Beheerinterface voor campings, gebruikers en recensies.

**Installatie en Setup:**

1. **API:**
   - Zorg ervoor dat je .NET Core en LiteDB hebt geïnstalleerd.
   - Voer het project uit vanuit de projectmap.

2. **Vue Applicatie:**
   - Zorg ervoor dat je Node.js en Vue CLI hebt geïnstalleerd.
   - Voer de volgende commando's uit in de projectmap:
     ```bash
     npm install
     npm run serve
     ```

**Contactinformatie:**
Voor vragen of ondersteuning, neem contact op met de ontwikkelaar via [email@example.com].
