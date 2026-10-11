# `iaLPSS2_I2C_ADL.sys`

[Назад до індексу](../README.uk.md) · [English version](iaLPSS2_I2C_ADL.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `5EC0AE9FD89ABD8983C48EFB1E1F9323E26A10B6370D09826D50AD2725C17564` | `6BFD2236551F17708E752998EDE8940A47E2B74C` | `99EC46C839C60F9C0EEEB614B674C96F` |

## Метадані

- **Ім'я файлу:** `iaLPSS2_I2C_ADL.sys`
- **Розмір:** 220224 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Intel(R) Serial IO Driver
- **Опис:** Intel(R) Serial IO I2C Driver v2
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
