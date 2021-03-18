---
sidebar: auto
---

# PC Modding

## Voorwoord

::: danger DISCLAIMER Door mods te gebruiken, begrijp je dat:

* Je ervaart mogelijk problemen die niet bestaan in de niet aangepaste versie van het spel. 99,9% van de bugs, crashes en achterstand zijn te wijten aan mods.
* Mods worden vrijwel altijd onbruikbaar bij game updates en dat is normaal - wees geduldig en blijf respectvol wanneer dit gebeurt, want de mensen die mods maken zijn vrijwilligers met andere dingen in hun leven naast het maken van mods.
* Beat Games probeert niet met opzet mods niet meer te laten werken. Ze willen enkel aan de code werken en soms maakt dit mods onbruikbaar, maar dit betekent niet dat ze expres mods in de weg zitten.

Val de ontwikkelaars niet aan voor problemen gerelateerd aan het gebruik van mods, en vice versa - mod makers en de spel ontwikkelaars zijn twee aparte groepen. Wees gewoon geen eikel. :::

Beat Saber ondersteund van zichzelf zelfgemaakte nummers, dus als dat alles is wat je wilt heb je geen extra mods nodig! Het is echter een goed idee om `SongCore` te installeren, omdat deze mod de basis functionaliteit van het spel uitbreid door het verbeteren van laadtijden en functionaliteit te bieden aan andere mods zoals een in-game downlodaer voor nummers, een kunstmatige leaderboards, afspeellijsten, enz.

::: warning Deze gids is voor PC modificatie op Windows.   
Als je een Quest hebt, ga dan naar de [Quest Modificatie pagina](/quest-modding.md).  
Als je Linux gebruikt, ga dan naar de [Linux pagina](/modding/linux.md) of [QBeat](https://github.com/geefr/beatsaber-linux-goodies/blob/master/README.md) :::

Als je tegen problemen aanloopt, ga dan naar de [ondersteuning pagina](./support) en probeer de oorzaak van het probleem te identificeren voordat je het vraagt in de Discord server. De kans is groot dat het antwoord dat je zoekt op die pagina staat!

::: warning Ik heb deze video van Elite Eric gekeken, maar ik liep vast / het werkte niet. Waarom? Wij van de BSMG raden **sterk** af video's van Elite Eric te gebruiken. Na het beoordelen van veel van zijn content, vonden wij dat deze te veel incomplete, verkeerde, of compleet onjuiste informatie bevatten. Pogingen om hem te bereiken en deze fouten te herstellen hebben helaas enkel stilte en nieuwe (ook incorrecte) video's opgeleverd.

In plaats daarvan is het beter de geschreven gidsen te volgen die hier op de wiki beschikbaar zijn, of om hulp te vragen in de [BSMG Discord](https://discord.gg/beatsabermods). :::

## Installatieprogramma's

### Mod Assistant
> **OP DIT MOMENT IS DIT DE AANBEVOLEN MOD INSTALLER.**

__**Start het spel op zijn minst 1 keer**** voordat je probeert het spel te modificeren! Dit geldt ook voor het opnieuw installeren van je spel.

Een simpel Beat Saber mod installatie programma vergelijkbaar met mod manager, maar met extra functies zoals het weer verwijderen van mods en het controleren van versies! Download het op [Assistants GitHub](https://github.com/Assistant/ModAssistant/releases/latest)

![Mod Assistant](~@images/beginners-guide/modassistant.png)

## Hoe kom ik aan meer nummers
:: tip De meeste levels in de "Top All", "Rating", "Downloads" of "Plays" sorteerfilters werden gemaakt voordat er goede praktijken voor het maken van levels werden vastgesteld. Probeer levels van tussen eind 2019 en nu te downloaden voor de beste custom levels ervaring. :::

### In-game Downloader
Met de `BeatSaver Downloader` plugin kan je nummers downloaden terwijl je in het spel bent met de `MORE SONGS` menu knop op het `MODS` scherm. Dit haalt nummers rechtstreeks van [BeatSaver](https://beatsaver.com)

### BeatSaver
[BeatSaver](https://beatsaver.com) is de hoofd database van custom levels gemaakt door de community. Veel andere programma's en websites verbeteren de ervaring van het downloaden van custom levels, maar deze website is de plek waar ze opgeslagen worden. Om de nummers te installeren die van de site zijn gedownload, pak deze nummers uit in een map en plaats deze map in `Beat Saber/Beat Saber_Data/CustomLevels`. Je kan ook gebruik maken van de in-game downloader plugin, BeatList, of Mod Assistant's OneClick™ Install functie.

### Beast Saber
[Beast Saber](https://www.bsaber.com) (bsaber.com) is een website die probeert het vinden van fantastische nummers om te spelen veel makkelijker te maken. Het doet dit door de duizenden nummers van BeatSaver te categoriseren en laat je deze sorteren op het genre en vele andere attribuut labels. Ook heeft het een volledig sociale functie waar spelers nummers kunnen bekijken en hierop commentaar kunnen geven. Een van de meest gebruikte functies is de "Curator Recommended" functie waar een team de meeste nummers die elke dag uitkomen spelen en de nummers die het meest opvallen aanbevelen om deze [automatisch in het spel downloaden](https://bsaber.com/beatsync/).

### Apps voor het beheren van je nummers

* [BeatList](https://github.com/Alaanor/beatlist) is een app waarmee je je playlists en nummers kan beheren.

### Afspeellijsten
Je moet de [PlaylistManager](https://github.com/rithik-b/PlaylistManager/releases/latest) mod installeren.

Daarna kan je een van deze twee dingen doen:

* Het `Install playlists` hulpmiddel in het Opties tabblad in Mod Assistant gebruiken.
* Plaats de afspeellijst in `Beat Saber/Playlists`, selecteer het in het spel en klik dan op download all songs.

Je zou in het spel de afspeellijst naast de custom levels albums moeten zien. De mod ondersteunt ook het beheren van afspeellijsten in het spel.

## Installatie Map
_Waar is beat saber geïnstalleerd?_

### Standaard locatie
|        |                                                                                      |
| ------ | ------------------------------------------------------------------------------------ |
| Steam  | `C:\Program Files (x86)\Steam\steamapps\common\Beat Saber\`                  |
| Oculus | `C:\Program Files\Oculus\Software\Software\hyperbolic-magnetism-beat-saber\` |

### Andere locaties
**Als je de installatiemap hebt verplaatst naar een andere schijf, kan het op de onderstaande locatie staan.** Vervang de schijf letter `F` door de schijf waar je spel is op geïnstalleerd.
|        |                                                                       |
| ------ | --------------------------------------------------------------------- |
| Steam  | `F:\SteamLibrary\steamapps\common\Beat Saber\`                 |
| Oculus | `F:\Oculus\Software\Software\hyperbolic-magnetism-beat-saber\` |

## Handmatige installatie
Een mod installatie programma is de aanbevolen manier om mods te installeren. Zie de sectie [hierboven](#installatieprogramma's). Als je het spel al hebt gemod en alleen plugins wil installeren die niet in het installatieprogramma beschikbaar zijn, ga dan direct door naar stap 4.

**Start het spel op zijn minst 1 keer** voordat je probeert het spel te modden! Dit geldt ook voor het opnieuw installeren van je spel.

### BSIPA installeren

1. Download [BSIPA](https://github.com/bsmg/BeatSaber-IPA-Reloaded/releases).
2. Navigeer naar jouw [installatiemap.](#install-folder) En pak de inhoud van de BSIPA zip hierin uit. ![Directory Clean](~@images/beginners-guide/directory-clean.png "Directory Clean") ![Directory Ipa](~@images/beginners-guide/directory-ipa.png "Directory Ipa")
3. Dubbel-klik op IPA.exe om het spel te modificeren. Alle mods in de `Plugins` map worden nu geladen bij het starten van het spel. Als er foutmeldingen zijn, dan heb je waarschijnlijk stap 2 niet correct gevolgd. ![Directory Patched](~@images/beginners-guide/directory-patched.png "Directory Patched")

### Installeer mods

4. Download de mod(s) die je wilt installeren, of het vanaf GitHub is, het [BSMG Discord](https://discord.com/invite/beatsabermods) `#pc-mods` kanaal,  [BeatMods](https://beatmods.com/#/mods) of van andere bronnen. **Zorg ervoor dat je alle afhankelijkheden download die vereist zijn door de mod(s).** ![Directory Plugins](~@images/beginners-guide/directory-plugins.png "Directory Plugins")
5. Sommige mods hebben installatie-instructies, sommige niet. Over het algemeen kun je de inhoud van de zip naar je Beat Saber installatiemap slepen en neerzetten, de bestanden in de zip zouden naar de bijbehorende mappen moeten gaan.

## Het de-installeren van mods
Verwijder de .dll van de `Plugins` map, of klik op de `Uninstall` knop in Mod Assistant.

## Waar kan je verder gaan

* [Grepen en trucks](./grips-and-tricks.md)
* [Nummers maken](/mapping/)
* [Custom Sabers](/models/custom-sabers.md)
* [Custom Avatars](/models/custom-avatars.md)
* [Custom Platforms](/models/custom-platforms.md)
* [Multiplayer instellen](https://bs.assistant.moe/Multiplayer/)
* [Het maken van mods](/modding/)

## Heb je vragen?
Bezoek de hulp kanalen in de [BSMG Discord](https://discord.gg/beatsabermods)!
