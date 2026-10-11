# `netvsc.sys`

[Назад до індексу](../README.uk.md) · [English version](netvsc.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `0E7FF5AE75372CED3A4640D890CEB0B5CA7E018CAD491A1F541F9A620B7A0D76` | `27B17EC69728DBC2595DD344DC5F6006288025F9` | `0CB1232CE2C03BC5CBE21C969037BAFB` |

## Метадані

- **Ім'я файлу:** `netvsc.sys` (Ідентичні копії: `netvsc_1.sys`)
- **Розмір:** 398808 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** Virtual NDIS Miniport
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `MDL allocation`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmMapIoSpaceEx`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
