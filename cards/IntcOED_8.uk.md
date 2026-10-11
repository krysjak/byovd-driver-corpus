# `IntcOED_8.sys`

[Назад до індексу](../README.uk.md) · [English version](IntcOED_8.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `B88FE5095A68418DA9A1E13A22D47948CA8AB6267CFA86ECB41C20994B40BC65` | `14101FB311E18798DD18CAB0969993159045B1E6` | `E5EAED72095799AE2975C82CFEC15B5F` |

## Метадані

- **Ім'я файлу:** `IntcOED_8.sys`
- **Розмір:** 1279472 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel(R) Corporation
- **Продукт:** Intel(R) Smart Sound Technology OED
- **Опис:** Intel(R) Smart Sound Technology OED
- **Підпис:** signed
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 75

## Профіль можливостей

**Primitives:** `physical address resolution`, `physical memory mapping`

**Imports:** `MmGetPhysicalAddress`, `MmMapIoSpaceEx`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
