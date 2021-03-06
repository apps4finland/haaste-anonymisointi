Inspiraatioksi haasteen ratkaisuun
==================================

1. Voit lähestyä haastetta raja-pintojen kautta. Tällöin haastekysymys voidaan
muotoilla seuraavasti: <br>
_Miten rakennetaan sovellus ja rajapinta johonkin salaiseen potilasdataan (esim.
[AvoHilmoon](http://fi.opasnet.org/fi/AvoHILMO)) siten, että käyttäjä
(esimerkiksi THL:n ulkopuolinen lääkäri tai tutkija) voi kehittää tilastoanalyysin,
joka ajetaan suoraan AvoHilmossa ja
tulokset annetaan käyttäjälle ja/tai julkaistaan netissä, kun ensin on tarkastettu,
ettei salaisia tietoja vuoda tulosten mukana_? Ideana on siis, ettei
data liiku missään vaiheessa THL:n ulkopuolelle, mutta metadata julkaistaan
niin yksityiskohtaisessa muodossa, että sen perusteella on mahdollista
kirjoittaa tilastoanalyysikoodia. Kehitystarpeita on sekä teknisessä
rajapinnassa että tietokäytännöissä. Halusipa haasteen ratkaisuksi haluaa esittää
jotain jo käytössä olevaa valmista rajapintaa (esim. http://www.lisdatacenter.org/data-access/),
tai jotain omaa ratkaisuansa, on suositeltavaa esittää jonkinlaista verifioitavissa
olevaa mittausdataa ratkaisunsa tueksi tai muuten pyrittävä vakuuttaavasti argumentoimaan,
miksi ko. rajapinta soveltuu nimenomaan erityyppisten terveysdatojen analysointiin
ja suojaamiseen. Kilpailutyössä on siis hyvä pohtia toteutusta sekä datan että metadatan
ominaispiirteisiin kantaa ottaen.

2. Voit lähestyä haastetta metatietokuvausten ja generoitujen data-aineistojen
kautta. Tällöin haastekysymys voidaan muotoilla seuraavasti: <br>
_Miten arkaluontoista henkilödataa sisältäviä rekisteri- ja tietoaineistoja
voitaisiin avata ja muuntaa public use -tiedostoiksi niin että yksilöiden
tunnistaminen aineistoista on mahdollisimman hankalaa ja aineistot
mahdollisimman käyttökelpoisia tutkimuksen, päätöksenteon tai palvelutuotannon
näkökulmista_? <br>

Täydellista vastausta kysymykseen 1. tai 2. ei ole olemassa haasteen sisältämien
vaatimusten sisäisen ristiriitaisuuden vuoksi (hyöty vs. tietosuoja). Kilpailutyössäsi voit
halutessasi rajoittua pohtimaan asiaa valitsemastasi tarkemmin rajatusta
näkökulmasta. Alla on esitty esimerkkejä rajoitetummista kysymyksistä, joihin
voit kilpailutyössäsi hakea vastausta [data](https://github.com/apps4finland/haaste-anonymisointi/blob/master/data)-kansiosta löytyvän malliesimerkin
avulla ([esimerkkiaineisto-A](https://github.com/apps4finland/haaste-anonymisointi/blob/master/data/KTL_Sarcoma_study.csv)):

- mikä erilaisista anonymisointitavoista tai niiden yhdistelmistä sopii
parhaiten esimerkkiaineisto-A:n tyyppisen tiedoston sumeuttamiseen
Public Use -tiedostoksi?
Esimerkkiaineisto-A on valmiiksi käsitelty niin, että mittaustulokset eivät
ole todellisia. Haaste on siis ratkaistava tapauksessa, jossa tulokset ovat
todellisia ja potilaspopulaatio tulee maantieteellisesti rajatulta, joka
helpottaa tunnistamista. Katso kohdasta Viitteet tausta-aineistoja.
- millaisia erilaisia tapoja ja tietolähteitä käyttäen voidaan henkilö
välillisesti tunnistaa (jollain todennäköisyydellä) esimerkkiaineisto-A:sta
kun käytettävissäsi on koko internetin tietovarasto?
- osoita, että jokin tai jotkin standardinanonymisointitekniikoista (joita
kuvattu mm. [lähteessä \[2\], Fung et al.](https://github.com/apps4finland/haaste-anonymisointi/blob/master/data/linkkeja.md))
soveltuu erityisen hyvin/huonosti esimerkkiaineisto-A:n
kaltaisille aineistoille. Vaikka esimerkkiaineisto-A:n mittausdata on
kuvitteellista, on siinä pyritty säilyttämään tietoalkioiden väliset korrelaatiot
ja suuruusluokat niin, että anonymisointitekniikoiden tuottamat tilastolliset
tulokset ovat totuudenmukaisia.
- Voit myös käyttää itse keksimääsi esimerkkidataa, jonka kautta haet vastauksia
yllä mainittuihin kysymyksiin!

Rajoitetumpiin kysymyksiin vastatessasi voit myös hyödyntää tietoa
[esimerkkiaineisto-A](https://github.com/apps4finland/haaste-anonymisointi/blob/master/data/KTL_Sarcoma_study.csv):n lukuarvojen, tekstikenttien, ontologisten ym. piirteiden
tilastollisista, suuruusluokka- ym. ominaisuuksista.
