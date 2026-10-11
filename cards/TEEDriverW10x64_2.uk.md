# `TEEDriverW10x64_2.sys`

[Назад до індексу](../README.uk.md) · [English version](TEEDriverW10x64_2.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `947F553D885EEDB7621E9E3ED63DF24387F312CF3113EFAC74A81400F7182D5B` | `739241A537B45B810AC932566DAEFC4CD5CCE800` | `DB79C4B46EC10643EFAB119B95B4F3F2` |

## Метадані

- **Ім'я файлу:** `TEEDriverW10x64_2.sys`
- **Розмір:** 317984 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Intel(R) Management Engine Interface
- **Опис:** Intel(R) Management Engine Interface
- **Підпис:** signed
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 60

## Профіль можливостей

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpace`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
