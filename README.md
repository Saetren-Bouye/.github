# Saetren Buøye

### Kompakt modulbasert system for autonom måling og logging av vassøyledata

**Saetren Buøye** er eit lavstraums, kompakt og fleksibelt system utvikla for presis og tilpassbar datainnsamling frå vassøyla.
Systemet er retta mot forsking, miljøovervaking og fiskeoppdrett, der det er behov for stabile og repeterbare målingar over tid.

---

## Formål

Systemet fungerer som ein autonom dataloggar som styrer ei vinsj- og sensorsamling.
Buøya senkar sensoren til definert djupne, utfører målingar etter ein vald profil, og sender data automatisk over 4G eller Wi-Fi.
Etter fullført syklus går systemet tilbake i dvalemodus for å redusere straumforbruk.

---

## Fleksibilitet og konfigurasjon

Systemet gir brukaren høg grad av kontroll over måleoppsettet:

* Fritt val av måledjupne, intervall og sensortypar
* Støtte for både standard- og kundetilpassa sensorprofilar
* Justerbar fordelingsprofil for målepunkt (jamn, tett i toppen, tett i botnen)
* Konfigurasjon via webgrensesnitt eller MQTT
* Støtte for både faste målepunkt og dynamiske mål basert på sensorverdiar

Dette gjer systemet eigna både for enkle dataloggarar og komplekse forskingsoppsett.

---

## Eigenskapar

* Lågstraumsdesign med dvalemodus mellom målingar
* Lokal lagring av data med trygg buffer ved kommunikasjonsbrot
* Automatisk opplasting og synkronisering via MQTT over 4G eller Wi-Fi
* Integrert failsafe og redundans ved overføring
* Kompakt og robust konstruksjon tilpassa feltbruk
* Skalerbar arkitektur med støtte for fleire sensornoder eller integrasjon av fleire bøyestasjonar i same nettverk

---

## Datatilgang og integrasjon

Alle måledata blir logga i strukturert format og kan hentast på fleire måtar:

* Direkte visualisering gjennom tilknytta webgrensesnitt
* Automatisk opplasting til fjernteneste for visualisering og analyse
* Nedlasting eller API-tilgang for integrasjon i eigne verktøy

---

## Bruksområde

Saetren Buøye er utvikla for bruk i:

* **Forskingsprosjekt** innan marin og limnologisk datainnsamling
* **Fiskeoppdrett**, for overvaking av oksygennivå, temperatur, salthald og anna relevant vasskvalitet

Systemet eignar seg særleg godt i situasjonar der kontinuerleg, presis og energieffektiv overvaking er avgjerande.

---

## Teknologisk grunnlag

Systemet er basert på ESP32-plattformen og byggjer på modulær programvare med open arkitektur.
Det nyttar standardiserte grensesnitt (Modbus, MQTT, PPP) og er utvikla med fokus på robustheit, modularitet og energieffektivitet.
Arkitekturen er designa for å kunne utvidast trinnvis, slik at både fleire sensornoder og fleire buøye-stasjonar kan inngå i same distribuerte system.
