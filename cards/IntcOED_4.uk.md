# `IntcOED_4.sys`

[Назад до індексу](../README.uk.md) · [English version](IntcOED_4.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `68509AFB148C081C6695F986C0AA5C82250D8EA242361E5BD8F1412CBA9247BC` | `636AEE3ED89FA260D4F0BB93E35D334B850B1FA7` | `AE800B8AFF888187BF6812DC52DA2E8F` |

## Метадані

- **Ім'я файлу:** `IntcOED_4.sys`
- **Розмір:** 1293240 bytes
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
