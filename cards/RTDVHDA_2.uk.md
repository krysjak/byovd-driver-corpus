# `RTDVHDA_2.sys`

[Назад до індексу](../README.uk.md) · [English version](RTDVHDA_2.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `708551EBC475DECA8A4B0A64D4C2F7ABE70EFB3BF457B29CA206BE7FEDDB57B5` | `DD6325DF7EF9DA6E132B6341D9754CEB655184F3` | `177F3132B8B4CA6B3F021B1B3360DA7A` |

## Метадані

- **Ім'я файлу:** `RTDVHDA_2.sys`
- **Розмір:** 1912024 bytes
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
