# `bcmpciedhd63.sys`

[Назад до індексу](../README.uk.md) · [English version](bcmpciedhd63.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `8724A7C3CECB9B1ECB597841823253ED67F6B840F5CA97B761E157808D3E2B3D` | `BC1C2CA68C9F0303AF3FF2B26548276E30FB41F9` | `796B918259C2C8BEEF0FC6ADEC3C0182` |

## Метадані

- **Ім'я файлу:** `bcmpciedhd63.sys`
- **Розмір:** 1037824 bytes
- **Архітектура:** 0x8664
- **Компанія:** Broadcom Corp
- **Продукт:** Broadcom WiFi Driver wireless driver
- **Опис:** Broadcom WiFi Driver wireless driver
- **Підпис:** unsigned
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `physical address resolution`, `physical memory mapping`

**Imports:** `MmGetPhysicalAddress`, `MmMapIoSpace`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
