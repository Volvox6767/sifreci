# sifreci 🔐🎲

**EN | Strong password generator — runs in your browser, crypto-random, nothing ever sent.**
**TR | Güçlü şifre üretici — tarayıcında çalışır, kriptografik rastgelelik, hiçbir yere gitmez.**

**▶ Open / Aç:** **https://volvox6767.github.io/sifreci/**

Online password generators have one dirty secret: you can't be sure the
password isn't logged. **sifreci is one HTML file** — the password is created
*inside your browser* with `crypto.getRandomValues()` (cryptographic
randomness) and never leaves the screen. Turn off your internet and try it.

Online şifre üreticilerin kirli sırrı var: şifrenin kaydedilmediğinden emin
olamazsın. **sifreci tek HTML dosyasıdır** — şifre `crypto.getRandomValues()`
ile (kriptografik rastgelelik) *tarayıcının içinde* üretilir ve ekrandan hiç
çıkmaz. İnternetini kapatıp deneyebilirsin.

---

## 🇬🇧 English

### Features

- Length 8–64, pick your character sets (ABC / abc / 123 / symbols)
- **Confusable characters removed** (no `I l 1 O 0 o`) — you can read your password out loud
- Live strength meter with real entropy in bits
- One-click copy, one-click regenerate
- Zero network requests after first load — verifiable in DevTools → Network

### How strong is it?

Entropy = length × log₂(character pool). At the default 20 characters with all
sets enabled: **~126 bits** — more than enough for anything personal. 64
characters reaches ~380 bits.

### Install (optional)

```bash
curl -LO https://raw.githubusercontent.com/Volvox6767/sifreci/main/index.html
```

Double-click the file. Works offline forever.

### FAQ

**Is it safe to trust a random web page with passwords?** This one never
transmits anything — but don't take my word for it: the whole app is one file,
read the source. That's the point.

**Why isn't `I`, `O`, `0`, `l`, `1` in the sets?** They get confused when you
type passwords by hand. Removed on purpose.

**Is this a password manager?** No — it only *generates*. Store results in
your password manager of choice.

---

## 🇹🇷 Türkçe

### Özellikler

- 8–64 uzunluk, karakter seti seçimi (ABC / abc / 123 / semboller)
- **Karıştırılan karakterler çıkarıldı** (`I l 1 O 0 o` yok) — şifreyi yüksek sesle okuyabilirsin
- Gerçek entropi (bit) ile canlı güç göstergesi
- Tek tıkla kopyala, tek tıkla yenile
- İlk yüklemeden sonra sıfır ağ isteği — DevTools → Network'ten doğrulanır

### Ne kadar güçlü?

Entropi = uzunluk × log₂(karakter havuzu). Varsayılan 20 karakter, tüm setler
açıkken: **~126 bit** — kişisel kullanım için fazlasıyla yeterli. 64 karakter
~380 bit'e ulaşır.

### Kurulum (isteğe bağlı)

```bash
curl -LO https://raw.githubusercontent.com/Volvox6767/sifreci/main/index.html
```

Dosyaya çift tıkla. Sonsuza kadar çevrimdışı çalışır.

### SSS

**Rastgele bir web sayfasına şifremi emanet etmek güvenli mi?** Bu hiçbir şey
iletmiyor — ama benim sözüme güvenme: uygulamanın tamamı tek dosya, kaynağı
oku. Amaç bu.

**`I`, `O`, `0`, `l`, `1` neden setlerde yok?** Elle şifre yazarken
karıştırılıyor. Bilinçli olarak çıkarıldı.

**Bu bir parola yöneticisi mi?** Hayır — sadece *üretir*. Sonuçları
kullandığın şifre yöneticisinde sakla.

---

Made with ❤ by **Ahmet Gedik** — [instagram.com/ahmetgedik67](https://www.instagram.com/ahmetgedik67)
Follow on Instagram for more free everyday tools.
Daha fazla ücretsiz günlük araç için Instagram'da takip edin.

License / Lisans: [MIT](LICENSE)
