# `WiMan_8.sys`

[Назад до індексу](../README.uk.md) · [English version](WiMan_8.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `C29958A329A309435D910C9116081DBA5834BD13594B99D324F6EAF73B1623DF` | `D28D86C269D29581E774ED0DFD8FFCD88F64404A` | `1BA24C04F2139FE7C402196BFE8E9C8A` |

## Метадані

- **Ім'я файлу:** `WiMan_8.sys`
- **Розмір:** 152360 bytes
- **Архітектура:** 0x8664
- **Компанія:** —
- **Продукт:** —
- **Опис:** —
- **Підпис:** signed
- **Джерело:** `oem:hp`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 85

## Профіль можливостей

**Primitives:** `MDL allocation`, `physical address resolution`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmGetPhysicalAddress`, `MmMapIoSpaceEx`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
