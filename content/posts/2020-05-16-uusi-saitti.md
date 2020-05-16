+++
author = "Kimmo"
cover = ""
date = 2020-05-16T08:00:00Z
description = "Kohti uutta Vammala Party -sivustoa."
title = "Uusi saitti"

+++
Vammala Party -sivusto on muutaman vuoden ollut alhaalla alustaongelmien vuoksi. Tästä syvät pahoittelut allekirjoittaneen puolesta, koska en ole saanut aikaiseksi rakentaa sivustoa uudelleen. Nyt sivusto on rakentumassa uusiksi - ja tavallaan myös palaamassa juurilleen.

## Sivuston aikaisemmat versiot

Vammala Party -sivuston ensimmäiset iteraatiot toimivat kokonaan staattisesti: ne koostuivat läjästä yhteenlinkitettyjä HTML-dokumentteja, joita päivitettiin kokonaan käsin. Staattisten sivustojen hyvinä puolina ovat, että ne voi tarjoilla käytännössä miltä tahansa palvelimelta ongelmitta, eikä niissä ole mitään hakkeroitavaa, joten iso osa tietoturvahuolista katoaa. Ongelmallista tuossa kuitenkin oli se, että sivuston päivittäminen oli työlästä ja erittäin virhealtista.

Sivuston päivittämistä lähdettiin helpottamaan sillä, että sivusto rakennettiin nollasta uusiksi sisällönhallintajärjestelmän päälle. Sisällönhallintajärjestelmäksi valittiin palvelinteknisistä syistä jo tuolloin vanhahko Drupal 6. Järjestelmä palveli tässä käytössä kohtuullisesti, mutta sisällön päivittäminen koettiin edelleen melko hankalaksi.

Lopullisesti homma meni metsään siinä vaiheessa, kun palvelinpäivityksen myötä Drupal 6 lakkasi kokonaan toimimasta palvelimella. Tämä tarkoitti, että sivusto piti rakentaa käytännössä jälleen kokonaan uusiksi.

## Sivuston uusi versio

Sivuston tulevasta teknisestä ratkaisusta keskusteltiin jonkin verran Vammala Partyn Facebook-ryhmässä. Tärkeiksi ominaisuuksiksi sivustolle nostettiin seuraavat:

* Toimintavarmuus
* Tietoturva
* Päivityksen helppous

Tarpeena olisi siis tuottaa sivusto, jota on helppo päivittää ja josta ei varsinaisesti tarvitse kantaa huolta ollenkaan. Toimintavarmuus, tietoturva ja huolettomuus voidaan parhaiten taata tekemällä sivusto staattiseksi, mutta mitenkäs on tuon päivityksen helppouden kanssa?

Nykyaikaisten staattisten sivustogeneraattoreiden kanssa voidaan käyttää useampaakin helppokäyttöistä sisällönhallintajärjestelmää, jotka tekevät staattisen sivuston päivittämisestä helppoa. Tämän Vammala Party -sivuston sisällönhallinta hoituu [Forestryllä](https://forestry.io "Forestry.io"), joka päivittää sisältöä suoraan GitHubissa asustelevaan Git-repositorioon. Kaikki päivitykset ovat siis automaattisesti versiohallittuja ja sivusto voidaan tarvittaessa helposti palauttaa mihin tahansa tilaan koko historiansa ajalta. Sivustogeneraattorina toimii tässä tapauksessa [Hugo](https://gohugo.io "Hugo").

Tämän pitäisi olla erittäin vankka pohja tuottaa Vammala Party -sivustoa, joka ei enää katoa internetistä.