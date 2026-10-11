# `CmgHiber.sys`

[Назад до індексу](../README.uk.md) · [English version](CmgHiber.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `84D106B4426F90E275EE697EAD50AB46C2FBD70F3AC0BA3D5CD443C8BCC715ED` | `2A0238D9D588A0A76D0F9A7D9963864B750BA1FA` | `257ADF8EC20D905EDB70B511E1B25D31` |

## Метадані

- **Ім'я файлу:** `CmgHiber.sys`
- **Розмір:** 176864 bytes
- **Архітектура:** 0x14c
- **Компанія:** Dell Inc.
- **Продукт:** Dell Data Protection Encryption
- **Опис:** CmgHiber Device Driver
- **Підпис:** signed
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 100

## Профіль можливостей

**Primitives:** `MDL allocation`, `contiguous physical allocation`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmAllocateContiguousMemory`, `MmMapIoSpace`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
