# `xvdd.sys`

[Назад до індексу](../README.uk.md) · [English version](xvdd.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `6EBE33FE986BD78211FAA71B1F44BA651D4708E1E7197F797136BF4C73253A65` | `099A3F81652917DB8FE0B719BF63FF87A3A665F1` | `4B02439CB80BA8E3EBBF6D55229F7D51` |

## Метадані

- **Ім'я файлу:** `xvdd.sys`
- **Розмір:** 696048 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft Gaming Filesystem Driver
- **Опис:** XVD Disk Driver
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** так · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `MDL allocation`, `page locking`, `process address-space attach`, `process lookup`

**Imports:** `IoAllocateMdl`, `KeStackAttachProcess`, `MmProbeAndLockPages`, `PsLookupProcessByProcessId`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
