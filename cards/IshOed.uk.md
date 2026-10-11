# `IshOed.sys`

[Назад до індексу](../README.uk.md) · [English version](IshOed.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `FE4BB14246D87E2177274F126AD9AD877F6879011301EA97CD258CB5075AC375` | `509E8AC67C61A3749FB4CD6915AD9D83B3A8BB92` | `2D9D3694DFE1A9C76F8C2603EE19D2DD` |

## Метадані

- **Ім'я файлу:** `IshOed.sys`
- **Розмір:** 73808 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel
- **Продукт:** ISS
- **Опис:** Intel(R) Integrated Sensor Solution
- **Підпис:** signed
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 70

## Профіль можливостей

**Primitives:** `MDL allocation`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmMapIoSpace`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
