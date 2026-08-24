# 🏋️ Gym Tracker – PWA-treeniappi

Geneerinen kuntosalin treeniohjelmaseuranta iPhonelle. Toimii täysin offline-tilassa ja tallentaa tiedot puhelimen muistiin.

---

## 📱 Asennus iPhoneen (2 min)

1. **Avaa Safari** iPhonessa *(ei Chrome tai Firefox!)*
2. Mene appin osoitteeseen: **https://joel-korpela.github.io/gym-app-generic/**
3. Paina **Jaa-painike** (neliö, jossa ylöspäin osoittava nuoli) ↑
4. Selaa alaspäin ja valitse **"Lisää Koti-valikkoon"**
5. Paina **"Lisää"** oikeassa yläkulmassa
6. Valmis! 🎉 Appsi näkyy nyt kotinäytöllä kuin mikä tahansa appi.

---

## ✅ Ominaisuudet

- ⚙️ **Täysin mukautettava treeniohjelma** – valitse haluamasi liikkeet kirjastosta
- 📋 **A/B-suunnitelmat** – tallenna kaksi eri treenipohjaa ja vaihda niiden välillä
- ✅ Rastita sarjat tehdyksi
- 📊 Kirjaa paino (kg) ja toistot jokaiselle sarjalle
- ⏱️ Automaattinen palautusajastin sarjojen väliin (per liike konfiguroitu)
- 🔔 Ajastin hälyttää ääni + värinällä kun palautus on ohi
- 📅 Treenihistoria päivämäärän kera
- 📈 Edellisen treenin painot näkyvät viitteenä per liike
- 💪 Treenattavat lihakset näkyvät jokaisella liikekortilla
- ☁️ iCloud-varmuuskopiointi (lataa/palauta JSON-tiedosto)
- 💾 Kaikki data tallennetaan vain omalle puhelimellesi (localStorage)
- 🌐 Toimii täysin offline-tilassa – ei vaadi internetiä

---

## ⚙️ Liikkeet ja suunnitelmat

Avaa **⚙️ Liikkeet** -välilehti appissa ja:

1. Valitse haluamasi liikkeet saatavilla olevasta kirjastosta
2. Tallenna valinta **Suunnitelma A**:ksi tai **Suunnitelma B**:ksi
3. Vaihda aktiivista suunnitelmaa milloin tahansa treenin aikana

Saatavilla olevia liikkeitä ovat mm. kyykky, penkkipunnerrus, leuanveto, pystypunnerrus, hauiskääntö, maastaveto, kulmasoutu ja monet muut.

---

## ☁️ iCloud-varmuuskopiointi

1. Avaa **☁️ iCloud** -välilehti appissa
2. Paina **"Tallenna iCloudiin"** – JSON-tiedosto latautuu puhelimeesi
3. Tallenna tiedosto **iCloudin Tiedostot-appiin**
4. Tiedosto synkronoituu automaattisesti iCloudiin ✅

Voit palauttaa datan milloin tahansa "Palauta varmuuskopiosta" -napilla.

> ⚠️ **Tärkeää:** Ota varmuuskopio ennen puhelimen vaihtoa tai Safarin välimuistin tyhjennystä!

---

## 🌐 GitHub Pages -käyttöönotto (kertaluonteinen)

Jotta appin osoite toimii, GitHub Pages täytyy ottaa käyttöön repositoriossa:

1. Mene repositorioon GitHubissa
2. Avaa **Settings** (yläpalkin oikea reuna)
3. Selaa vasemmasta valikosta kohtaan **Pages**
4. Valitse **Source**: `Deploy from a branch`
5. Valitse **Branch**: `main` ja hakemistoksi `/ (root)`
6. Paina **Save**
7. Odota noin minuutti – sivu on sitten saatavilla osoitteessa **https://joel-korpela.github.io/gym-app-generic/**

---

## 🛠️ Tekniset tiedot

- Yksittäinen `index.html`-tiedosto – ei ulkoisia riippuvuuksia
- Kaikki koodi inline (HTML + CSS + JavaScript)
- Tiedot tallennetaan `localStorage`-muistiin
- PWA-metatagit iOS-kotinäyttöasennusta varten
- Tumma teema, optimoitu iPhonen näytölle
