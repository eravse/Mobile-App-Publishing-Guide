---
name: Google-PlayStore-App-Publishing-Skill
description: >
  Google Play Console app publishing skill for Android. Rules, Google Play policy
  rules, data safety, content rating, permissions, app review checklist items, commands
  and templates for mobile app developers and new learners.
---

# Google Play App Publishing Skill

## Purpose

Android uygulamasını Google Play Console (`play.google.com/console`) üzerinden yayınlamadan önce uygulanacak kuralları, policy kurallarını, app review aşamasında karşılaşılabilecek kalemleri, oluşturulacak komutları ve kullanılacak şablonları belirleyen skill.

Hedef kitle: Derinlemesine mobil uygulama yazan yazılımcılar ve yeni başlayan öğrenciler.

## When to use

- Yeni bir Android uygulaması Google Play'de yayınlamaya başlarken.
- Google Play review sürecinden önce hazırlık checklist'i oluşturulmasında.
- Review'dan sonra izinsiz yankı / politika ihlali / teknik ret'e düşüldüğünde.

## Rules & Policy Rules

### 1. Developer Account

- Google Play Developer hesabı: tek seferlik **25 USD** ücret.
- Hesap onaylı, aktif ve **good standing** (geçerli) olmalıdır.

### 2. Privacy & Data Safety

- Kişisel veya hassas veri işleyen uygulamalar için **privacy policy URL'si** zorunludur.
- **Data Safety formu** (Veri Güvenliği formu) eksiksiz ve doğru doldurulmalıdır.
- Toplanan veri tipleri belirtilmelidir: konum, kişisel bilgi, fotoğraf/fil, kamera, mikrofon, not, çağrı kaydı vb.
- Veriler şifrelenmiş (SSL/TLS) şekilde aktarılmalıdır.

### 3. Content & Content Rating

- **İçerik derecelendirmesi** (Content Rating / IARC) doldurulmalıdır.
- Yasaklı içerikler: nefret söylemi, cinsel içerik, şiddet/kan, uygunsuz reklam, kötüye kullanım, vb.
- **Reklam politikası** (Ads Policy) uyumu sağlanmalıdır.

### 4. Permissions

- Kullanılan izinler (permissions) listelenmeli ve gerekli ise açıkça açıklanmalıdır.
- Rekabetçi amaçlı / kısıtlı izinler (SMS, çağrı kaydı, arama kapsamı vb.) Google Play politikelerine tabidir.

### 5. Technical Requirements

- Minimum API level ve hedef API seviyesi uyumlulukları.
- **64-bit** uyumluluğu.
- Yeni uygulamalar için **AAB** (Android App Bundle) formatı.
- Doğru imzalama ve hazırlama süreci.

## App Review Phase Checklist

- [ ] Geliştirici hesabı doğrulandı ve good standing.
- [ ] Gizlilik politikası / KoS URL'leri eklendi.
- [ ] Data Safety formu dolduruldu.
- [ ] İçerik derecelendirmesi tamamlandı.
- [ ] Hedef kitle (target audience) belirlendi.
- [ ] İzinler listelendi ve gerekçelendi.
- [ ] Yasaklı içerik / reklam politikasından sapma yok.
- [ ] Teknik gereksinimler sağlandı (API seviyesi, 64-bit, AAB).
- [ ] Mağaza listing asset'leri hazır (ikon, feature graphic, ekran görüntüleri).
- [ ] Test (internal / closed / open beta) veya rollout planı.

## Commands

- `google-play-publish-checklist` — App review öncesi hazırlık checklist'i üretir.
- `scaffold-google-play-guide` — Google Play rehberi için klasör yapısını (SKILL.md, references, commands, templates) oluşturur.

## Templates

- `templates/google-play-publish-checklist.md`

## Notes

- Policy kuralları zaman zaman güncellenir; mutlaka güncel resmi Google Play policy dokümanlarını takip edin.