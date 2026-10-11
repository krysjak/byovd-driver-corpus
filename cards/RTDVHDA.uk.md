# `RTDVHDA.sys`

[Назад до індексу](../README.uk.md) · [English version](RTDVHDA.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `A5D47AF544402B3FDDF6A851805A6A630ABDAF0D3FF7F3A5D706365E0FBB3901` | `8772C5496CB1E94CD54A2DFB67ECE8A17C179FC2` | `8A2FB0F3A851CF12626A23B98EBDEAFB` |

## Метадані

- **Ім'я файлу:** `RTDVHDA.sys`
- **Розмір:** 2004504 bytes
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
