# 🏋️ Golden Six – PWA-treeniappi

Arnoldin Golden Six -treeniohjelma iPhonelle. Toimii täysin offline-tilassa ja tallentaa tiedot puhelimen muistiin.

---

## 📱 Asennus iPhoneen (2 min)

1. **Avaa Safari** iPhonessa *(ei Chrome tai Firefox!)*
2. Mene appin osoitteeseen: **https://joel-korpela.github.io/golden-six-app/**
3. Paina **Jaa-painike** (neliö, jossa ylöspäin osoittava nuoli) ↑
4. Selaa alaspäin ja valitse **"Lisää Koti-valikkoon"**
5. Paina **"Lisää"** oikeassa yläkulmassa
6. Valmis! 🎉 Appsi näkyy nyt kotinäytöllä kuin mikä tahansa appi.

---

## ✅ Ominaisuudet

- **Arnoldin Golden Six 2020** – fullbody-ohjelma, 3 × viikossa
- Liikkeet 1, 3 ja 5 vaihtuvat **A/B-vuorottelulla** joka treenissä
- **Treeni A:**
  - 1️⃣ Kyykky – 4 × 10 *(pakarat, etureidet)*
  - 2️⃣ Penkkipunnerrus – 3 × 10 *(rinta, ojentaja, olkapäät)*
  - 3️⃣ Leuanveto, leveä myötäote – 3 × max *(selkä, hauis)*
  - 4️⃣ Pystypunnerrus – 3 × 10 + Vipunostot kulmassa 1 × 12 *(olkapäät, takaolkapäät)*
  - 5️⃣ Hauiskääntö – 2 × 10 + myötäote 1 × 10 *(hauis, brachialis)*
  - 6️⃣ Vatsalihasliike – 3 × 15–20
- **Treeni B:**
  - 1️⃣ Suorin jaloin maastaveto – 4 × 10 *(takareidet, pakarat, selkä)*
  - 2️⃣ Penkkipunnerrus – 3 × 10
  - 3️⃣ Kulmasoutu levytangolla – 3 × 10 *(selkä, epäkäs, hauis)*
  - 4️⃣ Pystypunnerrus – 3 × 10 + Vipunostot kulmassa 1 × 12
  - 5️⃣ Ranskalainen punnerrus – 3 × 10 *(ojentajat)*
  - 6️⃣ Vatsalihasliike – 3 × 15–20
- ✅ Rastita sarjat tehdyksi
- 📊 Kirjaa paino (kg) ja toistot jokaiselle sarjalle
- ⏱️ Automaattinen palautusajastin (2 min / 1,5 min liikkeelle 5 / 1 min vatsaliikkeille)
- 🔔 Ajastin hälyttää ääni + värinällä kun palautus on ohi
- 📅 Treenihistoria päivämäärän ja A/B-variantin kera
- 📈 Edellisen treenin painot näkyvät viitteenä per liike
- 💪 Treenattavat lihakset näkyvät jokaisella liikekortilla
- ☁️ iCloud-varmuuskopiointi (lataa/palauta JSON-tiedosto)
- 💾 Kaikki data tallennetaan vain omalle puhelimellesi (localStorage)
- 🌐 Toimii täysin offline-tilassa – ei vaadi internetiä

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
7. Odota noin minuutti – sivu on sitten saatavilla osoitteessa **https://joel-korpela.github.io/golden-six-app/**

---

## 🛠️ Tekniset tiedot

- Yksittäinen `index.html`-tiedosto – ei ulkoisia riippuvuuksia
- Kaikki koodi inline (HTML + CSS + JavaScript)
- Tiedot tallennetaan `localStorage`-muistiin
- PWA-metatagit iOS-kotinäyttöasennusta varten
- Tumma teema, optimoitu iPhonen näytölle
