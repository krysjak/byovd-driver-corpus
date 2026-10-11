# `TEEDriver_1.sys`

[Назад до індексу](../README.uk.md) · [English version](TEEDriver_1.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `E4B1397A941828CEE7D90D0E7C36360BBA26AE5859A4EE2A1E246F52C3957B63` | `8EEA06323F7A897E1A7976F04FD95B0118C0CA1B` | `87CD837BC89F1ADAEC3EA00B9227B39C` |

## Метадані

- **Ім'я файлу:** `TEEDriver_1.sys`
- **Розмір:** 155424 bytes
- **Архітектура:** 0x14c
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
