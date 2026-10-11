# `iaStorAC_6.sys`

[Назад до індексу](../README.uk.md) · [English version](iaStorAC_6.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `8E18016F08C3CB87E2C9DBFA40B1B9E9FA35ED692A172A1208F334129DFEBBAD` | `1E7C19CADD64C1EBFF31C6E906269719C5B7BF37` | `18763231FF358B20084E95F0F22EBC08` |

## Метадані

- **Ім'я файлу:** `iaStorAC_6.sys`
- **Розмір:** 1036288 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Intel(R) Rapid Storage Technology driver 
- **Опис:** Intel(R) Rapid Storage Technology driver - x64
- **Підпис:** signed
- **Джерело:** `oem:hp`
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
