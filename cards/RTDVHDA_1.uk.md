# `RTDVHDA_1.sys`

[Назад до індексу](../README.uk.md) · [English version](RTDVHDA_1.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `D75F2F0F836BF89E620B639798A432A4AE095DCE0282571F0F947903401BBF57` | `E15A7E236E1A9C1D367956C5C7863414EA5EA8DD` | `F9913CFCD2AABF6A03CC9C9B3D5C2C31` |

## Метадані

- **Ім'я файлу:** `RTDVHDA_1.sys`
- **Розмір:** 1690456 bytes
- **Архітектура:** 0x14c
- **Компанія:** Realtek Semiconductor Corp.
- **Продукт:** Realtek(r) High Definition Audio Function Driver
- **Опис:** Realtek(r) High Definition Audio Function Driver
- **Підпис:** signed
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 80

## Профіль можливостей

**Primitives:** `MDL allocation`, `page locking`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmMapIoSpace`, `MmProbeAndLockPages`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
