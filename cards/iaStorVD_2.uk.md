# `iaStorVD_2.sys`

[Назад до індексу](../README.uk.md) · [English version](iaStorVD_2.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `C5DA1D9C368B757DB3E2A318CC928CF287DE32D94A1BD4F7A93058FBC18DA906` | `9F8FC3D825DDC70A52C6C481A3825CACE708E618` | `2C2232F7E03AE788A43D7940B8FEE5F0` |

## Метадані

- **Ім'я файлу:** `iaStorVD_2.sys`
- **Розмір:** 1547464 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Intel(R) Rapid Storage Technology driver 
- **Опис:** Intel(R) Rapid Storage Technology driver - x64
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
