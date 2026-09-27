# mobile

LibreUniversity mobil self-servis uygulaması (Android ve iOS).

## Teknoloji

- React Native + Expo, TypeScript
- `platform-api` OpenAPI istemcisi ve `@libre-university/ui` tokenları
- Derleme yerel veya CI üzerinde; kapalı kaynak bulut derleme servislerine zorunlu bağımlılık yok
- Android için F-Droid dağıtımı hedeflenir

## Kapsam

Rol bazlı ana sayfa, ders programı, notlar, duyurular, bildirimler, dijital kampüs kartı ve self-servis başvurular ([MODULES.md](https://github.com/Libre-University/docs/blob/main/MODULES.md) §26).

## Fazlara Göre İşler

| Faz | Bu repoda yapılacaklar |
| --- | --- |
| Faz 0 | Bu repoda iş yok; web arayüzü responsive olarak kullanılır |
| Faz 1 | Bu repoda iş yok |
| Faz 2 | Expo prototipi, OIDC girişi, ders programı ve notlar |
| Faz 3 | Mobil self-servis 1.0: ana sayfa, bildirimler, duyurular, erişilebilirlik, F-Droid dağıtımı |
| Faz 4+ | Dijital kampüs kartı (QR/NFC), self-servis başvurular, çevrimdışı önbellek |

Ayrıntılı ve işaretlenebilir liste: [ROADMAP.md](ROADMAP.md). Fazlar [ana yol haritası](https://github.com/Libre-University/docs/blob/main/ROADMAP.md) ile hizalıdır. Açık işler için `phase:*` etiketlerine bakın.

## Katkı

Katkı rehberi, davranış kuralları ve güvenlik politikası organizasyon genelinde [`.github`](https://github.com/Libre-University/.github) reposundadır. Mimari kararlar [`docs`](https://github.com/Libre-University/docs) reposundaki ADR'lerle alınır.

## Lisans

Lisans kararı [ADR-0002](https://github.com/Libre-University/docs/blob/main/docs/adr/0002-prefer-agpl-3-or-later-license.md) ile kesinleştirilecektir (öneri: AGPL-3.0-or-later).
