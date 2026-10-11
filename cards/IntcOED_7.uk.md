# `IntcOED_7.sys`

[Назад до індексу](../README.uk.md) · [English version](IntcOED_7.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `ACABB510C4DE938B0D58970F3CCEC8B221100B31766480C29892253C5E7F5A1F` | `15C1F13176101DD8CEA21F90207D6F1C09CF8D6A` | `C7D6DDA8589923515D56B46DF83DFD1D` |

## Метадані

- **Ім'я файлу:** `IntcOED_7.sys`
- **Розмір:** 1289168 bytes
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
