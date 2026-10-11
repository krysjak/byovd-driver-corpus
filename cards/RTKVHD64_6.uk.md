# `RTKVHD64_6.sys`

[Назад до індексу](../README.uk.md) · [English version](RTKVHD64_6.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `A4A009E89EF704BAA9FD19EA683FF49906A0A08203A2786A980B7901A22821E3` | `EC2204799F3F830D80682C3AB371829A3BD20F34` | `5F48EEC7BC9AB643701F8EB53CD8DB85` |

## Метадані

- **Ім'я файлу:** `RTKVHD64_6.sys`
- **Розмір:** 6545472 bytes
- **Архітектура:** 0x8664
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
