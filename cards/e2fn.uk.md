# `e2fn.sys`

[Назад до індексу](../README.uk.md) · [English version](e2fn.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `545B4BAD3CB0A02A4FEAE77480F0447B33F0A3F858DBDDE84C282F77DF898078` | `569346BB5B14A837AAEE4C986E899FF3A7D53207` | `10E353864C680ED0F688666442E3FDC7` |

## Метадані

- **Ім'я файлу:** `e2fn.sys`
- **Розмір:** 1427528 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Intel(R) Ethernet Controller I225
- **Опис:** Intel(R) Ethernet Controller (NetAdapterCx 2.2)
- **Підпис:** signed
- **Джерело:** `oem:hp`
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
