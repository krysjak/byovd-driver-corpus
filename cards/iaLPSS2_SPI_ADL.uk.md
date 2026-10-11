# `iaLPSS2_SPI_ADL.sys`

[Назад до індексу](../README.uk.md) · [English version](iaLPSS2_SPI_ADL.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `93286B86DB6CCAB700C950FDCE1E30A597440C9CA017E0CBD053AD7789BC774D` | `B7DB16A79F41BC8F132502579586CC52B7440C01` | `26D25F8D8FDEF64E20AC9E3101C6C88C` |

## Метадані

- **Ім'я файлу:** `iaLPSS2_SPI_ADL.sys`
- **Розмір:** 171608 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Intel(R) Serial IO Driver
- **Опис:** Intel(R) Serial IO SPI Driver v2
- **Підпис:** signed
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 60

## Профіль можливостей

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpaceEx`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
