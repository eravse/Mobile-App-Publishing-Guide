---
description: Google Play app publish readiness checklist generator
---

# Command: Google Play Publish Checklist

## Purpose

Android uygulamasının Google Play review sürecine girmeden önce hazırlık checklistini üretir.

## Inputs

- Uygulamanın kategori (category).
- Toplanan veri tipleri (data types collected).
- Kullanılan izinler (permissions used).
- İçerik türü / reklam kullanımı (ads usage).

## Outputs

- App review öncesi hazırlık checklisti (markdown).

## Steps

1. `SKILL.md` içindeki `App Review Phase Checklist` maddelerini al.
2. Kullanıcıdan gelen app bilgilerini checklist'e işle.
3. Eksik / tam olmayan maddeleri çıktı olarak ver.

## Example

```
Command: google-play-publish-checklist
Inputs: navigation, location, personal data; permissions: location, camera
Output: App review readiness checklist
```