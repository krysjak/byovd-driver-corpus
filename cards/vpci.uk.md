# `vpci.sys`

[Назад до індексу](../README.uk.md) · [English version](vpci.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `5582D06D0CAE7C1E2D4DF659824EC9E7434C64B3F17738EF723C82DB08F389EC` | `C08586F70D99BB8B3D5556589FAC43DE73E60B1C` | `80C6399EA81B6736620CDE235126CAB7` |

## Метадані

- **Ім'я файлу:** `vpci.sys` (Ідентичні копії: `vpci_1.sys`)
- **Розмір:** 169464 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** Virtual PCI Bus
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpaceEx`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
