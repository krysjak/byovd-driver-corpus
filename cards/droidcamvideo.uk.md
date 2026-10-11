# `droidcamvideo.sys`

[Назад до індексу](../README.uk.md) · [English version](droidcamvideo.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `5772C8D9459A1B05699ED7591EED7A9AEA8D5F4F35B01666D198893B79E0C959` | `953D73C0E89FEAB03D8C98BA6F58BFAC187FA2B7` | `F0357B94DDE14DC16C759AC7EB240CE5` |

## Метадані

- **Ім'я файлу:** `droidcamvideo.sys`
- **Розмір:** 136360 bytes
- **Архітектура:** 0x8664
- **Компанія:** Windows (R) Win 7 DDK provider
- **Продукт:** DroidCam
- **Опис:** Virtual Video Driver
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `MDL allocation`, `page locking`, `section mapping (kernel R/W surface)`, `section object access`

**Imports:** `IoAllocateMdl`, `MmProbeAndLockPages`, `ZwMapViewOfSection`, `ZwOpenSection`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
