# `RTKVHD64_7.sys`

[Назад до індексу](../README.uk.md) · [English version](RTKVHD64_7.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `77480F6EC6A2D3CEECFF2086138CA5B8C7BB3D3ABA61C8A03331ABF731EF8B16` | `47250D0B326414037BB9CCB76E9B007C00E78312` | `1525CE9413CE8084DAF6563BC2FB4940` |

## Метадані

- **Ім'я файлу:** `RTKVHD64_7.sys`
- **Розмір:** 6185768 bytes
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
