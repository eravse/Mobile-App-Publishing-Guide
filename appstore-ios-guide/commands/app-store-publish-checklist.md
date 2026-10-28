---
description: App Store app publish readiness checklist generator
---

# Command: App Store Publish Checklist

## Purpose

iOS uygulamasının App Store review sürecine girmeden önce hazırlık checklistini üretir.

## Inputs

- Uygulamanın kategori.
- Toplanan veri tipleri (privacy nutrition).
- IAP / subscription kullanımı.
- Encryption / export compliance durumu.

## Outputs

- App review öncesi hazırlık checklisti (markdown).

## Steps

1. `SKILL.md` içindeki `App Review Phase Checklist` maddelerini al.
2. Kullanıcıdan gelen app bilgilerini checklist'e işle.
3. Eksik / tam olmayan maddeleri çıktı olarak ver.

## Example

```
Command: app-store-publish-checklist
Inputs: health app, location, purchases
Output: App Store readiness checklist
```