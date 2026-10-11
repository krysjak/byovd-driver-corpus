# `iaStorA_2.sys`

[Назад до індексу](../README.uk.md) · [English version](iaStorA_2.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `520399E73B9F6460378768CE75976F91CE024A6111C7238A5D1D6E154532F60F` | `AAF874B6F4A72677ACFA5A515BA60F6E7217FF8D` | `6C76ED95D0572FB0BD0FA7C55F5930F2` |

## Метадані

- **Ім'я файлу:** `iaStorA_2.sys`
- **Розмір:** 1992192 bytes
- **Архітектура:** 0x14c
- **Компанія:** Intel Corporation
- **Продукт:** Intel(R) Rapid Storage Technology driver 
- **Опис:** Intel(R) Rapid Storage Technology driver - x86
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
