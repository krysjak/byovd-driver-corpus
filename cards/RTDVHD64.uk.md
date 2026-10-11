# `RTDVHD64.sys`

[Назад до індексу](../README.uk.md) · [English version](RTDVHD64.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `380545E5CACBA42366FCD23CD9984C563EF0634884D16660B9174F4D8A0BAC38` | `6889A132E030894DB5BB72DFEF79FEF3C88635E8` | `428C61AB08A41B95428484BD1CAB32DA` |

## Метадані

- **Ім'я файлу:** `RTDVHD64.sys`
- **Розмір:** 2638808 bytes
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
