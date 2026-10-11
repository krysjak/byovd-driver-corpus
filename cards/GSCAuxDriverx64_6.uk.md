# `GSCAuxDriverx64_6.sys`

[Назад до індексу](../README.uk.md) · [English version](GSCAuxDriverx64_6.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `27EAC7BC4C03A05E3F6E8EAB3A022C6A0A21C37F51298535FD83D5CE83876D96` | `93BFA94F7CB4DBCBAB87FC7E8F15790D2718916D` | `9D68DD1B98C9AB6C157998A8D2376CFF` |

## Метадані

- **Ім'я файлу:** `GSCAuxDriverx64_6.sys`
- **Розмір:** 109256 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Intel(R) Graphics System Controller Auxiliary Firmware Interface
- **Опис:** Intel(R) Graphics System Controller Auxiliary Firmware Interface
- **Підпис:** signed
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 60

## Профіль можливостей

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpace`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
