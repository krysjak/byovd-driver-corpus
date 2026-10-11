# `ipustack.sys`

[Назад до індексу](../README.uk.md) · [English version](ipustack.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `C4A7AB4F7F6838961E15C42F2BF7258E0939C3D2F8EC1CA011127C6B3396EBFC` | `D6B486B2EF667B4F4F6E786FBF0F972C5DF5D6E5` | `E7F13642B653AEFD319EEB6ACB132467` |

## Метадані

- **Ім'я файлу:** `ipustack.sys`
- **Розмір:** 372032 bytes
- **Архітектура:** 0x8664
- **Компанія:** Advanced Micro Devices, Inc
- **Продукт:** AMD IPU Driver
- **Опис:** AMD IPU Driver
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `driver loading`, `physical address resolution`

**Imports:** `MmGetPhysicalAddress`, `ZwLoadDriver`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
