---
name: Apple-App-Store-Publishing-Skill
description: >
  Apple App Store app publishing skill for iOS. Rules, App Store policy rules,
  privacy nutrition, encryption, content rating, in-app purchase, app review
  checklist items, commands and templates for mobile app developers and new learners.
---

# Apple App Store Publishing Skill

## Purpose

iOS uygulamasını App Store Connect üzerinden yayınlamadan önce uygulanacak kuralları, App Store policy kurallarını, app review aşamasında karşılaşılabilecek kalemleri, oluşturulacak komutları ve kullanılacak şablonları belirleyen skill.

Hedef kitle: Derinlemesine mobil uygulama yazan yazılımcılar ve yeni başlayan öğrenciler.

## When to use

- Yeni bir iOS uygulaması App Store'de yayınlamaya başlarken.
- App Store review sürecinden önce hazırlık checklist'i oluşturulmasında.
- Review'dan sonra izinsiz yankı / politika ihlali / teknik ret'e düşüldüğünde.

## Rules & Policy Rules

### 1. Developer Account

- Apple Developer Programı üyeliği (Apple Developer Program / Apple Developer account).
- App Store Connect erişimi ve TestFlight kullanımı.

### 2. Privacy & Privacy Nutrition

- **Privacy Policy** URL'si gerekliliği.
- **App Privacy** (Privacy Nutrition) etiketi / veri toplama beyanları.
- Toplanan veri tipleri: konum, kişisel bilgi, fotoğraf/fil, kamera, mikrofon, contacts, purchases, kullanım verileri vb.

### 3. Content & Content Rating

- **Content Rating** sorusu (IARC / Apple rating).
- Yasaklı içerikler: nefret söylemi, cinsel içerik, şiddet, kötüye kullanım, vb.

### 4. In-App Purchase & Subscription

- IAP kuralları: StoreKit, subscription süreleri, refund politikası, developer payout.

### 5. Encryption & Export Compliance

- Uygulamanın kullanılan şifreleme (HTTPS / standard encryption vs. exempt).
- Export compliance (CTS / encryption export compliance) beyanı.

### 6. Technical Requirements

- Xcode sürümü, iOS minimum sürüm (minimum OS version).
- App icon, screenshot, build ayarları.

## App Review Phase Checklist

- [ ] Apple Developer hesabı doğrulandı / üye.
- [ ] App Store Connect hesabı ve TestFlight hazır.
- [ ] Privacy Policy URL'si eklendi.
- [ ] App Privacy (Privacy Nutrition) dolduruldu.
- [ ] İçerik derecelendirmesi tamamlandı.
- [ ] IAP / subscription kurallarına uygunluk.
- [ ] Encryption / export compliance beyanı.
- [ ] Teknik gereksinimler (Xcode / iOS version) sağlandı.
- [ ] Mağaza listing asset'leri hazır (icon, screenshot).
- [ ] Test / rollout planı.

## Commands

- `app-store-publish-checklist` — App Store review öncesi hazırlık checklist'i üretir.
- `scaffold-app-store-guide` — App Store rehberi için klasör yapısını oluşturur.

## Templates

- `templates/app-store-publish-checklist.md`

## Notes

- Policy kuralları zaman zaman güncellenir; mutlaka güncel resmi App Store review guidelines / Apple dokümanlarını takip edin.