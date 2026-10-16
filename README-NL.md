# Activiteitenkiezer — gratis webapp voor iPhone

Dit is een complete eerste versie van je activiteitenkiezer. De bestanden zijn bedoeld om gratis te hosten als website en daarna als icoon aan het beginscherm van je iPhone toe te voegen.

## Functies
- Categorieën selecteren om de loting te filteren.
- Activiteiten toevoegen, bewerken en verwijderen.
- Meerdere categorieën per activiteit.
- Categorieën aanmaken, hernoemen en verwijderen.
- Direct dezelfde activiteit opnieuw kiezen wordt vermeden zolang er alternatieven zijn.
- Gegevens lokaal opslaan in de browser.
- Offline ondersteuning na het eerste bezoek, mits de service worker succesvol is geïnstalleerd.

## Gratis online zetten via GitHub Pages
Je hebt een gratis GitHub-account nodig.

1. Ga op je computer naar https://github.com en maak gratis een account of log in.
2. Maak een nieuwe repository, bijvoorbeeld `activiteitenkiezer`. Kies **Public**.
3. Upload de vier bestanden uit deze map (`index.html`, `manifest.webmanifest`, `sw.js`, `icon.svg`) naar de hoofdmap van de repository.
4. Open in GitHub de repository **Settings → Pages**.
5. Bij **Build and deployment** kies je **Deploy from a branch**.
6. Kies branch `main` en map `/ (root)`, en klik op **Save**.
7. Wacht even tot GitHub een website-link toont in hetzelfde Pages-scherm. Die link kan er ongeveer zo uitzien: `https://jouwgebruikersnaam.github.io/activiteitenkiezer/`. Gebruik alleen de link die GitHub zelf toont.

## Op je iPhone zetten
1. Open de website-link in **Safari** op je iPhone (niet in een ingebouwde browser van een andere app).
2. Tik op de knop **Deel** (vierkantje met pijl omhoog).
3. Kies **Zet op beginscherm**. Als je deze optie niet meteen ziet, scroll in het deelmenu omlaag.
4. Laat **Open als webapp** ingeschakeld als die optie verschijnt en tik op **Voeg toe**.
5. Open het nieuwe icoon op je beginscherm.

## Opslag en privacy
- Activiteiten worden bewaard in de lokale browseropslag van dit apparaat.
- Er is geen account of database nodig voor de app zelf.
- Verwijder je de websitegegevens of gebruik je een andere browser/een ander toestel, dan staan je activiteiten daar niet automatisch.
- Omdat dit een eerste versie is, is er nog geen export/back-upfunctie. Bewaar je belangrijke gegevens eventueel apart.

## Aanpassen
Bewerk `index.html` om tekst, kleuren of functies te veranderen. Na een wijziging upload je het bestand opnieuw naar GitHub; soms moet je de website op iPhone even verversen of opnieuw openen.
