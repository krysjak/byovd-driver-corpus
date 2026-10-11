# `bcmwl63a_3.sys`

[Назад до індексу](../README.uk.md) · [English version](bcmwl63a_3.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `8FA00E445D7C5A1C38064B461CBBA047F4E854A43F55E5197DEFDA48AECD01F5` | `2D9FA5CC2613020091D5F9598677147E13156684` | `1D993452E89B23F1D1DFF4ECD7223BCA` |

## Метадані

- **Ім'я файлу:** `bcmwl63a_3.sys`
- **Розмір:** 7515312 bytes
- **Архітектура:** 0x8664
- **Компанія:** Broadcom Corporation
- **Продукт:** Broadcom 802.11 Network Adapter wireless driver
- **Опис:** Broadcom 802.11 Network Adapter wireless driver
- **Підпис:** signed
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 75

## Профіль можливостей

**Primitives:** `physical address resolution`, `physical memory mapping`

**Imports:** `MmGetPhysicalAddress`, `MmMapIoSpace`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
