# BMI #

* Tekijä: Edilberto Fonseca <edilberto.fonseca@outlook.com>.
* Luontipäivä: 11.8.2022
* Lisenssi: [GPL 2.0][1]
* Arviointipäivä: 18.3.2024

## Esittely

Tervetuloa BMI-lisäosaan! Tämä liitännäinen on suunniteltu auttamaan
kehonpainoindeksin (BMI) laskemisessa, joka on kansainvälinen mittari kehon
rasvapitoisuuden arviointiin. Voit helposti laskea BMI:n antamalla pituutesi
ja painosi. Saat lisäksi tuloksistasi luokituksen, jonka avulla ymmärrät
paremmin tilanteesi ja voit ryhtyä tarvittaviin toimenpiteisiin hyvän
terveyden saavuttamiseksi ja ylläpitämiseksi.

Huomautus: BMI:n oikean tulkinnan kannalta on suositeltavaa ottaa huomioon
myös muut tekijät, kuten kehon koostumus, rasvan jakautuminen, ikä,
sukupuoli ja henkilön yleinen terveydentila. Tarkempaa arviota ja
asianmukaista terveyden- ja painonhallintaa varten on aina suositeltavaa
kääntyä terveysalan ammattilaisen, kuten lääkärin tai ravitsemusterapeutin,
puoleen.

## Asennus

Tässä ovat vaiheittaiset ohjeet BMI-lisäosan asentamiseen NVDA:han:

1. Lataa lisäosan asennustiedosto joko lisäosakaupasta tai [BMI:n][2]
   kotisivulta. Huom: Jos lisäosa ladataan lisäosakaupasta, asennus tapahtuu
   automaattisesti. Muussa tapauksessa seuraa alla olevia ohjeita.
2. Paina Enteriä lataamasi lisäosan kohdalla.
3. Suorita asennus seuraamalla ruudulla näkyviä ohjeita.
4. Käynnistä NVDA uudelleen.
5. Avaa Työkalut-valikko painamalla NVDA+N ja varmista, että BMI-lisäosa
   näkyy siellä.

Olet nyt valmis käyttämään BMI-lisäosaa kehonpainoindeksisi laskemiseen
suoraan NVDA:sta. Muista tutustua lisäosan dokumentaatioon saadaksesi
lisätietoja sen käytöstä ja mukauttamisesta tarpeisiisi.

## Asetukset

Lisäosan määrittämiseen ei ole erillisiä ohjeita, sillä sen käyttö on
yksinkertaista.

## Käyttö

Avaa lisäosan käyttöliittymä painamalla Alt+Windows+I tai menemällä
NVDA-valikkoon (NVDA+N), valitsemalla Työkalut ja sieltä "Laske
kehonpainoindeksi". Näytölle avautuu ikkuna, jossa on kaksi kenttää:

1. Pituus, johon syötetään tai valitaan pituus senttimetreinä.
2. Paino, johon syötetään tai valitaan paino kilogrammoina.

Kun kaikki kentät on täytetty, paina Laske-painiketta joko pikanäppäimellä
Alt+A tai painamalla Enter sen kohdalla.

NVDA puhuu laskennan tuloksen. Kohdistus on valmiiksi OK-painikkeen
kohdalla. Enteriä painettaessa kohdistus palaa Pituus-kenttään.

## Pikanäppäimet

### Pääikkuna

* Alt+L: Laskee tuloksen.
* Alt+Y: Tyhjentää annetut tiedot ja siirtää kohdistuksen Pituus-kenttään.
* Alt+S: Sulkee ikkunan. Myös Esc-näppäintä voidaan käyttää.

## Lisenssi

Tämä lisäosa on suojattu GNU [GPL v2][1] -lisenssillä.

## Kiitokset

Erityiskiitokset avustajille Rui Fontes, Noelia ja Dalen, jotka ovat
auttaneet tekemään tämän version mahdolliseksi.

[1]: https://www.gnu.org/licenses/gpl-2.0.html

[2]: https://github.com/EdilbertoFonseca/BMI

[[!tag dev stable]]
